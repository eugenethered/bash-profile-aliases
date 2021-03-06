# bash-profile-aliases
Bash profile aliases

## Note
This does not effect `.bashrc` profile, rather creates links in `~/.bash_aliases`.

## Link aliases
Create `bash` dir in home dir and place these aliases in sub-dir `bash-profile-aliases`. Link these to the main bash profile.

1. `mkdir ~/bash`
2. `cd ~/bash; git clone git@github.com:eugene-the-red/bash-profile-aliases.git` (sub-dir `bash-profile-aliases` will be created due to project)
3. `echo -e "\n# --- CUSTOM BASH ALIASES ---\n. ~/bash/bash-profile-aliases/bash-all-aliases\n" >> ~/.bash_aliases` (links bash-all-aliases top level file to bash profile)
4. `source ~/.bashrc`

## Add contextual aliases
1. Create a 'contextual' alias file (e.g. bash-git for short git commands)
2. Place the above file in `aliases` dir
3. Link 'contextual' alias file in `bash-all-aliases`

## Prerequisits
* `~/.bash_aliases` should already be present in `.bashrc` (check this on your end)
