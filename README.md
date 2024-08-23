# Operating-Platforms-C-4
Operating Platforms for future clients 
"Draw it or Lose it"
Document Revision History

int tilte and name of author;//Version	Date	Author	Comments
1.0	08/23/2024	Michael Sanchez	Creative Technology Solutions {game designer wants to develop a web-based game that can be played on multiple platforms}. 
/
Instructions: 
Insert paragtaph; 1) The software or game is hosted in a distributed environment. It means it is network intensive and actual game runs on the application servers and the inputs are taken through client applications, processed at servers and output is rendered on the client screen. 2) Traditional Desktop Platforms and modern mobile platforms are included -in such a way that it is like a web app that shows html responsive window through a browser. Regardless of the platform, every platform has a separate set of development Tools, APIs and programming languages. Web apps also have the advantage of being easy for you, the developer, to update. Install a new version of your app on the web server and bingo, it's available instantly to every user.
The downside to creating web applications is that making them super-responsive can be difficult to impossible, especially if the app will rely on data from the server. Because you don't control the Internet, performance can vary from hour to hour or day to day depending on the status of the Internet.
First, we can discuss the server-side implementation and related facts and figures, then we can discuss the client-side implementations.;
Executive Summary:
Insert pargraph; Due to the sudden rise in demand for mobile Application and web-based games, Creative Technology Solutions (CTS) has recently taken on a new client, The Gaming Room. The globe has experienced difficulties in developing Lose It or Draw It games that serve multiple platforms. One of the common challenges is that the players were drawing images on an easel to help team members guess the puzzle, which led to the delay and less enjoyment of the game. Another difficulty is the sudden rise in demand experienced in creative technology solutions where people request new games that serve different environments. Creative technology solution has decided to develop software where Lose It or Draw It games are deployed in diverse playing environments. The Gaming Room will develop a web-based game that serves multiple running environments based on their current game, Draw It or Lose It, which is currently available in an Android app only. The application will render images from a large library of stock drawings as clues rather than a player drawing images on an easel. The Gaming Room would like to create a web-based version of their current Android game, Draw It or Lose It. Draw It or Lose It is a multiplayer picture guessing game, like Win, Lose or Draw from the 1980’s. The web-based version of their game needs to serve multiple platforms, not just Android exclusively. The Gaming Room has outlined a few requirements, which will be described in the Design Constraints section below.;
Requirements:
< Please note: While this section is not being assessed, it will support your outline of the design constraints below. In your summary, identify each of the client’s business and technical requirements in a clear and concise manner.> 
Inter strg //Design Constraints:
When developing web-based software, there are a few design constraints which you need to consider. Software designing is among the most relevant stages when developing an application. Examples of these constraints are UML diagram, class diagrams, and ESS diagram. These examples are non-functional elements which enable the software developer to have a visual awareness of the required application. These constraints imply the main artifacts, actors, actions, classes, and roles, which letter allows for better understanding and documenting of the developed software. They further provide the developer with the programming tools required, technology requirement, and other important requirements from the customers. 
•	The game must be a web-based application and run in multiple different environments (iOS, Android, Windows, Mac, etc.)
•	The game must utilize network connections to allow for multiple players to connect to the same game instance.
•	The game must have unique team-names and must allow users to check name validity before submitting a team name for themselves.
•	Only one instance of the game may exist in the system memory at any given time, so that all players will be connected to the same game.;
/
System Architecture View:

Please note: There is nothing required here for these projects, but this section serves as a reminder that describing the system and subsystem architecture present in the application, including physical components or tiers, may be required for other projects. A logical topology of the communication and storage aspects is also necessary to understand the overall architecture and should be provided.;

int string Domain Model:
The most object-oriented programming principle applied in the UML diagram below is inheritance. It has enabled the singlectonTester class to perform activities and responsibilities inherited from the main class. The singlectonTester class inherits from program Driver class which is the main class as shown below. It has seven classes, namely, program Driver, Game Service, Team, Singleton Tester, Entity, Player, and Game. Entity class as a parent interface relates to the four child classes. Game Service, Game, Team, and Player relate to each other in an association relationship where each entity depends on the other one.;
/end
Evaluation:
int string//Using your experience to evaluate the characteristics, advantages, and weaknesses of each operating platform (Linux, Mac, and Windows) as well as mobile devices, consider the requirements outlined below and articulate your findings for each. As you complete the table, keep in mind your client’s requirements and look at the situation holistically, as it all must work together.; 
/
int tables Development Requirements	Mac	Linux	Windows	Mobile Devices
Server Side	 Mac is the most expensive of the brands, but it has good app abilities.
Characteristics include web hosting and flexible terminal commands.
The advantages are that Mac makes good upgradable equipment. It has different options for web browsing requirements.
The disadvantages are it’s not the most preferred for web browsing.  	
Macs can be used as a server, although the licensing is expensive, and you must have Mac books to develop.
/
	Linux has a lot of the same features as Mac, but it’s more cost effective and efficient. 
