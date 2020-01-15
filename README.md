Dotfiles
=============

Customizations for your computer. 

Setup
-----

Follow these instructions to get dotfiles running on your system.

1. Read through the dotfiles and remove things you don't want or need. Use at your own risk.
1. Clone dotfiles folder into your home directory.
1. Create symlinks in the home folder to .gitconfig and .zshrc files
  1. In your home directory run `ln -s ~/dotfiles/.zshrc ~.zshrc` . This will create a symbolic link called .zshrc in your home directory. This will only work if you don't already have a .zshrc file in your home directory. If you already have one, make sure to save your configurations.
  1. In your home directory run `ln -s ~/dotfiles/.gitconfig ~.gitconfig` . This will create a symbolic link called .gitconfig in your home directory. Make sure to update the .gitconfig file in the dotfiles folder with your own username and email.
1. Restart your terminal to put the changes made in your dotfiles into effect.


Happy coding! :smile:
