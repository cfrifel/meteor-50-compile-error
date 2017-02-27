# meteor-50-compile-error
Assignment: Meteor 50 minutes

Current state of Master branch:
Just prior to importing accounts-ui and accounts-password.

Current state Compiler Error branch:
At the addition of {{> loginButtons}} stage in the video.  Changed let to var in line 12 of tasklist.js to make the error go away.

Problem Description:

A compiler error shows up in line 12 when trying to run meteor.  The error states that in tasklist.js, there is a missing semicolon in the line 12: "let name = event.target.name.value;"

Problem Solution:

Go to Control Panel > Default Programs, and click on "Associate a file type or protocol with a program".
Then find .js, and change it to IntelliJ.
