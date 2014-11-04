mac_setup
=========

This is to setup work environment in Mac

1. install xcode if you haven't.
after the xcode is installed, agreeing the agreement by the following command:
$ sudo xcodebuild -license


2. Before everything, install homebrew by the following command:
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
or the latest command from http://brew.sh/

$ brew doctor
$ brew update

3. install git by homebrew

$ brew install git


4. run setup.sh 





$ vim .bash_profile 
 
export JAVA_HOME=$(/usr/libexec/java_home)
 
$ source .bash_profile
