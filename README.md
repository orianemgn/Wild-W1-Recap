# WCS - Recap of the first week

## The terminal 

### What’s that for? 

- **Execute commands** by typing them on the keyboard
- **Manipulate** files and directories (copy, move, rename, delete)
- **Extract** specific **information** from large text
- Efficiently **search** for files in a file tree, according to different criteria (name, modification date, etc.) 
- **Install sofware** 
- Others…

## Commands

**Home directory on Windows** : <span style="color:yellow">/c/Users/MyName</span>

<https://www.youtube.com/watch?v=AO0jzD1hpXc&ab_channel=danscourses>



|**Some basic commands** |
| :-: |

|commands|name if name |description|
|--------|-------------|-----------|
|pwd|prompt - print working directory|display current directory |
|<span style="color:red ; background-color: lightgray">cd</span> or <span style="color:red ;background-color: lightgray">cd~</span>|change directorie command|retourn to the personal directory of the current user|
|<span style="color:red ; background-color: lightgray">cd~</span>||short cut to the user folder|
|<span style="color:red ; background-color: lightgray">cd ..</span>||go up one directory (parent directory)|
|<span style="color:red ; background-color: lightgray">cd ~/Music </span>||go under your Music folder (whatever folder you were in before) |
|<span style="color:red ; background-color: lightgray">cd a  + press tab twice </span> <br /> <span style="color:red ; background-color: lightgray">cd x + press tab twice </span> <br /> <span style="color:red ; background-color: lightgray">cd letter + press tab twice </span>||show all folders beginning with a // same with x or every letter|
|<span style="color:red ; background-color: lightgray">ls </span> |list command|tell you the files in the directory|
|<span style="color:red ; background-color: lightgray">ls -l </span>||tell you the files in the directory with more details|
|<span style="color:red ; background-color: lightgray">ls .</span> |list command “the current directory” = .|tell you the files in the directory|
|<span style="color:red ; background-color: lightgray">ls - a</span> ||displays the contents of the dictory but inclund hidden files (this are preceded by the characer .)|
|<span style="color:red ; background-color: lightgray">ls Pictures </span> and  <span style="color:red ; background-color: lightgray">ls./Pictures </span>||displays the contents of the Pictures folder |
|<span style="color:red ; background-color: lightgray">ls /Users </span>||allows you to display the list of directories associated with each user in the system |
|<span style="color:red ; background-color: lightgray">ls .. </span> ||will give you the same result! The .. means the *parents directory* The one just above it in the tree strucure. /Users is above /Users/mgnor|
|<span style="color:red ; background-color: lightgray">ls /bin </span> ||displays the contents of a directory containing the basic system commands (for exemple the command ls itselft!) |
|<span style="color:red ; background-color: lightgray">ls -l /bin| </span>|does the same thing, but gives more details, such as woh owns the files, when they were last modified, and so on. |

Notes : 

Notion of *parameters* or *arguments*: 

- <span style="color:red ; background-color: lightgray">-l</span> and <span style="color:red ; background-color: lightgray">/bin</span> are the arguments given to ls. 
- Arguments beginning with <span style="color:red ; background-color: lightgray">-</span> or <span style="color:red ; background-color: lightgray">- -</span> like <span style="color:red ; background-color: lightgray">-a</span>, <span style="color:red ; background-color: lightgray">-l</span> or <span style="color:red ; background-color: lightgray">- -help</span> are called *flags* they **modify the behavior of the command**. 

The slash character (<span style="color:red ; background-color: lightgray">/</span>) allows you to **chain the names of directories and their subdirectories**. This is the **directory separator.** 

**Meaning of ~**

The character ~ (called tide) represents the **personal directory of the current user.**   

It’s a quick way to acces <span style="color:yellow">/Users/MyName</span>. 

It’s very handy, especially if you’re in a completely different directory and you want to look at something in your personal file. For exemple, wherever we are, ls ~/Downloads allows you to list the contents of your folder Downloads 




|**Some basic Files and Directories commands** |
| :-: |

