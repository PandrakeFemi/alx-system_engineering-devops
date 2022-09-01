su-a command that swtches the current user
whoami- a command that prints the effective username of the current line
groups-A script that prints all the groups the current user is part of
chown betty hello- A script that changes the owner of the file to the user
touch hello - A script that creates an empty file hello
chmod u+x hello - A script that adds execute permission to the owner file
chmod ug+x,o+r- A script that adds execute permission,read permissions to other users.
chmod ugo+x - A Script that adds execution permission to everbody
chmod 007 - A script that gives only other users permission
chmod 753 - script that sets the mode to rwxr-x-wx
chmod --reference=(any mode given)> to set the mode of a file to be the same
chmod ugo+x */- A script that executes permission to all subdirectories of the current directory
mkdir -m 751 my_dir - A script that creates a directory with permission 751 in working directory
chgrp- To change group owner of a file
