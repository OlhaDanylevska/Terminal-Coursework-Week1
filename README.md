# Terminal Coursework

In this coursework we want to test what you've learnt in the previous coursework.

## Tasks

### 1) Find my script

In this repository you'll find `MyDocuments` - this is all the documents that I use on my laptop.

I need to find the `script.js` file that is a part of MyFirstWebsite however you are **not** allowed to use a GUI, you must use Command Line and the Terminal.

What commands would I need to change directory to the directory containing `script.js`? In the section below, write all the commands you used.

Hint: You should use `cd` and `ls`.

#### 1) Answer

<!-- Write your answer here -->
`Mac@192 Terminal-Coursework-Week1 % pwd
/Users/Mac/Documents/CYF/Terminal-Coursework-Week1
Mac@192 Terminal-Coursework-Week1 % ls
GRADING.md              HOW-TO-SUBMIT.md        README.md
HOW-TO-GET-HELP.md      MyDocuments
Mac@192 Terminal-Coursework-Week1 % cd myDocuments
Mac@192 myDocuments % ls
Photos          Projects        Quiz            Scripts
Mac@192 myDocuments % cd projects
Mac@192 projects % ls
JavaScript-Core1        MyFirstWebsite          PortfolioWebsite
Mac@192 projects % cd JavaScript-Core1 
Mac@192 JavaScript-Core1 % ls
script.js
Mac@192 JavaScript-Core1 % `

### 2) Find my Hotel Photo

Great work!

Next, I want to try and find the photo of my hotel from my holiday in July that I want to send to a friend.

**Note**: You should do this by moving from where you are after completing the previous task.

#### 2) Answer

<!-- Write your answer here -->
Mac@192 Terminal-Coursework-Week1 % cd MyDocuments 
Mac@192 MyDocuments % cd photo
cd: no such file or directory: photo
Mac@192 MyDocuments % cd Photos
Mac@192 Photos % ls
HolidayJuly     HolidayJune

### 3) Counting Script

Next, I want you to run the script in this directory

```
/MyDocuments/Scripts/
```

You can run the script by typing

```
./count_to_100.sh
```

when you're in the correct directory.

For this task, I want you to **stop** the counter when I have counted to 10.

#### 3) Answer

Copy the output of the script here

<!-- Write your answer here -->
Mac@192 Scripts % ./count_to_100.sh
I have counted to 1
usage: sleep seconds
I have counted to 2
usage: sleep seconds
I have counted to 3
usage: sleep seconds
I have counted to 4
usage: sleep seconds
I have counted to 5
usage: sleep seconds
I have counted to 6
usage: sleep seconds
I have counted to 7
usage: sleep seconds
I have counted to 8
usage: sleep seconds
I have counted to 9
usage: sleep seconds
I have counted to 10
usage: sleep seconds
Mac@192 Scripts % 

### 4) Quiz

In this directory you'll find a quick quiz for you to complete

```
/MyDocuments/Quiz
```

You should open the quiz in Visual Studio Code and complete it. You can do this either by opening this project in VSCode or by running the command

```sh
code QUIZ.md
```

when you're in the correct directory.
