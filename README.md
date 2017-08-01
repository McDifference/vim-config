# vim-config
ultimate vim + seoul256 + show line number + activate mouse

1. Install the ultimate vimrc from https://github.com/amix/vimrc. 

        git clone --depth=1 https://github.com/amix/vimrc.git ~/.vim_runtime
        sh ~/.vim_runtime/install_awesome_vimrc.sh

2. Put the seoul256 (https://github.com/junegunn/seoul256.vim) folder under ~/.vim_runtime/sources_forked

3. Modify  ~/.vim_runtime/vimrcs/extended.vim, in the "GUI related" section, change colorscheme to "colorscheme seoul256". You can download my modified extended.vim and replace the original one.

        colorscheme seoul256

4. Modify ~/.vimrc, add two lines at the end.

        set number
        set mouse=a
        
       
