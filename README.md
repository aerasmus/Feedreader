# Feed Reader Testing Project
The project focuses on testing javascript code with [Jasmine](https://jasmine.github.io/ "Jasmine"). 


## How To Run
---
* Download or clone the project repository.
   
* Navigate to projects files.
    * Unzip files (*if you downloaded zip file*).
    * Locate directory where files were cloned to

* Open up index.html file.

## Tests Performed
---
* RSS Feeds

    1. It must have URl' loops through each feed and it must not be empty.

    2. It must have name'loops through each fedd and it should not be empty.

* The Menu

    1. The Menu should be hidden by default.
    
    2. The Menu should open and close upon a click on the hamburger button.
 
* Initial Entries

    1. When loadFeed function is called and completes its work, there should be at least one .entry element within .feed container.

* New Feed Selection

    1. Contents should change when new feed is loaded.