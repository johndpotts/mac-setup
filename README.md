# mac-setup
collection of stuff to do to set up a mac


## Installing Git
Git is actually installed on MacOS, but we'll be reinstalling it so that we'll have the newest version:

go to https://git-scm.com/downloads
download the software for Mac
install Git choosing all of the default options
Once everything is installed, you should be able to run git on the command line. If it displays the usage information, then you're good to go!

Configuration Steps
To configure the terminal, we'll perform the following steps:

1. download the zipped file
2. move the directory udacity-terminal-config to your home directory and name it .udacity-terminal-config (there's a dot at the front, now!)
3. move the bash_profile file to your home directory and name it .bash_profile (there's a dot at the front, now!)
4. if you already have a .bash_profile file in your home directory, transfer the content from the downloaded bash_profile to your existing .bash_profile


First Time Git Configuration
Before you can start using Git, you need to configure it. Run each of the following lines on the command line to make sure everything is set up.

#### sets up Git with your name
git config --global user.name "<Your-Full-Name>"

#### sets up Git with your email
git config --global user.email "<your-email-address>"

#### makes sure that Git output is colored
git config --global color.ui auto

#### displays the original state in a conflict
git config --global merge.conflictstyle diff3
git config --list

Git & Code Editor
The last step of configuration is to get Git working with your code editor. Below are three of the most popular code editors. If you use a different editor, then do a quick search on Google for "associate X text editor with Git" (replace the X with the name of your code editor).

Atom Editor Setup
git config --global core.editor "atom --wait"
Sublime Text Setup
git config --global core.editor "'/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl' -n -w"
VSCode Setup
git config --global core.editor "code --wait"