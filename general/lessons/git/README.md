###Introduction to Github

In Github we use git which is a control system that allows users to work on varieties of projects.

Github is an online website where programmers can share and store their code. Here, you can see previous revisions and variations of a project.

These three features - fork, pull request and merge - are what make Github so powerful. In this website we will explain how these features work as well as how to use them.

But first we will start with making an account.
To do this simply follow the instructions below:

  * Go to [github.com](github.com)
  * Hit Sign Up
  * Follow the instructions
  * Make the username with the same guidelines as Slack (first name, last name)

Lets start with creating a Repository, but what is a Github Repository? Well, repositories are a place in github where things are or may be stored.  

###Creating a Repository

  * Click the + button on the top left
  * Hit New Repository
  * Follow the instructions

Now, that you have your own repository, let's look at somebody else's repository. You can do this by simply searching a random persons github repository or you may look at this repository right [HERE](https://github.com/araiyan/Own-Website)

After you are inside a repository, look at the top right corner. You will see a box that says fork inside of it.
Click it.
After a few seconds you should see it lets you select an account that you want to fork it to.
Choose your account (that should be the only account that pops up)

Now, that your forked to a repository you can contribute your knoledge to that reposatory to make it better. To do this you need to clone the repository to your device. To do this click on the green botton that says, "Clone or download" and copy the URL. After you have done that open up your terminal and go to a file where you would like to store the repository. Then, inside your terminal, put in the code "git clone " and paste in the URL that you have previously copied. This will allow you to have a copy of the original repository in your harddrive.

You may edit the files in the cloned repository and if you want to commit the changes you have made to the files inside the original repository you first have to use the command "git add " and the name of the file that you want to add or use "git add ." this will allow you to add all the files you have just changed. Now if you want to commit these changes, use the command "git commit -m " and the message name that you want to commit the changes with. But wait, that's not all. To actually have all these changes to the original repository you have to push it to that repository first. But if you don't have write access to the original repository you may make a pull request and the owner of the repository (or anybody with the write access) may view your changes and merge the changes to the original repository if they think the changes are reasonable.

To do this, first you have to push all your changes to a different branch. Think of branches as branches in trees and your files are leafs of that tree you are simply making a new branch out of that tree with a slightly different kinds of leafs that you have created. So to do this do "git checkout -b ". Then the name of your branch (you can name it whatever you want). This will let you make a new branch and "checkout" to it. Basically, switching over to that branch after making it. Now that you have a branch do "git push origin " and the name of the branch you just created. This should allow you to push your changes to the fork you created from the repository. After you have done this, if you go back to the forked repository in the website you should see a new button named "Pull Request". Click it and follow the instructions, and now you have just created a pull request that other people can see and hopefully think about merging it to their original repository.
