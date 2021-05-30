# Objects:
Objects group together a set of variables and functions to create a model 
of a something you would recognize from the real world. In an object, 
variables and functions take on new names.
* *If a variable is part of an object*, it is called a 
**property**. Properties tell us about the object, such as 
the name of a hotel or the number of rooms it has. 
Each individual hotel might have a different name 
and a different number of rooms.
* *If a function is part of an object*, it is called **a method**. 
Methods represent tasks that are associated with 
the object. For example, you can check how many 
rooms are available by subtracting the number of 
booked rooms from the total number of rooms.
Ex:
```
c3/ j s/obj ect-1itera1 . j s 
var hote l = { 
name: 'Quay', 
rooms: 40, 
booked : 25, 
checkAvailability: function() { 
return this.rooms - this.booked; 
} 
} ; 
JAVASCRIPT 
var el Name = document .getElementByld('hotelName'); 
elName.textContent =hotel .name; 
var elRooms = document.getElementByid{'rooms'); 
elRooms.textContent = hotel .checkAvailability();
```
* This example starts by creating 
an object using literal notation. 
This object is called hotel which 
represents a hotel called Quay 
with 40 rooms (25 of which have 
been booked).
# Document Object Model (DOM):
The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. 
It is implemented by all major browser makers, and covers two primary areas: 
1. MAKING A MODEL OF THE HTM L PAGE .
2. ACCESSING AND CHANGING THE HTML PAGE. 

