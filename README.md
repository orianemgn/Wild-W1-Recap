The terminal 

# What’s that for? 

- **Execute commands** by typing them on the keyboard
- **Manipulate** files and directories (copy, move, rename, delete)
- **Extract** specific **information** from large text
- Efficiently **search** for files in a file tree, according to different criteria (name, modification date, etc.) 
- **Install sofware** 
- Others…

# Commands

**Home directory on Windows** : /c/Users/MyName 

<https://www.youtube.com/watch?v=AO0jzD1hpXc&ab_channel=danscourses>



|**Some basic commands** |
| :-: |

|commands|name if name |description|   |   |
|--------|-------------|-----------|---|---|
|pwd|prompt - print working directory|display current directory |
|cd or cd~|change directorie command|retourn to the personal directory of the current user|
|cd~||short cut to the user folder|
|cd ..||go up one directory (parent directory)|
|cd ~/Music||go under your Music folder (whatever folder you were in before) |
|cd a  + press tab twice <br />cd x + press tab twice <br />cd letter + press tab twice||show all folders beginning with a // same with x or every letter|
|ls |list command|tell you the files in the directory|
|ls -l||tell you the files in the directory with more details|
|ls . |list command “the current directory” = .|tell you the files in the directory|
|ls - a ||displays the contents of the dictory but inclund hidden files (this are preceded by the characer .)|
|ls Pictures and ls./Pictures||displays the contents of the Pictures folder |
|ls /Users||allows you to display the list of directories associated with each user in the system |
|ls .. ||will give you the same result! The .. means the *parents directory* The one just above it in the tree strucure. /Users is above /Users/mgnor|
|ls /bin ||displays the contents of a directory containing the basic system commands (for exemple the command ls itselft!) |
|ls -l /bin||does the same thing, but gives more details, such as woh owns the files, when they were last modified, and so on. |

Notes : 

Notion of *parameters* or *arguments*: 

- -l and /bin are the arguments given to ls. 
- Arguments beginning with - or  - -  like -a, -l or - -help are called *flags* they **modify the behavior of the command**. 

The slash character (/) allows you to **chain the names of directories and their subdirectories**. This is the **directory separator.** 

**Meaning of ~**

The character ~ (called tide) represents the **personal directory of the current user.**   

It’s a quick way to acces /Users/MyName. 

It’s very handy, especially if you’re in a completely different directory and you want to look at something in your personal file. For exemple, wherever we are, ls ~/Downloads allows you to list the contents of your folder Downloads 




|**Some basic Files and Directories commands** |
| :-: |

|commands |name if name |description|
|-------- |------------ |-----------|
|mkdir name|makedirectory|make a new directory |
|rmdir name|remove directory |remove directory|
|touch name||create file|
|code name||open the file |
|code .||open the folder you are inside |
|cp|copy|use|copy|use two parameters, namely source(s) and destination (or target) There may be several sources, but there is only one destination |
|cp ap\* banana /fruits||copy all files beginning with ap + babana in the fruits folder|
|<p>cp -R fruits copy-of-fruits</p><p></p><p></p><p>cp -R     -R is mandadoty to copy a directory, even an emty one </p>|Recursive copy|copy of folder (because of the -R argument, if the source forled contains files, they are copied. If it contains directories, it copies them too, then “descends” into each of there directories, and so on. |
|cp -R fruits copy-of-fruits /tmp/||This also works with multiple source directories, in this case you have too give an existing directory as destination argment|
|rm|remove|<p>delete files and/or directories</p><p>immediate and definive not like “place in Recycle Bin”</p>|
|rm -r name-directory||The rmdir command being unable to delete a non-empty directory, one can use rm  with the -r option (recursive) to accomplish this. |
|mv |move and/or rename|rm  is used with two argument, the last one being the destination, and the previous one(s) the sources|
|mv ca\* parsnip courgette vegetable/||move|
|mv fruits/orange fruits/grapefruit||rename|
|mv vegetables/courgette fruits/kiwi||Move and rename|




|**Temporary files** |
| :-: |

|commands |name if name |description|
|-------- |------------ |-----------|
|/tmp|places for temporary files|this folder contains temporary files which are sometimes used when installinf or running programs on your computer|
|<p>echo “Hello, world” > helloWorld.txt</p><p></p>|||
|echo||used to display text in the console|
|>||symbol used to store the result of a previous command in a file, specifying next (you can use it with anything you want, not only echo)|
|cat helloWord.text||display the contents of the file|
|echo “Hello there” > helloWorld.text||change content of the file|
|mv helloWorld.txt helloThere.txt||mv command is used to move a file from one location to another, but it can also be used to rename a file|



**Software skyscrapers** 

[**https://wildcodeschool.github.io/console-workshop/**](https://wildcodeschool.github.io/console-workshop/)


# Git and GitHub 



|**Git and GitHub**|
| :-: |

|commands |name if name |description|
|-------- |------------ |-----------|
|/tmp|places for temporary files|this folder contains temporary files which are sometimes used when installinf or running programs on your computer|
|<p>echo “Hello, world” > helloWorld.txt</p><p></p>|||
|echo||used to display text in the console|

