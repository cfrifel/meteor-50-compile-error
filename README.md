# meteor-50-compile-error
Assignment: Meteor 50 minutes

Current state of Master branch:
Just prior to importing accounts-ui and accounts-password.

Current state Compiler Error branch:
Same as master with SKYBLUE background color.

Problem description:
If "meteor reset" is typed in to the command prompt, the compiler error in tasklist.js will surface after typing "meteor run".  You don't  need to import accounts-ui or accounts-password to reach the compiler error.

Some guesses:  On Meteor's <a href="https://docs.meteor.com/commandline.html#meteorreset">command line documenation</a> page, meteor reset is said to put meteor in a fresh state.  Maybe it deletes some cached information about tasklist.js and causes the compiler error.  Currently testing if the error does not occur if Meteor is never resetted in another repo.
