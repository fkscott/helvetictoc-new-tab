# Helvetictoc New Tab
===============

![new tab page](./screenshots/new-tab.png)

A time-full tribute to a timeless typeface in your new tab page.

I always loved this site so I figured I would turn this into something I could see every time I opened a new tab in Chrome. 

I also removed all the references to Ruby Make since the JS has been stable for 12 years. Feel free to fork this and mess with the fonts and background.

## Installation

1. Clone this repo or download its contents in a zip file.

2. Unzip the folder if you haven't already.

3. Once extracted, navigate to [chrome://extensions](chrome://extensions) in your browser and make sure you have "Developer Mode" turned on.

4. Click "Load Unpacked Extension"

5. Select the folder containing the contents of this repository. 

6. Enjoy your new tab page !


# Orignal README
-------------------------------------------

helvetictoc is my entry to the [10K apart contest](http://10k.aneventapart.com/).

It displays humanized time set in Helvetica.

Technical details:
-----------------

helvetictoc doesn't rely on any external scripts.

It's however using [CommonJS modules](http://wiki.commonjs.org/wiki/Modules/1.1) which are concatenated using [modulr](http://github.com/codespeaks/modulr).

The JS source files (the modules) are found in `src` and concatenated to `js/main.js`.

This hopefully proves proper code organisation doesn't trump file size: the included modulr JS script is just above 3kb _before minification_.

The [src code](http://github.com/tobie/helvetictoc) is available on github.