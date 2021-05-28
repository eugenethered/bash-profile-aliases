# bash-profile-aliases
Bash profile aliases

## Backup bash profile
Best to backup your bash profile file before making these changes ;)
* `cp ~/.bashrc ~/.bashrc.bak`

## Link aliases
Create `bash` dir in home dir and place these aliases in sub-dir `bash-profile-aliases`. Link these to the main bash profile.

1. `mkdir ~/bash`
2. `cd ~/bash; git clone git@github.com:eugene-the-red/bash-profile-aliases.git` (sub-dir `bash-profile-aliases` will be created due to project)
3. `echo -e "\n------------- BASH PROFILE ALIASES -------------\n. ~/bash/bash-profile-aliases/bash-all-aliases" >> ~/.bashrc` (links bash-all-aliases top level file to bash profile)

## Add contextual aliases
1. Create a 'contextual' alias file (e.g. bash-git for short git commands)
2. Place the above file in `aliases` dir
3. Link 'contextual' alias file in `bash-all-aliases`
