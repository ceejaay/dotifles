Dot files.

In order use some of these dotfiles. They need a sym link in the home directory.


Example:
In order to get a sym link from .bash_profile to the home directory you have to type this:

`ln -sv ~/.dotfiles/runcom/.bash_profile`


`.dotfiles/runcom/.bash_profile` is where I have all my bash settings.


## Vim

Copy the .vim file into the home directory.
    This has all the plugins and stuff.
then create a sym link to the `.vimrc` file in the `.dotfiles/runcom/` directory.


## runcom.
    Create sym links with this code:

`ln -sv ~/.dotfiles/runcom/.bash_profile`
`ln -sv ~/.dotfiles/runcom/.inputrc`
`ln -sv ~/.dotfiles/runcom/.vimrc`



## How to run the bootstrap script.

Make sure the script has execute permissions:

`chmod +x /path/to/bootstrap.sh`


Run the script in the HOME DIRECTORY this way:

`./.dotfiles/bootstrap.sh`



What I need when setting up a new system. 
    `.bash_profile`
    `.vimrc`
    `.vim` file and all the plugins.
    `.inputrc`
    The correct python version.
    The current vim version.
    Pip.
    virtualenv
    virtualenv wrapper
    homebrew


