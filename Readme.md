# Cloud Project

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSETUE46G7gv41P7dFD5i4VQ_TAgV_FIcS4Kg&usqp=CAU" width="400" height="400">



## Members:

* Silvia
* Ricardo
* Alberto
* Tony
* Nacho


### Important git concetps

Each team member will initially clone develop branch and work on features. The first exercise will walk you through in how to initially set up your environment.

### First Exercise:

1. Create a folder in your computer : Cloud_Project
2. Open terminal and go inside folder Cloud_Project

~~~
git clone -b develop https://github.com/IgnacioGB1990/Cloud_Members.git
~~~

3. Create your own branch and move to it:
~~~
git checkout -b "members_name"
~~~


4. Create folder with your name **inside folder members** and add readme.md with your github url (see my example)
~~~
git add .
~~~

~~~
git commit -m "my_name added github url"
~~~

~~~
git push --set-upstream origin "members_name"
~~~

Important we will work on develop



### Basic Git Commands

Check status of files:
~~~
git status
~~~

Add all files to staging area prior to commit:
~~~
git add .
~~~

Add commit :
~~~
git commit -m "First Commit"
~~~

Push changes to Github
~~~
git push
~~~

Pull any changes done remotely and update them into your local directory:

~~~
git pull
~~~

#### Branches

Creates and moves to branch:

~~~
git checkout -b "Name_of_new_branch"
~~~

Move to existing branch:

~~~
git checkout "name_of_existing_branch"
~~~



