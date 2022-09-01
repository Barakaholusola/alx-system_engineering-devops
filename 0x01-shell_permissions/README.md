# 0x01-shell_permissions
## 0-iam_betty
This script changes the current user to a user named betty
## 1-who_am_i
This scripts prints the effective username of the current user
## 2-groups
This script prints all the group the current user is part of
## 3-new_owner
This script changes the owner of the file hello to the user betty
## 4-empty
This script creates an empty file hello
## 5-execute
This script adds execute permission to the owner of the file hello
## 6-multiple_permissions
This script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
## 7-everybody
This script adds execute permission to the owner, the group owner and the other users, to the file hello
## 8-James_Bond
This script gives no permission at all to the owner and the group owner but gives the other users all the permissions
## 9-John_Doe
This script sets the mode of file hello to 756
## 10-mirror_permissions
This script sets the mode of the file hello to the same as olleh's
## 11-directories_permissions
This script adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users without changing the regular files
## 12-directory_permissions
This script cretes a directory called my_dir with permissions 751 in the working directory
## 13-change_group
This script changes the group owner to school for the file hello
## 101-symbolic_link_permissions
This script changes the owner and the group owner of _hello to vincent and staff respectively
## 102-if_only
This script changes the owner of the file hello to betty only if it is owned by the user guillaume
## 103-Star_Wars
This script will play the StarWars IV episode in the terminal

