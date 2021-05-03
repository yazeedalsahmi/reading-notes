# What is the Git ?

Befor we talking about git we have to first explain various aspects of ***Version Control ***:
## Version Control
Version control is the system that saving diffirent changing you do on files that you can revisit the various varsions of the files ,that help you revert a file or project to a previous version, track modifications and modifying individuals, and compare changes.So mistakes with files can easily be rectified.
### There are some types of Version control :
1. **Local Version Control:**
 A Local VCS entails one database on your hard disk that stores changes to files.
2. **Centralized Version Control :**
This system entails a single server storing all changes and file versions, which can be accessed by various clients.This streamlined the collaboration process (by eliminating the need to involve all local databases), allowed programmers to have more knowledge of team members’ activities with certain files, and gave administrators much more control over divvying up revision privileges.
![center](https://www.edureka.co/blog/wp-content/uploads/2016/11/Centralized-Version-Control-System-Workflow-What-Is-Git-Edureka.png)

3.** Distributed Version Control**:
A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. Also, in the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.
To prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.
![Distributed](https://www.edureka.co/blog/wp-content/uploads/2016/11/Distributed-Version-Control-System-Workflow-What-Is-Git-Edureka.png)
##  What is the Git ?? 

![git](https://1000logos.net/wp-content/uploads/2020/08/Git-Logo.png)

With Git, one gets to know about an open-source distributed system. When software is developed, there is a need to track the incurred changes in the source code. It performs the work to track these changes. Linus Torvalds launched this system during the time period of 2005. Junio Hamano is the present person who is maintaining this system. When there is a need to coordinate a certain set of work to the programmers, it can perform this function easily. With a data integrity feature, it has become a widely popular system.
Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.
- **local operations** 
Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.
- **Loss of Data**
Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.
- **States**
Files in Git can reside in three main states: 
1. ***committed*** : Data is securely stored in a local database.
2. ***modified*** :File has been changed but not committed to the database.
3. ***staged*** :Flagged a file’s changed version to be committed in the next snapshot.

