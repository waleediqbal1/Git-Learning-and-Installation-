#  Git-Learning-and-Installation-

We will learn here the basics about git & github. After that we will learn how to install and use it.

## GitHUb & Git
- Github is basically a code sharing and collaboration platform.
- Git is basically a version control system and version control means keeping track of the versions of your files. For example (Keep in mind this example is to create and save a file in our system not on server for now.) we created the html file for the first time we created it means we have first version of it and when we save it after creation that’s means we have created and save the first version of our file. But Suppose we have changed something in our file now if we save it the system have just the latest file which is the updated version so means its second version of file but what about the previous version and where is it now ?. So here Git serve us in quite efficient way who actually controls and save all the versions of our all files.

## Why we use Git

We have some techniques or ways through which we can control versions but most of them have some draw backs and on the same time Git give us opportunity to control the version in quite efficient way that’s why we like to use that for example

## Drop box:

- Drop box periodically save the versions of the files and we can see the previous version by using history. But drop box save these versions for only 30 days. So it have some limitations. We can’t use it offline too. But yes drop box can do proper editor work.

##Google Docs:

- Google Docs is clearly not design to control versions of the code file. They are special purpose editors not design to highlight the editor work like (), syntax etc. Can’t use offline too.

In upper both the approaches to use as version control doesn’t helps us in quite efficient way .As a programmer we want a specific type of version control system where whenever we do some change in our code can do changes on control system too and when we need previous version it will allow us to get the previous version whether that previous version would be of last year. On the same time we need that control system who give us whole information regarding to changes and also give us feature through which we can compare the changes in versions. These all things which are the basic need of programming based version control system are not provided by the upper two examples somehow they lack in that. So here Git is been introduced who is such an efficient and well organized controlling system through which we as programmer can do any change whether we are online or offline is never been lost. 

## Git Installation's Commands and implementation

## Repository Creation

We have to create a repository for a new project on BitBucket .

- Go on  [Bitbucket](https://bitbucket.org).

- Create account on it first if you don't have already.

- Select Repositories from top nevigation bar and from drop down select Create Repository.

- Give Repository Name and check Access Level if you want to make your repository private (i select private because i want to make my repository private).

- Select Repository type as Git.

- Click Create repository.

This whole procedure creates a repository on bitbucket for us same like we created a folder on our operating systems .
But hold on see our repository is empty no data or file is in it because like creating a new folder it is empty. 
Now bitbucet give's us two options to use this repository .

## 1st Option: 

We clone(copy) this repository on our machine for that we have to select ( I'm starting from scratch ) from gitbucket.

## I'm starting from scratch

Use these commands in cmd or Terminal while first you have to go on the directory where you want to clone(copy) your repository in your operating syatem.


- First Go on the root directory of the folder where you want to clone(copy) your repository using cmd or Terminal on your operating system. Like i use cd on windows to my root directory. e.g  'cd C:\Users\usr_Name\Desktop\myfolder'

- First initialize the git use 'git init'.

- Now use command which you got on your gitbucket website now. It should be like 'https://xyz@bitbucket.org/xyz/repositoryName.git'( In this process you may asked to provide your credientials like your user name or password so provide those which you used on creation of the directory).


- use second command now from github website now.

- echo "# My project's README" >> README.md

- git add README.md

- git commit -m "Initial commit

- git push -u origin master

Through these commands we first cloning our repository on our desired folder then we are creating a a simple README.md file and then we are sending our file to server which is commmitting file to server.

## 2nd Option:

We first create a folder in our operating system and save some data in form of files in it then save it to server means our newly created repository and this we can do by 'pushing' called as 'commit'. So we can commit our data on our repository. For that we select (I have an existing project) . 

## I have an existing project

I personally use this approach because for me ts little easy approach.

- First created a folder and save a text file in it. 

- Open cmd or Terminal and move on the folder which we created. (on windows like cd C:\Users\Waleed\Desktop\GitFolder).GitFolder is mine newly created folder.

- Now use 'git init' command to initialize the git.  

- Now use command which is been displayed on second number by clicking "I have an existing project".

- It may open a window to give your username & password if it will open then provide your data which you use on account creation time.

- Now use command "git add --all".

- Now use command "git commit -m "Any comment (Like i use My first GIT)".

- Last command "git push origin master". 

Origin word we use because on creation we have not changesd the origin to any other name if you changed that before then you have to use the same name here too.
This whole process send our data or you can say copy and here we use appropiate word 'commit' our data on our created repository on the gitbucket. 
After that we can see the status of the git by using "git status" command. 
Now if you go on the repository and select your project you will see your commit with specififc id there and you can see what you commit and when too there.















