# MACSS2019

A repository for the contents of MACSS2019. To download the repository just click on the Download green button.

If you want to clone the repository to your computer using git follow the tutorial below.

GitHub Tutorial

Before you star using Github, you must be sure you have Git installed on your system. to check if you have Git, open the terminal en type

$ git --help

if and errors appears it means that you have to install git.

To install git follow the instructions in here: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

To have this repository locally on your computer first you have to make an account. After that, open your terminal and type:

$ more ~/.ssh/id_rsa.pub

and copy the output.

Go to your GitHub account setting and click the SSH and GPG Keys option. There add a new ssh key by pasting the contents of id_rsa.pub.

Click on the Clone and copy the url that appears in the little box (be sure is the ssh url).

In your terminal type

$ git clone git@github.com:cosmostatschool/MACSS2017.git

this will create a folder named MACSS2017 on your computer.

To have the latest version of the MACSS2017 repo, open the terminal and type

$ cd ~/MACSS2017 $ git pull origin master

We recommend that you make a pull of the repository every day to have all the necessary material.
