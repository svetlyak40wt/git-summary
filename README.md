# git-summary
Checks what repos has been changed in your workspace.

# Install

## Linux

Use version from [master branch](https://github.com/svetlyak40wt/git-summary/tree/master)

* `sudo apt install gawk` (find the alternative command if you're not using ubuntu)
* `sudo cp git-summary /usr/local/bin`

## OSX

Use version from [osx branch](https://github.com/svetlyak40wt/git-summary/tree/osx)

* `brew install coreutils gawk`
* `sudo cp git-summary /usr/local/bin`

# Usage
* cd into a directory where you have multiple git repos you wanna check. For example: `cd Workspace`
* `git summary` (Checks the remotes to see if they have changes you do not or vica versa)
* `git summary -l` (Only checks for local changes and thus is much faster)

# Credits
Thanks for the amazing people who made the original git-summary bash script
* [mzabriskie](https://github.com/mzabriskie)
* [CycleMost](https://github.com/CycleMost)
* [lmj0011](https://github.com/lmj0011)
* [gimbo](https://github.com/gimbo)
* [zartc](https://github.com/zartc)

It all started [here](https://gist.github.com/mzabriskie/6631607) :heart:
