# Local Storage :

persistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.

Historically, web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

* **Cookies** are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
* **Cookies** are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
* **Cookies** are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful
What we really want is
a lot of storage space
on the client
that persists beyond a page refresh
and isn’t transmitted to the server
Before HTML5, all attempts to achieve this were ultimately unsatisfactory in different ways.

## HTML Storage:

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.
```
interface Storage {
  getter any getItem(in DOMString key);
  setter creator void setItem(in DOMString key, in any data);
};
```
`Calling setItem() `with a named key that already exists will silently overwrite the previous value. `Calling getItem()` with a non-existent key will return null rather than throw an exception.

Like other JavaScript objects, you can treat the localStorage object as an associative array. Instead of using the getItem() and setItem() methods, you can simply use square brackets. For example, this snippet of code:
```
var foo = localStorage.getItem("bar");
// ...
localStorage.setItem("bar", foo);
…could be rewritten to use square bracket syntax instead:

var foo = localStorage["bar"];
// ...
localStorage["bar"] = foo;
There are also methods for removing the value for a given named key, and clearing the entire storage area (that is, deleting all the keys and values at once).

interface Storage {
  deleter void removeItem(in DOMString key);
  void clear();
};
```
Calling removeItem() with a non-existent key will do nothing.

Finally, there is a property to get the total number of values in the storage area, and to iterate through all of the keys by index (to get the name of each key).
```
interface Storage {
  readonly attribute unsigned long length;
  getter DOMString key(in unsigned long index);
};
```
If you call key() with an index that is not between 0–(length-1), the function will return null.



### HTML5 Storage specification:

Introduction to DOM Storage on MSDN
Web Storage: easier, more powerful client-side data storage on Opera Developer Community
DOM Storage on Mozilla Developer Center. (Note: most of this page is devoted to Firefox’s prototype implementation of a globalStorage object, a non-standard precursor to localStorage. Mozilla added support for the standard localStorage interface in Firefox 3.5.)
Unlock local storage for mobile Web applications with HTML5, a tutorial on IBM DeveloperWorks
Early work by Brad Neuberg et. al. (pre-HTML5):

Internet Explorer Has Native Support for Persistence?!?! (about the userData object in IE)
Dojo Storage, part of a larger tutorial about the (now-defunct) Dojo Offline library
dojox.storage.manager API reference
dojox.storage Subversion repository
Web SQL Database:

Web SQL Database specification
Introducing Web SQL Databases
Web Database demonstration
persistence.js, an “asynchronous JavaScript ORM” built on top of Web SQL Database and Gears
IndexedDB:

Indexed Database API specification
Beyond HTML5: Database APIs and the Road to IndexedDB
Firefox 4: An early walk-through of IndexedDB
