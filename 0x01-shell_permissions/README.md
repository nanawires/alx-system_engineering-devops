#DESCRIPTION OF SCRIPTS IN THIS REPOSITORY

0-iam_betty
#!/bin/bash
su betty
script switches the current user to the user betty

1-who_am_i
#!/bin/bash
whoami
script prints the effective username of the current user

2-groups
#!/bin/bash
groups
script prints all the groups the current user is part of

3-new_owner
#!/bin/bash
chown betty hello
script changes the owner of the file hello to the user betty

4-empty
#!/bin/bash
touch hello
script creates an empty file called hello

5-execute
#!/bin/bash
chmod u+x hello
script adds execute permission to the owner of the file hello

6-multiple_permissions
#!/bin/bash
chmod ug+x,o+r hello
script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello

7-everybody
#!/bin/bash
chmod ugo+x hello
script adds execution permission to the owner, the group owner and the other users, to the file hello