Characteristics include being one of the most preferred and is more secure. 
The advantages are the preferred choice of web server, and the security is better. Most flaws are caught before it becomes an issue later.
The disadvantages are that it is difficult to find and use applications.  Linux is well equipped for a web-based hosting situation. It is the most popular of these and is free as far as licensing goes. 
 	Windows has more software choices than the other OS Systems.
Characteristics are more dominant to other platforms.
The advantages are that Windows has less loading time and higher comfort while using the platform.
The disadvantages are it is easily susceptible to viruses and the tech support is not the best.  Windows has server and they are very secure and easy to set up and use. But the licensing is expensive.
/
 	 Mobile Devices are widely the most popular operating platforms right now. 
Its characteristics are portable and easy to use. 
The advantages are better compatibility and is more cost effective.
The disadvantages are poor security. 
Although mobile devices can be used as servers. They are not quite equipped to excel at it. They lack the power for high end. It could be used for development though.
/
Client Side	Much time is required to access the software
High expertise required to develop software for clients who pertain to Mac.
It is expensive as the clients are charged monthly. Mac has good and easy to use SDKs, but the thing is you must have a Mac Book to develop for Mac. This will add up cost and require someone that has developed swift. 
	It is expensive as it’s not popular.
Requires high expertise as few applications are available.
 Less loading time.
a) Development Tool/IDE - Eclipse is the most popular
b) Programming Language - C is the default template to use.  The cost for this would be highest in development time, you also must have someone that is used to using python.  	It is expensive as more resources are required.
Less loading time.
It requires a high expertise as it has high resource requirements.
1) Desktop Application - Windows
On Windows we use the following technologies. 4) Web Application
A web app is really two apps.
1. One app runs in the user’s browser
2. while the other runs on a server.
Now we must deal with one run on the browser
The default technology stack consists of HTML, CSS, JAVASCRIPT.
one running on the server is supported by server-side languages like PHP
Now we have the modern frameworks such REACT, ANGULAR JS etc...to build front ends. The expertise is probably the highest requirement for Windows. Would highly recommend using the .NET framework for security and capability.	It takes less time to load a page 
It is common and therefore, it has high technical support for the clients
It is cost-effective Development Tool/IDE - Visual Studio
b) Programming Language - Visual Basic (default)
It is very hard to develop network-oriented apps with visual basics. But still, it is possible. 5) Mobile Application -Android
development Environment - Android Studio (default)
Programming Languages - Java, Kotlin. 
For mobile devices you want to find developers that have experience developing apps. User interaction and how things are displayed need to be taken care of differently than on the web.
Development Tools	Languages consists of HTML/CSS/JavaScript while it has libraries to support the front-end and general-purpose languages. These can be Java, Python, and PHP. 2) Desktop Application – Mac
On Mac we are using the following technologies,
a) Development Tool/IDE -Xcode
b) Programming Language - Swift (or Objective).  A Mac Book that has iCode on it. All coding will be done using swift.	Languages consists of HTML/CSS/JavaScript while it has libraries to support the front-end and general-purpose languages. These can be Java, Python, and PHP.   
Python is already installed on most Linux distributions. You could use IntelliJ’s Ultimate IDE to code for this. 	 Languages consists of HTML/CSS/JavaScript while it has libraries to support the front-end and general-purpose languages. These can be Java, Python, and PHP. 
Visual Studio Code is the standard and best way to code Windows applications. You could use relatively any language but C++ or c# is what most Windows programs are written in. 
	You can create countless applications using Android and IOS.
