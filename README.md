If you are in PE node:

1. Clone this repo
2. cd myVimConfig
3. cp -r .vim ~
4. cp .vimrc ~

If you are not in PE node:

1. Download zip from github
2. Unzip
3. scp the folder to the remote server eg. scp -r <folder> remoteserver:~
4. Follow step 2 - 4 from the steps if you are in PE node

Note:

Linux commands:

1. cd is to change directory
2. cp is to copy file, the format is cp <file you want to copy> <destination directory>
3. cp -r means to copy recursively (for copying folders)
4. ls to list all files/folder in the folder you are currently in
5. ls -a to list all files/folder in the folder you are currently in + hidden files/folder
6. source ~/.bashrc if you made any changes to .bashrc and you want to reflect it by reloading the .bashrc file
7. mv to move file, the format is mv <file you want to move> <destination directory>
