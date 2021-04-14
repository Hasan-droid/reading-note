# what github?
## Hasan Test

## introduction 

### before git hub

*Version Control*
>is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control
>
three types of version control
1. Local Version Control
2. Centralized Version Control
3. Distributed Version Control

**Local Version Control**
>Many years ago, programmers created Local Version Control systems. A Local VCS entails one database on your hard disk that stores changes to files.
>

**Centralized Version Control**
>The need for collaboration within a developer team on a single file or set of
> files led to the advent of the Centralized Version Control System (CVCS).
>  This system entails a single server storing all changes and file versions, which can be accessed by various clients.
>  
this system has a major problem which is >
collaborators cannot work with each other on a file or save changes and new versions.
Also, in the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.
>
the solution comes with **Distributed Version Control**
>To prevent this type of catastrophic loss,
> a DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.
> 
![image](https://user-images.githubusercontent.com/54712715/114395449-0cb48b80-9ba5-11eb-8bae-c68cead5c8a5.png)

### so what is github ?

1. *Snapshots*
stores the data as snapshots , > 
> each timyou save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it
> 
2. *Local Operations*
information are stored on local resource 
>eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.
>
3. *Tracking Changes*
track the process
>Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.
>
4. *loss of Data*
the data has stored successfully and safely
>Git is set up to greatly minimize the possibility of irreversible damage to files,
> such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.
>
5. *state*
where the proccing is now ?
 - Committed
 - Modified
 - Staged
 
![image](https://user-images.githubusercontent.com/54712715/114396458-476af380-9ba6-11eb-932a-a89dc74f7b33.png)





