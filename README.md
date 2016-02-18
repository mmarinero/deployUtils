# deployUtils
Small bash tools to automate update and maintenance tasks with svn and ssh.

* pather: Generates absolute and relative paths to itself or another directory from pather location. Other scripts can then use paths relative to this location easily.
* sshrelpath: Logins into a server using ssh and a path from the login directory, just hides the ssh underlying command.
* svnreplacebranch: Takes to branches in a svn repository and replaces a subdirectory from one to the other, has an interactive mode.
* svnupdate: Logs into a server using ssh and updates a directory or file using svn, has an interactive mode.
* svnupdater: Uses svnupdate to update multiple servers.
