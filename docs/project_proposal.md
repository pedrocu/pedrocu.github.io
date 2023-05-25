# Vision Statement
* I will develop a simple desktop application in Python to gain experience creating a GUI to interact with users to complete tasks that otherwise would have to be run on command lines.  The GUI will streamline the running of Fortran programs to perform data jobs and analytical tasks.  
* It is my expectation that GUI programming will provide hands on experience with object-oriented programming (OOP) concepts such as inheritance, polymorphisms and Python development tools such as built in object interables. 
* The project will be published as open-source software, allowing employers to evaluate my programming skills in an application, as well as open source publishing.
# Motivation
I have wanted to do these things since first entering CSPB several years ago and now, alas, I have the chance to do it. I have always thought skills and experience developing a user interface (web or GUI) were "basic" to a computer science degree and to the computer science profession.  User interfaces can be helpful in many settings. I hope the open-source code will be helpful to the general research and code community (economics) and help prospective employers assess my skills and abilities outside of a resume and\or degrees.

# Background
I'm an economist with a great deal of background in international economic analysis.  I regularly conduct analysis of global economic policies (such as trade agreements, climate change, poverty, and food security).   You can see some of my research at: https://impactecon.com/resources/working-papers/.
# Idea
I want to develop an open-source application (GUI) to automate and facilitate routine tasks in the analysis of global economic data.  There are several data tasks which must be undertaken before a global economic study can be undertaken. Many of the tasks are routine and are currently done via "batch" files which run data programs and can take a long time to run (asynchronous).  The process is subject to errors, due to the complexities of running command line programs which processes user input in the form of text files.  I would like to create a basic Python application (PyQt) which incorporates these processes into a GUI. 
# Goals
* Create a GUI interface which gathers input from a user (input files, output location, desired file structure)
* The input from the user is checked, stored (MySQL) and passed to external program (Fortran) for running (asynchronous)
* Progress bar for programs running (they can take a few minutes or more to run)
* Task completion summary
* GUI programming in PyQT, like most GUI frameworks, is founded on objects and the concepts of inheritance, polymorphisms, and overloading.  I expect at each step to be gaining valuable experience with OOP in an application setting, applying these concepts in subclass objects to complete tasks.
* ADVANCED GOAL (if time allows)
    * Develop a multithreaded run of the external program runs (synchronous - parallel)

# Platform
Python, Windows, PyQT (GUI), harpy plugin for accessing Fortran datafiles via NumPy, GitHub, MySQL database.

# Risks
* PyQT, from what I have read, is one of the most widely used GUI programs in Python and in C++.  PyQT is essentially a C++ program run from Python, as such, it is an abstraction, which makes it a bit more complicated, especially the documentation. 
    * Mitigation - While PyQT documentation can be complex, several books have been published recently (showing the popularity of this framework) with directions and code recipes to assist with fast development.  Examples are key to rapid development in this context, and I expect those resources will be valuable.
* PyQT, from what I have read, is based on a handful of classes, with inheritance and polymorphisms used extensively to create subclasses etc.  This is a great way to learn OOP in an application context, but it can get very complicated, since one has to understand the root classes objects derive from to fully understand them and follow the documentation.
    * Mitigation - Limiting user interface features to accomplish the essential tasks and limiting "bells and whistles."  An AGILE approach of getting the application running, first, to prove the concept, even if rough.  Then improving incrementally.  
* Developing a user interface requires a lot of planning to get correct or one can waste a lot of time recreating basic things.
    * Mitigation - An old user interface developed in Delphi is available (code is not open source or easy to adapt).  The interface is 20 years old, but still provides a basic framework of what the user expects, so I plan to use that to plan the basic interface, and make extensions from there.
* Multi-threaded applications can be much tricker to run than might first appear.  If intermediate files are not ready when called, the program will fail. 
    *  Mitigation - This is an ADVANCED GOAL.  PyQT provides a threading object and queue, but with these applications, I suspect the order of program runs is still a problem to be solved by the programmer, so I will first program an asynchronous application in the AGILE spirt of getting it working first.



# Project Assessments
# Project Portfolio Link
Assume it is this page


[[Return to Home Page]](https://pedrocu.github.io)
