# BME
The Quickest Fix: Force a Refresh
The absolute easiest way to force GitHub to rebuild the site and make that PDF link work is to give the repository a tiny nudge:

Click on the Code tab at the top-left of your screen (next to Issues and Pull requests).

Click on your README.md file (or any small text file you have in the main folder).

Click the pencil icon in the top-right corner of the file preview to edit it.

Add a single space or a period to the very bottom of the file.

Click the green Commit changes... button in the top right.

This small update forces GitHub's internal hosting system to wake up, re-scan the PROJECTS folder, and publish the new MAINLAB_poster.pdf. Give it about 60 seconds after committing, and your original link should load perfectly!