|commands |name if name |description|
|-------- |------------ |-----------|
|<span style="color:red ; background-color: lightgray">mkdir name</span>|makedirectory|make a new directory |
|<span style="color:red ; background-color: lightgray">rmdir name</span>|remove directory |remove directory|
|<span style="color:red ; background-color: lightgray">touch name</span>||create file|
|<span style="color:red ; background-color: lightgray">code name</span>||open the file |
|<span style="color:red ; background-color: lightgray">code .</span>||open the folder you are inside |
|<span style="color:red ; background-color: lightgray">cp</span>|copy|use|copy|use two parameters, namely source(s) and destination (or target) There may be several sources, but there is only one destination |
|<span style="color:red ; background-color: lightgray">cp ap\* banana /fruits</span> |copy all files beginning with ap + babana in the fruits folder|
|<p><span style="color:red ; background-color: lightgray">cp -R fruits copy-of-fruits</span> |</p><p></p><p></p><p><span style="color:red ; background-color: lightgray">cp -R</span>     <span style="color:red ; background-color: lightgray">-R</span> is mandadoty to copy a directory, even an emty one </p>|Recursive copy|copy of folder (because of the -R argument, if the source forled contains files, they are copied. If it contains directories, it copies them too, then “descends” into each of there directories, and so on. |
|<span style="color:red ; background-color: lightgray">cp -R fruits copy-of-fruits</span> /tmp/||This also works with multiple source directories, in this case you have too give an existing directory as destination argment|
|<span style="color:red ; background-color: lightgray">rm</span>|remove|<p>delete files and/or directories</p><p>immediate and definive not like “place in Recycle Bin”</p>|
|<span style="color:red ; background-color: lightgray">rm -r name-directory</span><>||The rmdir command being unable to delete a non-empty directory, one can use rm  with the <span style="color:red ; background-color: lightgray">-r</span> option (recursive) to accomplish this. |
|<span style="color:red ; background-color: lightgray">mv</span> |move and/or rename|rm  is used with two argument, the last one being the destination, and the previous one(s) the sources|
|<span style="color:red ; background-color: lightgray">mv ca\* parsnip courgette vegetable/</span>||move|
|<span style="color:red ; background-color: lightgray">mv fruits/orange fruits/grapefruit</span>||rename|
|<span style="color:red ; background-color: lightgray">mv vegetables/courgette fruits/kiwi</span>||Move and rename|




|**Temporary files** |
| :-: |

|commands |name if name |description|
|-------- |------------ |-----------|
|<span style="color:red ; background-color: lightgray">/tmp</span>|places for temporary files|this folder contains temporary files which are sometimes used when installinf or running programs on your computer|
|<p><span style="color:red ; background-color: lightgray">echo “Hello, world” > helloWorld.txt</span></p><p></p>|||
|echo||used to display text in the console|
|>||symbol used to store the result of a previous command in a file, specifying next (you can use it with anything you want, not only echo)|
|<span style="color:red ; background-color: lightgray">cat helloWord.text</span>||display the contents of the file|
|<span style="color:red ; background-color: lightgray">echo “Hello there”</span> > helloWorld.text||change content of the file|
|<span style="color:red ; background-color: lightgray">mv helloWorld.txt helloThere.txt</span>||<span style="color:red ; background-color: lightgray">mv</span> command is used to move a file from one location to another, but it can also be used to rename a file|



**Software skyscrapers** 

[**https://wildcodeschool.github.io/console-workshop/**](https://wildcodeschool.github.io/console-workshop/)


## Git and GitHub

**What is GitHub and what is GitHub for?**

GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

|**Git and GitHub**|
| :-: |

|commands |description|
|-------- |-----------|
|<p style="color:red ; background-color: lightgray">echo "# Wild-W1-Recap" >> README.md</p><p style="color:red ; background-color: lightgray">git init</p><p style="color:red ; background-color: lightgray">git add README.md</p><p style="color:red ; background-color: lightgray">git commit -m "first commit"</p><p style="color:red ; background-color: lightgray">git branch -M main</p><p style="color:red ; background-color: lightgray">git remote add origin https://github.com/orianemgn/Wild-W1-Recap.git</p><p style="color:red ; background-color: lightgray">git push -u origin main</p>|create a new repository on the command line with a https link|
|<p style="color:red ; background-color: lightgray">echo "# Wild-W1-Recap" >> README.md</p><p style="color:red ; background-color: lightgray">git init</p><p style="color:red ; background-color: lightgray">git add README.md</p><p style="color:red ; background-color: lightgray">git commit -m "first commit"</p><p style="color:red ; background-color: lightgray">git branch -M main</p><p style="color:red ; background-color: lightgray">git remote add origin git@github.com:orianemgn/Wild-W1-Recap.git</p><p style="color:red ; background-color: lightgray">git push -u origin main</p>|create a new repository on the command line with a SSH link|
|<p style="color:red ; background-color: lightgray">git remote add origin https://github.com/orianemgn/Wild-W1-Recap.git</p><p style="color:red ; background-color: lightgray">git branch -M main</p><p style="color:red ; background-color: lightgray">git push -u origin main</p>|push an existing repository from the command line https|
|<p style="color:red ; background-color: lightgray">git remote add origin git@github.com:orianemgn/Wild-W1-Recap.git</p><p style="color:red ; background-color: lightgray">git branch -M main</p><p style="color:red ; background-color: lightgray">git push -u origin main</p>|<p style="color:red ; background-color: lightgray">push an existing repository from the command line SSH</p>|
|<span style="color:red ; background-color: lightgray">git pull</span>| Uploading the change of your project on GitHup on your local machine|
|<span style="color:red ; background-color: lightgray">git add .</span>  or <span style="color:red ; background-color: lightgray">git add name-of-file</span>|to add all or one fill |
|<span style="color:red ; background-color: lightgray">git commit -m “message”</span>|to add your comment on the push request|
|<span style="color:red ; background-color: lightgray">git push</span> |to push from your on gitHub |
|<span style="color:red ; background-color: lightgray">git pull</span>|The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content|
|<span style="color:red ; background-color: lightgray">git branch branch-name</span>|Create a new branch|
|<span style="color:red ; background-color: lightgray">git checkout -b branch-name</span>|go to the branch|
|<span style="color:red ; background-color: lightgray">git push origin branch-name</span>|push on the branch|

