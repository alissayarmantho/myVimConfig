If you are in PE node:

On the remote server:
1. git clone --recursive https://github.com/alissayarmantho/myVimConfig
2. cd myVimConfig
3. cp -r .vim ~
4. cp .vimrc ~
5. cp .bashrc ~
6. source ~/.bashrc

If you are not in PE node:

In your computer (not remote server):
1. Clone the repo: git clone --recursive https://github.com/alissayarmantho/myVimConfig
2. scp the .vim folder to the remote server eg. scp -r [folder] remoteserver:~
3. scp the .vimrc to the remote server eg. scp .vimrc remoteserver:~
4. scp the .bashrc to the remote server eg. scp .bashrc remoteserver:~

On the remote server:
1. On the remote server, run: source ~/.bashrc

Note:

Linux commands:

1. cd is to change directory
2. cp is to copy file, the format is cp [file you want to copy] [destination directory]
3. cp -r means to copy recursively (for copying folders)
4. ls to list all files/folder in the folder you are currently in
5. ls -a to list all files/folder in the folder you are currently in + hidden files/folder
6. source ~/.bashrc if you made any changes to .bashrc and you want to reflect it by reloading the .bashrc file
7. mv to move file, the format is mv [file you want to move] [destination directory]

What you will get from this:
1. Colorscheme
2. Mouse support for vim
3. Auto-closing brackets + different color brackets 
4. Folder navigator
