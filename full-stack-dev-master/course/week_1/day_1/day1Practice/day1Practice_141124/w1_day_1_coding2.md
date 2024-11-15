# Week 1 - Day 1

#### Coding Session 2

**Introduction to git (Part 1)**

***NOTE**: Make sure that `git` is installed on your system!  
You can check with the command `git --version`, it should show the version of git that you currently have.  
If it is not installed you can do so using the command given below*  
Ubuntu
```


test@LAPTOP-LLCMMN9C:~/full-stack-dev/full-stack-dev-master/course/week_1/day_1/day1Practice/day1Practice_141124$ git --version
git version 2.43.0



sudo apt-get install git
```
Mac
```
brew install git
```

### FSD.W1.1.2_1

Setup your name and email using the `git config` command.


test@LAPTOP-LLCMMN9C:~/full-stack-dev/full-stack-dev-master/course/week_1/day_1/day1Practice/day1Practice_141124$ git config user.name
chetan
test@LAPTOP-LLCMMN9C:~/full-stack-dev/full-stack-dev-master/course/week_1/day_1/day1Practice/day1Practice_141124$ git config user.email
chetanchavan0300@gmail.com
test@LAPTOP-LLCMMN9C:~/full-stack-dev/full-stack-dev-master/course/week_1/day_1/day1Practice/day1Practice_141124$




### FSD.W1.1.2_2

Create a folder name `masai` in your home directory. Change directory to `masai` and initialise with an empty `git` repository.

test@LAPTOP-LLCMMN9C:~$ mkdir masai
test@LAPTOP-LLCMMN9C:~$ cd
.cache/         .landscape/     chetan/         course/         full-stack-dev/ masai/          practise/       rk/
test@LAPTOP-LLCMMN9C:~$ cd masai/
test@LAPTOP-LLCMMN9C:~/masai$ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint:   git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint:   git branch -m <name>
Initialized empty Git repository in /home/test/masai/.git/


### FSD.W1.1.2_3

Create a file called `profile.md` inside `masai` folder with the content using the below command.

echo "# VIKINGS - <FIRSTNAME LASTNAME>" > profile.md
```

test@LAPTOP-LLCMMN9C:~/masai$ echo "chetan chavan" >>profile.md
test@LAPTOP-LLCMMN9C:~/masai$ ls
profile.md
test@LAPTOP-LLCMMN9C:~/masai$


### FSD.W1.1.2_4

Create a repository on github with the name `masai-school` 


### FSD.W1.1.2_5

Add the created repository `masai-school` on github as the new remote to the previously initialised repository in `masai` folder

### FSD.W1.1.2_6

Make sure your file `profile.md` is synced and visible at the remote repo you created on github.

### FSD.W1.1.2_7

Clone your batch repo https://github.com/masai-school/cohort_1 on to your system using the `git clone` command. 

### FSD.W1.1.2_8

Copy the file `template.md` in the `profiles` folder with your name `firstname_lastname.md` in the `profiles` folder itself  
**Eg:** If you name is Nrupul Dev then the new file name will be `nrupul_dev.md` (no spaces, lower_case). 

### FSD.W1.1.2_9

Edit your profile file with your relevant info and make sure the attendance is marked for Week 1 Day 1.

### FSD.W1.1.2_10

Sync the repo back to github to reflect the changes you have made.