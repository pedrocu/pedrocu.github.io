# Week 3

## My First Window
![Week-3](https://pedrocu.github.io/pics/Week3_image-1.JPG "First Window")
![Week-3](https://pedrocu.github.io/pics/Week3_image-2.JPG "Added Tabl")
# Week 4

## Adding some tab widgets and getting data from external files
Learned a bit about using windows registry to strore setting from one session to another.
![Week-4](https://pedrocu.github.io/pics/Week4-image-1.JPG "Populated Database Tab")

# Week 5
## First selection tab 
This was alot more work than I had expected, but worth the late nights.  I expect the other tabs will go much faster now that the first template is done.
I have put underlying data into the table using temporary tricks.  The next step is to develop a solid data model fit for this purpose, likely save to Json and manipulate in Python dictionary.

![Week-5](https://pedrocu.github.io/pics/Week5-image-1.JPG "Populated Sectors Tab")

# Week 10
## Long time working on the data structures

Sorry not to post pictures for so long.  I was deep into the code, very little was getting done on the GUI, since I wanted to figure out a good way of keep the data in the tabs up to date and make it consistent and easy to "Save" the users work into a file.  I wound up using a JSON format to “Save” and "Open" the data.  This required a lot of work on the basic "sectors" tab along with creating a data object and testing.  After that was done, the next two tabs were straight forward, since I used OOP.

![Week-10](https://pedrocu.github.io/pics/Week10_image-1.JPG "Populated Regions Tab")

And the "Endowments" tab.

![Week-10](https://pedrocu.github.io/pics/Week10_image-3.JPG "Populated Endowments Tab")

I won't post all my open and save screens, since I used the system GUI and we all know wha that looks like.  Note the default *.json format, that is the format I used to save the data and retrieve it.

![Week-10](https://pedrocu.github.io/pics/Week10_image-2.JPG "Populated Open File Dialog")

And, for good measure, I added an about dialogue.

![Week-10](https://pedrocu.github.io/pics/Week10_image-2_5.JPG "Populated Open File Dialog")

# Week 11
## The output Tab

This is what it is all heading to.  The real work.  Running the programs based on the user input.  

First, the very basic tab - 

![Week-11](https://pedrocu.github.io/pics/Week11image-1.JPG "Populated Output Tab")

Now the progress bar - note, this is using multiple threads as multiple programs are running at the same time.  This was a bit tricky, since some routines had to be run after another had completed, though the whole lot of them are not serial.  

![Week-11](https://pedrocu.github.io/pics/Week11image-2.JPG "Populated Status Bar Running programs")

and it completes!


![Week-11](https://pedrocu.github.io/pics/Week11image-3.JPG "Populated Status Bar Running programs")

