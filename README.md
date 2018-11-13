###### Started Oct 1,2018

# WildWorld-Fishing-Guide
A month by month guide for fishing in Animal Crossing: Wild World

### News

#### Project Update
###### **Posted 11/13/18**

Finally finished the whole functionality of the Fishing Guide, I'll put up a Codepen in a bit to show the very bare bones demo that would make a skeleton blush. Currently the **index.html** file in the **root** folder is the most current version as of typing. To summarize everything though:

* Now there's a set of buttons for each month that when clicked will process the **fishList.js** array to filter it to find which fishes appear in the month selected.
* It will then output that array within a table (which I just realized still uses an old ID! :flushed:) which displays the fish's name, location, daily availability and monthly availability.
* Also when a button is clicked a few things happen:
   * It will check if the table has anything within it and clean it out if it does.
   * Extract the value from the button and text which are used for the filter and title tag respectively.
   * Then it starts the filter function.
   
So next steps will be the design but I also want to make sure my JS/jQuery is up to snuff, because while building this I read a few articles detailing scope, etc which I might not be up to speed on. So rather than ignore it and say "Hey, it works right?" I'm going to learn now to help myself and others in the future.

Also! Within the **index.html** file there's a little bit of extra code to output the entire **fishList.js** array in the console. This won't be in the final product, it's just there for my reference and anyone else who needs it.

Thanks and have a great day! It's lunchtime for me now. :weary:

#### Project Update
###### **Posted 11/12/18**

Updated the branches by removing "JS + jQuery" branch and creating a new one to contain all code changes named "Dev". I felt it would make it easier and more general instead of the old name which implied that only changes to the JS or jQuery was only made. Today I'm also hoping to rebuild the index to be a bit more cleaner as the current one has multiple lines of JS with some commented out which makes it harder to read.

So some tasks for today:

* Make a clean main index file that contains the most update code
* Create a new folder that will contain WIP index files, possible in separate folders if anyone else wants to work on it or name the index file as such: index-yourusername.html

Thanks for reading and have a great day! :yum::+1:

#### Project Update
###### **Posted 11/07/18**

Made a branch for JS + jQuery to test functions. Updated the index file to test filter by filtering fish by several that are available all year.

#### Project Update
###### **Posted 11/06/18**

Added completed object list with all the data in it and updated the index page to display the outputted data as a table.

#### Project Update
###### **Posted 11/05/18**

It's been awhile since I touched this project but I'm back to work some more on it. Currently I've been working on the JS list of fish which I will upload today after this README update. It contains the fish in an object list which is what will be referenced when it outputs that data based on the month selected.

That's pretty much all for now but I hope to have more done within the week, hopefully the design! :relieved:

#### Fish Data Update
###### **Posted 10/03/18**

So this morning I went quickly over the current spreadsheet while doing some back and forth between sources. So I have updated the fishes that have specific end dates to their availability (ex, they can be caught until Sept 15th) and sorted out dates that have disrepency by going with the ones that have a majority across different sites. Still if there's any errors please feel free to open an issue to point it out and update the public spreadsheet.

Thanks and have a great day! :smiley:

---

### Current Tasks

* ~~Gather fishing data in spreadsheet~~
  * ~~Make sure data is accurate~~
* ~~Organize data into months~~
* Build out basic HTML layout for guide (preferably in a calendar/bulliten format)
  * Graphical style to match Animal Crossing series or Wild World graphics

---

### Important Links

**Fishing Data Googlesheets**
https://docs.google.com/spreadsheets/d/16NFsjjyIcPFiZerwo5Fc6RRLgrcETTHFPXEcyd6s73o/edit?usp=sharing  
*Updated 10/03/18*
