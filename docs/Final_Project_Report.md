# Project Goals
- Develop a GUI which takes user input and runs several data programs to aggregate large data sets to a size conducive to analysis in economic models.
- Apply data structure and database skills to systematize saving and opening user data for future use (Save and Open) data functions.
- Hands on application of OOP skills (inheritance, polymorphisms)
- Stretch goal to implement multithreading application
- Deploy this GUI on an open-source platform such as GitHub

# Assessments
- Develop GUI: Achieved. Much of the front end, user interface is complete.  There are always aras to improve and extend, but the essentials of user input are programed.  I was pleased I was able to customize several of the standard PyQt GUI objects.  For example, I implemented a "paint data" feature, which allowed the user to drag data from one cell into multiple cells, saving the user time and reducing errors if they had to click on each data element and change it.  Likewise, I was able to implement sorting of user tables, to facilitate on demand analysis of user input up to that point in time.  Again, time saver and quality improvement. I developed skills in reading PyQt documentation, which is much more complicated then it might sound, since PyQt documentation is essentially written for C++ in QT.  The user has to be able to translate from C++ objects, functions, types and arguments to Python equivalents.  I also learned the strengths and weaknesses of using built in Qt data models vs. implementation of user customized data models (covered in next section).

- Apply data structure skills: Achieved.  I started out thinking I would use a db management system, like SQLite, but I was driven by the obvious fit between.  
standard Python data structures, such as dictionaries and lists and json.  A significant factor in this thinking is that much of the user data to be gathered and saved were in varying lengths - fields varied, not standard across a large set of user data.  Moreover, I wanted to leave flexibility for adding new fields as needed, with the least amount of effort.  A semi-structured data format, such as Python dictionaries and lists, saved as json was a fit which worked.  I was happy with this choice.  Late in the software development processes, I tried the user interface on an older set of data.  It turned out a couple of trivial data elements were different and crashed the program.  The fix, simply add a couple of additional fields to the json file and it was up and working.  A final benefit of using native python data objects was that I could build custom data models in PyQt using Python lists and dictionaries.  This reduced the need to select data from SQL databases and write it back.  Careful implementation of my data models, by passing them by reference to PyQt data objects meant the data were in one place.  When they changed in the user interface, they changed in the system data.  A simple "save" routine writes those objects to json. No worry about having the most up to date data. The creation of custom PyQt data model did require me to develop APIs for the Python data structures (read, write, edit, etc.).   This was very similar to writing APIs for the data structures class.

- Hands on application of OOP skills: Achieved.  I was hoping to master some basic OOP skills, such as inheritance and polymorphism, as well as learning some advanced Python coding skills, such as iterators.   I did learn a lot about inheritance, as developing custom widgets and data models in PyQt requires a mastery of these skills.  I often inherited the properties and methods of a PyQT object.  Further, I was often called to augment the built in PyQt methods via the super(). method.  The development of my custom data objects required that I master the various methods of implementing object properties and methods.  For example, I learned that the built in @property wrapper provides numerous capabilities, but it is not inheritable!   Instead, I wound up implementing the __attr__  and __getattr__ built in methods, which work much better and are inheritable.   This gave me hands on experience with leveraging and modifying built in Python methods-an advanced skill for development.

- Stretch goal, implement multithreading: Achieved.  I tried implementing the PyQt threading objects but was having difficulty with the que.  I then switched to the built in Python "subprocess” object and that worked for me.  I had to figure out how to que up programs such that those which depended on an earlier program were not run prematurely.  I did this by creating sub functions which would only run after their parents completed.  Still, this resulted in a much faster implementation than running the programs in serial.

- Deploy this GUI on an open-source platform such as GitHub: Achieved.  The files for the program are on a public GitHub site listed below. The project is set up to accept pull requests, protections on existing branches and issue tracker are set up.  There is always more to do.

# What Skills Did I Develop
- As mentioned above, working with OOP and Python built-ins was a big take away.  I always found Python built in "magic" methods to be a mystery, until now.  I now understand them much better and how to leverage them (modify) for my own use.  It also helps to understand how Python implements many of these routines.  
- I found an interesting interaction between OOP and fundamental programing concepts such as passing variables by reference or value.  This interaction is even more nuanced in Python since Python passes by attribute and by data type (static vs dynamic). 
- Developing a GUI taught me that building the user graphics is just a small part of the "system".  An effective system must test for all kinds of various issues with user input, data input, system errors etc.  It is mostly back-end programming, which may have no limit.  As a result, one should set performance goals, to balance the effort in the interface and the backend.  Without performance goals, one can spend a lot of time developing "features" for the user but are not at all stable.  If one focuses on stability alone, you are left with an app which does not do much for the user.  Balancing these competing needs to make and effective productive app is a skill to be learned.
- Developing a project for open-source development is, by definition, creating an incomplete product.  The question becomes, what level of development makes the project interesting enough for others to invest their time in extending it?  To some extent, having a solid set of core features that work well is a good goal.  Stability in the basic code would seem to be essential, to show potential contributors and employers you are competent.  These are elements one must bring to the design, development, and goal setting.   
# Reflections on How to Improve my Learning Process
- I tend to see learning as a big processes experience.  It is a biased belief that anything worth learning takes time.  However, a great deal can be learned by strategically setting smaller goals and doing a little bit each week or each day.  In fact, doing a little each week is likely to result in more learning in the end, since it is easier to fit into a busy schedule.
- In addition to targeting smaller learning goals over time, it helps to be strategic, planning and choosing one’s goals carefully to fit into one’s needs.
- I found the LinkedIn learning modules helpful and plan to use them more often.

# Link to Class Proposal and Weekly Journal

https://pedrocu.github.io/

# Link to Open Source Code Project

https://github.com/pedrocu/PyGTAPAgg

# Link to GUI Pictures

https://pedrocu.github.io/docs/progress_pics.html

