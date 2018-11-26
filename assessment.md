# Password Vault Assessment

## **1 - Development Methodology**

For the purpose of this assignment, we will be using Agile software development methodology. The reasons for that are numerous, but the major ones are 1) speed of development 2) source code quality 3) visibility of the development process and 4) flexibility. 

### *1) Speed*

The speed is increased with Agile approach due to the use of several branches, where you implement and test different features by putting them into diffent branches not to affect the major code. 

### *2) Quality*

The quality is increased with agile, because testing of the code is integrated into the process of writing a code. The code is not only tested when the final version is ready, but during each stage of the code development. By doing this, once can insure the final code comes up with a higher quality and requires less testing.

### *3) Visibility*

With visibility the code is being constantly shared with potential users and also with other developers, who can comment while the code is in production. This allows to avoid many common mistakes early in the process and also saves valuable tiime.

### *4) Flexibility*
Flexibility of agile allows to make quick and frequent changes to the code, unlike in the traditional software development mode, where the scope change is a diffifcult and slow process.

## **2 - Source Control Software**

We will be using Git and Github tools for the source countrol. The reason for that is the Git allows 1) version control and changes tracking 2) repositoty management 3) coordinated access to many people. Github allows to store repositories in a cloud for storage and remote access.

### *1) Version control*

Git allows to easily control different versions of software with branching and other tools, i.e. tracking changes and returning back to the working release quickly.

### *2) Repository management*

Git allows to alter the code on the machine, while not commiting it to accept the change and without pushing it to Github until one is competely sure the code is working as expected. Repositories can be cloned from Github to a local Git repositoty and back and also they can be forked from one user to another.

### *3) Coordinated access*

There are also messanging and task assignments tools for better project management. These tools allow several people (normally a project lead and other coders) to quickly assign tasks to each other and check their execution and quality.

### *4) Remote access and storage*

Github allows to store repositories remotely (on Github cloud) and access them from anywehre with any device. It also provides a backup feature, when if local repository is lost, it can be cloned back from Github.

## **3 - Project Management Software**

For project management we are going to use Trello. The reason is it allows to create quick "sticky notes" on a screen with very simple layout. It allows move the sticky notes arround, alter and delete them. Also, Trello allows assigning the deadlines and adding a lot of other userful information to each note separately and combine them into different tasks. The simple layout allows three major buckets, such as "to do", "doing" and "done" and track the progress of a project, becoming a simple form of project management. It also allows for remote access for main user or other users to, for example to allow a manager to track performance of a reporting emoployee.

## **4 - Collaboration Software**

For collaboration we will be using Github, the reason is that it is cloud based and can be easily accessed by many users simultaniously. Github allows forking repositories and cloning them to local machines, allows assigning different tasks for different users and tracking the performance. It also tracks the access rights and who can assign tasts to whom, making it more convenient to manage a large project. Github also allows to create branches, where each branch will represent a separate feature and then it allows assigning specific people to specific branches, track their performance and also merge the working code back to a master branch when ready.

## **5 -- The Purpose of Developing Secure Password Vault App**

The purpose of developing the secure password vault application is to allow a user to securely store numerous user names and passwords from many resources in one simple secure and remote location. This will allow the user to only memorize one user name and password and use it every time the user wants to be authenticated into a resource. This allows easier password management and actually allows to use safer and longer computer generated random passwords instead of short words, wbich can be easily remembered, but also easily hacked.

The two security features, which we are going to use in this application are **authentication** and **encryption**. Authentication protects an unathorized access by requesting a user name and password to access the resource, while encryption provides a more secure way for communication by not sending a clear text information. The encryption can be assymentric, where different passwords are used to encrypt and decrypt the message (as an example - private/public keys) or symetric, where the password for encryption and decreaption is the same. Even when the password is the same, the clear password is not normally send over, instead the hash function is being transffered and then compared with a hash function stored remotely to grand the access.