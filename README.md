# meteor-50-compile-error
Assignment: Meteor 50 minutes

Current state of Master branch:
Just prior to importing accounts-ui and accounts-password.

Current state Compiler Error branch:
At the addition of {{> loginButtons}} stage in the video.  Changed let to var in line 12 of tasklist.js to make the error go away.

Problem Description:

A compiler error shows up after doing either "meteor reset" or "meteor add accounts-ui accounts-password".  The error states that in tasklist.js, there is a missing semicolon in the line "let name = event.target.name.value;"

Problem Solution:
After adding accounts-ui accounts-password to the app directory, type in "meteor npm install" to recalibrate the directory.  Also, change let to var in the problem line in tasklist.js (after getting it to run successfully, you can change it back to "let" and it will still run)
