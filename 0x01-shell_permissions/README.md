# 0x01-shell_permissions
0-iam_betty: It switches the current user to the user betty.  
1-who_am_i: It prints the effective username of the current user.  
2-groups: It prints all the groups the current user is part of.  
3-new_owner: It changes the owner of the file hello to user betty.  
4-empty: It creates an empty file called hello.  
5-execute: It adds execute permission to the owner of hello.  
6-multiple_permissions: It adds execute permissions to the owner and group owner and read permissions to all others.  
7-everybody: It adds execute permissions for everybody.  
8-James_Bond: It adds all permissions for other users while setting owner and group to no permissions.  
9-John_Doe: It sets the mode of hello to a specified set of permissions.  
10-mirror_permissions:  It mirrors the mode of olleh to hello.  
11-directories_permissions: It sets the permissions of all subdirectories as executable for all users.  
13-channge_group: It changes the group for a specified file.  
100-change_owner_and_group: It changes the owner to vincent and the group owner to staff for all files and directories in the workinng directory.  
101-symbolic_link_permissions: It changes the owner and the group owner of a symbolic link _hello.  
102-if_only: It changes the owner of file hello only if its current owner is guillame.  
