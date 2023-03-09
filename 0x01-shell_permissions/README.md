
0. My name is Betty
#!/bin/bash 
su betty 

 
#!/bin/bash
id -un

2-groups
#!/bin/bash
groups

3-new_owner
#!/bin/bash
chown betty hello

4-empty
#!/bin/bash
touch hello



5-execute
#!/bin/bash 
chmod u+x

6-multiple_permissions
#!/bin/bash
chmod u+x,g+x,O+r hello

7-everybody
#!/bin/bash
chmod ugo+x hello

8-James_Bond
#!/bin/bash
chmod 007 hello



9-John_Doe
#!/bin/bash
chmod 753 hello

10-mirror_permissions
#!/bin/bash 
chmod --reference=olleh hello 

11-directories_permissions
#!/bin/bash
chmod -R ugo+X 

12-directory_permissions
#!/bin/bash
mkdir -m 751 my_dir

13-change_group
#!/bin/bash
chgrp school hello