Both languages and software can run on all three.
Languages consist of HTML/CSS/JavaScript. 
5) Mobile Application -iOS
a) Development Tool/IDE -Xcode
b) Programming Language - Swift
In each cell, remove the bracketed prompt and write your own paragraph response covering the indicated information.
There are 3 options as far as mobile goes. Android’s you will need someone that specializes in Android Studio to develop the app. For iPhones you need someone that has a Mac book that can develop using swift in iCode. Or you can have someone develop the app using unity. Which is C++ and then can convert to either an android app or an iPhone app. But you will still need a mac to convert it to an iPhone app.;
/end tables;
/
Recommendations:
insert paragraph: Analyze the characteristics of and techniques specific to various systems architectures and make a recommendation to The Gaming Room. Specifically, address the following:
Operating Platform: Windows Operating platform highly secured with less loading time and is relatively cheap. It is the recommended environment as it is common in developing web-based software. It is compatible and portable therefore suitable for the development of the Lose It or Draw It game. I highly recommend using Linux Ubuntu Server to host Draw It or Lose It on a Kubernetes cloud setup.
Operating Systems Architectures: The Windows operating platform is a preemptive and reentrant operating system designed to work with either symmetric multi-processor or uniprocessor. It uses packet driven I/O to process input/output requests. It has two main components, which are the user model and kernel model. The kernel mode has unrestricted access to the system memory and external devices while programs and subsystems in user mode are limited in terms of what system resources they can access. The Linux kernel is stable and secure. The Kubernetes clusters allow easy separation of system and even hardware needs.
Storage Management: Due to its high compatibility database management System is the best storage system that will work effectively and efficiently with Windows. It is easy to use and runs on multiple operating platforms. It is also highly adaptive, therefore suitable for Windows. Can either use a HDD storage or a SSD storage but I recommend the latter. The SSD will allow for faster access to assets, having to load the pictures to users’ devices. This will be helpful with user experience. To optimize storage, I recommend setting up a Kubernetes node for file storage and a NoSQL node for game data and user management. In the NoSQL link the URL to the location of the picture.; 
Memory Management: insert sentances// Windows applies page file system technique where Windows will start removing pages of memory out of RAM and store them temporarily on the hard disk when the amount of memory for the Draw It or Lose It software exceeds the of RAM available. Another technique applied is the memory compression technique to accommodate the heavy use from the Draw It or Lose It software, which will increase the responsiveness of the operating system. To assist with costs, I recommend setting up a watcher for the load on the system. That way when usage is low you can lower the required memory and during peak times you can add all that you need so that you will only have to pay for what is necessary to give the best experience.;
Distributed Systems and Networks: insert pargraph:the distributed system will use hubs to connect multiple computers such that when one computer crashes, the game still operates by using LAN as the networking technology. Having LAN as our reliable network and Hub as the connectivity hardware, it will help the system to have a small outage overall. The hub will also serve as a repeater to amplify the signals that deteriorate when travelling for a long distance. Being as your system will be in the cloud if there is a required minimum on the servers your game will not have to stop. You can just move the node to another server or if the system crashes another server will start automatically. Going this route will allow you to host everything you need to run the game except for on the client end. This will allow all operating systems to have a client match that can access that information. Separation of functions that Kubernetes provides easier management and organization of your system.;
Security:
insert sentances:Protection measures will be put into consideration to ensure the clients’ details are secured. Due to the high security capabilities for Windows operating platform, the user protection against intruders will be higher. The encryption of the clients’ particulars will be the basis of security for this application. I recommend using a role-based security system. It will serve your needs best and allow separation from admin, game, team, player, and user. With this you can make it so that a user cannot access information that they should not.
Insert sentances;
Project Summary:
insert sentances: For this course project, I developed a C++ program that reads data from a text file, performs various mathematical operations on the data, and outputs the results to another text file. The goal of the project was to demonstrate my proficiency in C++ programming and my ability to design a functional program that meets industry standards.;
/
Particularly Well-Done:
Insert sentance:I believe I did particularly well in designing my program's architecture and organizing my code. I spent a significant amount of time planning and considering the most effective way to implement the various operations required for the project. I also used modular programming, dividing the program into smaller, more manageable components to make it easier to understand and maintain.;
/
Potential Improvements:
insert sentances:There is always room for improvement in any project, and my program is no exception. One area where I could enhance my code is by using more efficient algorithms for the mathematical operations. For instance, I could explore more advanced numerical methods to improve the accuracy and speed of calculations. I could also improve the program's security by implementing more robust error handling and input validation routines.;
/
Most Challenging Piece of Code:
insert sentances:The most challenging piece of code was the file I/O operations, especially reading and parsing the input data file. To overcome this challenge, I had to research and study various C++ libraries and functions that are designed for working with files. I also sought advice and feedback from my peers and instructors.;
/
Transferable Skills:
insert sentances:The skills I learned in this project are transferable to other projects or coursework. For example, my experience in designing a modular program will be useful in developing large-scale applications. My proficiency in using C++ libraries and functions will also come in handy when working with other programming languages.; 
/
Maintainability, Readability, and Adaptability:
insert sentances:To make the program maintainable, readable, and adaptable, I followed several best practices. I used meaningful variable names, wrote comments to explain the code's functionality, and used consistent coding style throughout the program. I also tested my program thoroughly, both with valid and invalid input data, to ensure it is robust and adaptable to different scenarios.;
/end;
/
