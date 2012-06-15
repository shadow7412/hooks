DR HOOK.

This is a git repo that is meant to reside inside in the .git folder.

The idea of this code is to test all files for syntax errors before allowing them into the repository.

It only tests new files - so runs quickly.

It uses a case statement to distinguish different languages - this means that many languages can be added in the future.

WARNING - this tests files in the working directory. That could cause problems if you are doing partial commits etc.

TO INSTALL:
Go to the git repostitory that you want to add this to.
Go into the folder called .git (it may be hidden)
Delete or rename the folder called 'hooks'.
Clone this repository into the folder you just deleted.

WINDOWS USERS:
You may need to change the wamp variable to your php version.
Find out where php.exe lives, and change the path to that.
You will not be able to commit until this change has been made!