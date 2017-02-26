# meteor-50-compile-error
Assignment: Meteor 50 minutes

Current state of Master branch:
Just prior to importing accounts-ui and accounts-password.

Current state Compiler Error branch:
Same as master with SKYBLUE background color.

Problem description:
If "meteor reset" is typed in to the command prompt, the compiler error in tasklist.js will surface after typing "meteor run".  You don't  need to import accounts-ui or accounts-password to reach the compiler error.

Some guesses:  In tasklist.html in the current state, intellij is highlighting "name" in line 8, < template name="tasks" > and states a warning message.  The warning message says "Attribute name is not allowed here".  The app runs fine when ignoring the warning message, but if this warning doesn't show up on other systems then maybe my Intellij setup is flawed.
