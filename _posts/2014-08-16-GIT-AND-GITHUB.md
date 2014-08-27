---
layout: post
title: Git and Github!
quote: Git is a revision control system, a tool to manage your source code history. GitHub is a hosting service for Git repositories.
image: /media/2014-08-16-GIT-AND-GITHUB/cover1.jpeg
video: false
---

#INTRODUCTION

##WHY GIT?

I was at gym when this thought struck my mind - "What if our whole life was version controlled!!"

If so I will have to gym only once in my whole lifetime to get the desired shapes and brilliant physique.So when I want to look build up, I can switch to my "WWE champion" look and when I feel too heavy I can get back to my "lean MJ" look.This would have been so easier.

Even for girls,They dont have to waste their time doing the same makeup everytime they wanna go outing,they can just switch between their versions whenever required.Just imagine how much time and energy would have been saved.
But unfortunately,we cannot do so!!

Nevertheless,we still have the power to version control our documents and source codes in the tech world.

Now,the question is how?

>hmmmm..hmmmmm....thinking ...... :P

Simple answer:

> GIT-version controller

##WHAT IS GIT AND GITHUB?

###Git

It is a distributed version controller which maintains,stores and tracks all the different versions of the documents and codes that are created by a user in the given course of time.It is with the help of git that the user can easily switch between the different versions.

###Github

It is a web based hosting service which provides us a web based graphical user interface to store and share documents and source codes between one another, irrespective of our location around the world.

##HOW TO USE IT?
 In order to use git,we need to first install it.
This can be done in a single step,just open the terminal and type the following command:
{% highlight javascript %}
sudo apt-get install git
{% endhighlight %}


#GETTING STARTED!!

so now that you have git installed, let us see some of the basic commands used in git. It goes as follows:

###git init

Imagine you are going to write a novel. So you will have to buy a new book - "X" and maintain it as your novel wherein you pen down all your thoughts.So whenever you wanna write something in your novel you will write in this book - "X" and not in any other book because you are maintaining this book - "X" as your novel.
Using the same logic,when you working on a computer system you need to tell the system which is your git directory so that the system can differentiate it from other directories.This is done using the "git init" command.
So "git init" basically tells your computer that your present working directory is now initialized as a git repository or a git directory.Hence the word "init" - initialized.

{% include image.html url="/media/2014-08-16-GIT-AND-GITHUB/image1.png" width="100%" description="The git init command illustrated" %}

###git status

I am sure everyone in today's world has a presence on one of the social networking website.So taking the example of facebook, we often update our status or in other words, "What's on your mind ?"
Similarly,we have a command "git status" to check the current status of your git repository,ie, how many files have been modified,how many files are tracked or untracked,how many files commited etc etc.
One beautiful advantage of "git status" is that it suggests you the next step which is to be performed and also gives out its syntax.

{% include image.html url="/media/2014-08-16-GIT-AND-GITHUB/image2.png" width="100%" description="The git status command illustrated" %}

###git config

Git is beautifully structured. Its smart. 
So when you working with it, it wants to know your identity,ie, your name and email address. So whenever you make a change to a git repository(local/global), it will first ask for your identity and then make the changes. This way you can keep a track of who is changing your documents or codes, who is contributing etc etc. 
One good advantage is that no one can mess around with your files cause the changes are not accepted without their identity.So git is smart.

> Now how do you set your identiy??

Its simple, the syntax goes as follows:

> git config --global user.name <name>

and

> git config --global user.email <email>

(Here we have used global declaration,we can also use local declaration)

###git add filename

So taking the same example we took earlier,ie,example of a novel, assume that you have written down a novel which has three chapters namely chap1,chap2 and chap3. After few days you change the chap1 to chap1.1(say). Again after few days, you change chap1.1 to chap1.2(say).
 Again after few months you realise your first version of the chapter,ie, chap1 was better than chap1.1 and chap1.2 ,so you replace it back into your novel.

> Now the question is how does this process work in git.

Simple answer again,

> using the "git add" and "git commit" commands

So what the "git add" command does is that it adds your mentioned filenames to staging area. In other words, it begins to keep track of those mentioned filenames. So any changes made to those files will be tracked,stored,maintained and even reported by git.

SYNTAX:

> git add filename

{% include image.html url="/media/2014-08-16-GIT-AND-GITHUB/image3.png" width="100%" description="The git add command illustrated" %}

###git commit -m "message"

We know that the "git add" command stages your files. So taking the same example as above,when you "git add chap1", it will start tracking and controlling different versions of chap1, but you havent replaced chap1.2 with chap1. This is done using the "git commit" command.
One more simpler example of git commit could be your shopping kart, when you add and remove different items to and from your kart,its basically like using the "git add" command and when you finalised your decision, you make a bill of the items in your kart which is like using the "git commit" command.

SYNTAX:

> git commit -m "message"

Usually the commits made in git is accompanied by a message.This is done so that the other user, who is reading your document or code or in some cases sharing and contributing to your code, finds it easy to acknowledge what are the changes done by you.

{% include image.html url="/media/2014-08-16-GIT-AND-GITHUB/image4.png" width="100%" description="The git add command illustrated" %}

###git push

Now that you have committed the required changes and all things are set. You might want to publish your files for different people to view it, contribute to it etc. So you can publish them on your github account. You will have to create a github account by going to the official website of "[github](http://www.github.com)" and then create a repository in your account.
After that all you have to do is push your files from your system to your github account for other people to access and use it.
In order to push the files, we use the "git push" command.

SYNTAX:

> git push origin master 

OR simply,

> git push

origin is the link to the global repository where you will be pushing your files.
master is the default branch in github.You can have your own branches, if required.

###git pull

Just like "git push" command pushes your files to global repository hosted on github. Similarly "git pull" command will pull down the required files from the required link or repository. 

SYNTAX:

> git pull origin master

OR simply,

> git pull

###MORE OF GIT

There are lot more commands and functionality avaliable to git.Few other commands are :

> git clone

> git help

> git diff

> git checkout

and a lot more!!!

