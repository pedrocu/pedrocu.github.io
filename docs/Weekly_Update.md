# Weekly Updates

1. What did you do last week?
2. What do you plan to do this week?
3. Are there any impedments in your way?
4. What were the processes you used last week, how can you make the process work better?

## Week 1
No reporting required

## Week 2

1. What did you do last week?
    - Read all the course descriptions and requirements
    - Coded and posted web pages on github
    - Wrote questions and responded on piazza
    - Drafted a project proposal
    - Read background materials for proposal 
2. What do you plan to do this week?
    - Refine proposal, post, get comments feedback
    - Identify resources materials, online, textbooks etc.
    - Read more background materials to identify potential stumbling blocks
    - Develop reading list for coming weeks to sync tasks with new knowledge
3. Are there any impediments in your way?
    - Summer!   Really, summer requires extra attention to putting in the time required.  Keeping a good tempo will be important
4. What were the processes you used last week, how can you make the process work better? 
    -   I reviewed the requirements and made a list of tasks, which was a bit iterative.  One of the mistakes I always make in CSPB courses is not looking ahead to next week’s assignments, before making up a workplan.  Often the following week's task or description provides important information relevant to the current week's work.  Be tactical and strategic, look ahead.

## Week 3

1. What did you do last week?
    - Finalized proposal
    - Developed work schedule
    - Downloaded and read PyQt books (4 chapters)
    - Downloaded and started to read OOP documentation
    - Wrote first PyQt code to create dialogue box
    - Fixed up git website (added Jekyll config file)
2. What do you plan to do this week?
    - Plan application layout
    - Consider open-source issues (what will make my app attractive for others to use\contribute)
    - Develop main screen for application
    - Keep reading PytQt documentation
    - Look at linked-in
3. Are there any impediments in your way?
    - Main issue is time.  Being Summer and my son is in day camp, I have short days to work with.  
4. What were the processes you used last week; how can you make the process work better? 
    -   Setting a work agenda is key, as it allows me to just sit down and start working, not wonder first about what I must do.  
    -   Make setting weekly work agenda on Monday priority (this is rather detailed list)
    -   Check the agenda again on Wednesday (in most cases I can add to it)

## Week 4

1. What did you do last week?
    - Read PyQT (3 chapters)
    - Started repo for my program files
    - Started reading OOP
    - Finshed app layout (this will be modified as I go along, but it is a broad brush to keep focused)
    - Developed main screen for application
    - Continue to improve github web site 
2. What do you plan to do this week?
    - Finish first tab to read in database location and specifications
    - Develop methods for saving settings from one session to the other (use PyQt Settings class)
    - Start second tab for sectors (work on PyQt data API)    
    - Work on linked-in
3. Are there any impediments in your way?
    - Reading and working on code is a great combo, theory and applications work well for me, but application often requires more th
    - en just theory, it require experience. 
4. What were the processes you used last week; how can you make the process work better? 
    -   Setting a work agenda is key, as it allows me to just sit down and start working, not wonder first about what I must do.  
    -   Get more reading in at odd hours (down time) by having it on mulitple computers synched up
   
## Week 5

1. What did you do last week?
    - First tab done, reads in data location and verifies if database is valid, returns an error box if not valid
    - Integrated method for saving users state between session using PyQt Setting Class
    - Started sectors tab (tab 2) by creating layout (vlayout and hlayout, with buttons)
    - Read up on best practices to create a linked in site, talked to friends who have done it about pros and cons
3. What do you plan to do this week?
    - Continue to develop second tab for sectors (this tab will be used as a template for other tabs, so want to get it right)
    - Develop code to make tasks for user more efficient (painting data, quick selection)
    - Review options for saving application data (for datafiles in contrast to user settings)
        - SQLite
        - Json
    - Continue to work on linked-in
4. Are there any impediments in your way?
    - None 
5. What were the processes you used last week; how can you make the process work better?
    - Working with Qt documentation helps a lot, essential.  Qt documentation is written in C++, not python.  Getting to know the structure of objects within Qt and inheritances, along with enums is essential.  It takes time to look up all the options and configurations with the enums.
    - Solution: study the overall object structure and inheritance hierarchy within Qt so I can access required information more efficiently.
  
## Week 6
1. What did you do last week?
    - Studied data structure for data persistence between sessions (MySQLite or Json data formats)
    - Decided to use Json, since it can store lists and dictionaries in an easy to access structure
    - Many of my tasks will be manipulating lists, so putting and extra level of abstraction in the form of SQL added unneeded complexity 
    - Worked on creating an initial data structure in the form of a Json file with data (dictionaries and lists (these default templates required a lot of custom data to start off the program      
2. What do you plan to do this week?
    - Now that I have decided on a data structure to persist data, and the default file is setup, I need to integrate the Json data into the interface (now, I have some lists shoehorned into the model in place of a data structure.
    - Integrating the data model will require careful placement within the interface to leverage object inheritance and reduce duplication and unneeded read and writes.  
3. Are there any impediments in your way?
      - Yes.  Experience with OOP, inheritance, signals, and slots.  It is one thing to study this material and understand how it is implemented, it is another thing to implement a structure which serves the purpose well.  I must dive in a try my best idea and see how it plays out (learn the pros and cons of my approach).
5. What were the processes you used last week; how can you make the process work better?
   - The process has changed entirely.  I have gone from studying PyQt documentation to planning strategy around various programming structures to achieve my goals.  This is planning and implementation, so the processes are different.  I consider, look at existing code, and adapt as needed, while anticipating potential problems.

## Week 7

1. What did you do last week?
    - Coded a class object to hold data and processes it.
    - Used PyQt Signals and Slots to create connections to events which change the data in the data object (changing data directory or changing aggregation file).
    - Read in JSON file and sets file, merge them by codes using a dictionary and list structure which is efficient (essentially a hash index with a merge).
    - Passed data to the tab "by reference" which means when the data in the application tables changes, the data in the data object will also be changed, reducing unneeded code and improving efficiency.
    - Tested code on sectors tab.
2. What do you plan to do this week?
    - Cleanup class object code, with properties and setters and getters as required.
    - Develop an interface and code to "save" a new data object and retrieve it.
3. Are there any impediments in your way?
      - No.  
5. What were the processes you used last week; how can you make the process work better?
   - I studied the code a great deal to figure out where to put the data object and how best to apply it before I started coding.
   - In the future I will create a sandbox to test ideas sooner, with less concern on getting it correct the first time, since I found I spent several hours simply studying the code and considering options.  While that worked, it seemed a bit time consuming.


