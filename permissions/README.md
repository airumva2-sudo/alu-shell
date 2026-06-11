# permissions

ALU "Shell, permissions" project. Each script is exactly two lines:
`#!/bin/bash` followed by a single command. No backticks, &&, ||, or ;.

## Files

| File | Description |
| ---- | ----------- |
| 0-iam_betty | Switch the current user to betty (su betty) |
| 1-who_am_i | Print effective username |
| 2-groups | Print groups the current user belongs to |
| 3-new_owner | Change owner of hello to betty |
| 4-empty | Create empty file hello |
| 5-execute | Add execute permission for the owner of hello |
| 6-multiple_permissions | Set u+x, g+x, o+r on hello |
| 7-everybody | Add execute permission for all on hello (no commas) |
| 8-James_Bond | Set hello mode to 007 |
| 9-John_Doe | Set hello mode to 753 (-rwxr-x-wx) |
| 10-mirror_permissions | Mirror olleh's mode onto hello |
| 11-directories_permissions | Add execute permission to all subdirectories |
| 12-directory_permissions | Create my_dir with mode 751 |
| 13-change_group | Change group owner of hello to school |
| 14-change_owner_and_group | Change owner/group of everything to vincent:staff |
| 15-symbolic_link_permissions | Change owner/group of symlink _hello |
| 16-if_only | Change hello owner to vincent only if owned by guillaume |
