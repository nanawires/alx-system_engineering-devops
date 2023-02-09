#DESCRIPTION OF SCRIPTS IN THIS REPOSITORY

#!/bin/bash
pwd
Shows your current working directory

#!/bin/bash
ls
Lists contents of your current directory

#!/bin/bash
cd
Changes the working directory to the user's home directory

#!/bin/bash
ls -l
Displays current directory contents in a long format

#!/bin/bash
ls -la
Displays current directory contents, including hidden files and using long format

#!/bin/bash
ls -lan
Displays current directory contents, user and group IDs displaying numerically, hidden files all in long format

#!/bin/bash
mkdir /tmp/my_first_directory
Creates a directory my_first_directory in the /tmp/ directory

#!/bin/bash
mv /tmp/betty /tmp/my_first_directory
Moves the file betty form /tmp/ directory into /tmp/my_first_directory

#!/bin/bash
rm /tmp/my_first_directory/betty
Removes the file betty from /tmp/my_first_directory

#!/bin/bash
rmdir /tmp/my_first_directory
Deletes my_first_directory from the /tmp/ directory

#!/bin/bash
cd -
Changes the working directory to thr previous one

#!/bin/bash
ls -la . .. /boot
Lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.


