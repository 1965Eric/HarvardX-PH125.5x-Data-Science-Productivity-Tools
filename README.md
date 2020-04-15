# Data_Science_Productivity_Tools
# HarvardX: PH125.5x | Data Science: Productivity Tools

## Abstract
This is the 5th course in the HarvardX Professional Certificate in Data Science, a series of courses that prepare you to do data analysis in R, from simple computations to machine learning.

The textbook for the Data Science course series is [freely available online](https://rafalab.github.io/dsbook/).

## Learning Objectives
- How to leverage the many useful features provided by RStudio
- How to use Unix/Linux to manage your file system
- How to start a repository on GitHub
- How to perform version control with git

## Course Overview

### Section 1: Installing Software
You will learn how to install R, RStudio, git (and git bash for Windows users), create a GitHub account, create a GitHub repository, and connect RStudio to your GitHub account.

### Section 2: Unix
You will learn the basics of managing your filesystem from the terminal with Unix commands such as mv and rm.

### Section 3: Reproducible Reports
You will learn to create data science reports using R Markdown and the knitr package.

### Section 4: Git and GitHub
You will learn to use git and GitHub from the command line to clone and create repositories.

### Section 5: Advanced Unix
You will learn other Unix commands, including arguments, getting help, pipes, and wildcards that are helpful in data science.

The textbook for this course is available [here](https://rafalab.github.io/dsbook/introduction-to-productivity-tools.html)

## Comprehension Check

## Introduction to Rstudio, Git and Github

1. Installing R and RStudio Which of the following statements about R and RStudio is true?
- [X] A. R is a programming language, whereas RStudio is a desktop environment.
- [ ] B. You can use RStudio without using R, but we recommend using R in this course.
- [ ] C. When you download RStudio, it automatically downloads and installs R too.
- [ ] D. You can only use R on Mac OS X and Linux. Windows users must use RStudio.

2. Introduction to RStudio

Select the code that will NOT install the popular graphing and data manipulation packages ggplot2 and dplyr in R.
- [ ] A. install.packages(c(“ggplot2”,“dplyr”))
- [ ] B. install.packages(“tidyverse”)
- [X] C. install.packages(c("dplyr","ggplot2”)
- [ ] D. install.packages(“ggplot2”) install.packages(“dplyr”)

3. Which of the following is not true about installing packages? Select ALL that apply.

- [ ] A. To install a new package, the install.packages() function can be used
- [ ] B. To install a new package, the drop-down menu Tools > Install packages can be used
- [X] C. Installed packages will remain installed even if you upgrade R
- [X] D. Installing a package by building from GitHub will give you the exact same version as on CRAN

4. Which of the following commands for editing scripts is not correct?

- [ ] A. To save a script: Ctrl+S on Windows/Linux / Command+S on Mac
- [ ] B. To run an entire script: Ctrl+Shift+Enter on Windows/Linux / Command+Shift+Return on Mac, or click “Source” on the editor pane.
- [ ] C. To open a new script: Ctrl+Shift+N on Windows/Linux / Command+Shift+N on Mac
- [X] D. To run a single line of script: Ctrl+Shift / Command+Shift while cursor pointing to that line, or select the chunk and click "run"
- [ ] E. To comment selected text: Ctrl+Shift+C or Command+Shift+C for Mac.

5. Which of the following statements about keeping organized with RStudio projects is not correct?

- [ ] A. To start a new project, click on File > New Project > New directory > New project > {choose a file directory and project name}
- [X] B. You must always start a project in a new directory.
- [ ] C. RStudio provides a way to keep all components of a data analysis project organized into one folder and to keep track of information about this project.
- [ ] D. Creating a new R project will produce an .Rproj file associated with the project.

6. What can you change in the global options? Select ALL that apply.

- [ ] A. Set Git / GitHub configuration for each R project
- [X] B. Move the editor pane to the upper right correct
- [X] C. Change the editor theme to a dark background correct
- [X] D. Customize key binding correct

7. Introduction to Git and GitHub - Pull

What does the term “pull” mean in the context of using Git in RStudio?
- [ ] A. Add local files to a remote GitHub repo.
- [X] B. Download changes from the remote repo to your local repository.
- [ ] C. Configure the RStudio environment to automatically connect to GitHub.
- [ ] D. Save changes made in RStudio to the local repository on your computer.

Note: We “pull” changes from the remote repo on GitHub to directories on our computers.

8. Push

What does the term “push” mean in the context of using Git in RStudio?
- [X] A. Upload changes made in your local repository to a remote repository.
- [ ] B. Download changes from the remote repo to the RStudio environment.
- [ ] C. Configure the RStudio environment to automatically connect to GitHub.
- [ ] D. Save changes made in RStudio to the local repository on your computer.

Note: We “push” files to add them to a remote GitHub repository from our local computers.

9. Commit

What does the term “commit” mean in the context of using Git in RStudio?
- [ ] A. Add local files to a remote GitHub repo.
- [ ] B. Download changes from the remote repo to the RStudio environment.
- [ ] C. Configure the RStudio environment to automatically connect to GitHub.
- [X] D. Save changes made in RStudio to the local repository on your computer.

Note: A “commit” is like saving a file that you’re working on. Be sure to write a brief description about what you changed in that file.

10. Did you create a GitHub account? Enter your GitHub username below.


## Unix

![asset-v1-HarvardX+PH125 5x+1T2018+type@asset+block@data_science_1_rev](https://user-images.githubusercontent.com/17474099/79341673-749dab00-7f2c-11ea-82a2-a1695085ef26.png)

<img width="608" alt="Schermafbeelding 2020-04-15 om 16 00 56" src="https://user-images.githubusercontent.com/17474099/79346290-78343080-7f32-11ea-9dd2-1911f313d595.png">

<img width="604" alt="Schermafbeelding 2020-04-15 om 16 01 32" src="https://user-images.githubusercontent.com/17474099/79346399-9ac64980-7f32-11ea-87f5-de12c321cc8d.png">



1. Working Directory

It is important to know which directory, or folder, you’re in when you are working from the command line in Unix. Which line of code will tell you the current working directory?
- [ ] A. cd
- [X] B. pwd
- [ ] C. rm
- [ ] D. echo

2. Previously Executed Code

You can’t use your computer’s mouse in a terminal. How can you see a line of code that you executed previously?
- [ ] A. Type pwd
- [ ] B. Type echo
- [X] C. Use the up arrow
- [ ] D. Press the enter key

3. pwd Output

Assume a student types pwd and gets the following output printed to the screen: /Users/student/Documents.

Then, the student enters the following commands in sequence:
```
mkdir projects

cd projects
```
What will be printed to the screen if the student types pwd after executing the two lines of code shown above?
- [ ] A. /Users/student/Documents
- [X] B. /Users/student/Documents/projects
- [ ] C. /Users/student
- [ ] D. cd: projects: No such file or directory

4. Moving Files 1

The following is the full path to a your homework assignment file called “assignment.txt”: 
```
/Users/student/Documents/projects/homeworks/assignment.txt
```
Which line of code will allow you to move the assignment.txt file from the “homeworks” directory into the parent directory “projects”?
- [ ] A. mv assignment.txt
- [ ] B. mv assignment.txt .
- [X] C. mv assignment.txt ..
- [ ] D. mv assignment.txt /projects

Note: Double dots .. mean “up a directory”, so mv assignment.txt .. moves the assignment text file into the NEXT highest directory, projects.

5. Moving Files 2

You want to move a file called assignment.txt file into your projects directory. However, there is already a file called “assignment.txt” in the projects directory.

What happens when you execute the “move” (mv) command to move the file into the new directory?
- [X] A. The moved "assignment.txt" file replaces the old "assignment.txt" file that was in the "projects" directory with no warning.
- [ ] B. An error message warns you that you are about to overwrite an existing file and asks if you want to proceed.
- [ ] C. An error message tells you that a file already exists with that name and asks you to rename the new file.
- [ ] D. The moved “assignment.txt” file is automatically renamed “assignment.txt (copy)” after it is moved into the “projects” directory.

Note: Be careful when moving files around using the command line. Unix does not warn you before you overwrite a file

### Working with Unix

6. Unix Commands

Which of the following statements does NOT correctly describe the utility of a command in Unix?
- [ ] A. The q key exits the viewer when you use less to view a file.
- [ ] B. The command ls lists files in the current directory.
- [X] C. The command ```mkdir``` makes a new directory and moves into it.
- [ ] D. The mv command can move a file and change the name of a file.

## Reproducible Reports

1. Why R Markdown?

Why might you want to create a report using R Markdown?
- [ ] A. R Markdown has better spell-checking tools than other word processors.
- [X] B. R Markdown allows you to automatically add figures to the final document.
- [ ] C. R Markdown final reports have smaller file sizes than Word documents.
- [ ] D. R Markdown documents look identical to the final report.

2. Naming an R Chunk

You have a vector of student heights called heights. You want to generate a histogram of these heights in a final report, but you don’t want the code to show up in the final report. You want to name the R chunk “histogram” so that you can easily find the chunk later.

Which of the following R chunks does everything you want it to do?
- [ ] A. /{r, histogram, echo=FALSE} hist(heights)
- [ ] B. {r histogram} hist(heights)
- [ ] C. {r, echo=FALSE} hist(heights)
- [X] D. {r histogram, echo=FALSE} hist(heights)

3. R Markdown Report

Below is a section of R Markdown code that generates a report.
```
‐‐‐
title: “Final Grade Distribution”
output: pdf_document
‐‐‐
```{r, echo=FALSE}
load(file=“my_data.Rmd”)
summary(grades)```
```

Select the statement that describes the file report generated by the R markdown code above.
- [X] A. A PDF document called “Final Grade Distribution” that prints a summary of the “grades” object. The code to load the file and produce the summary will not be included in the final report.
- [ ] B. A PDF document called “Final Grade Distribution” that prints a summary of the “grades” object. The code to load the file and produce the summary will be included in the final report.
- [ ] C. An HTML document called “Final Grade Distribution” that prints a summary of the “grades” object. The code to load the file and produce the summary will not be included in the final report.
- [ ] D. A PDF document called “Final Grade Distribution” that is empty because the argument echo=FALSE was used.

4. Report File Format

The user specifies the output file format of the final report when using R Markdown.

Which of the following file types is NOT an option for the final output?
- [X] A. .rmd
- [ ] B. .pdf
- [ ] C. .doc
- [ ] D. .html

## Git and GitHub

1. Git and GitHub Benefits

Which statement describes reasons why we recommend using git and Github when working on data analysis projects?
- [ ] A. Git and Github facilitate fast, high-throughput analysis of large data sets.
- [X] B. Git and Github allow easy version control, collaboration, and resource sharing.
- [ ] C. Git and Github have graphical interfaces that make it easy to learn to code in R.
- [ ] D. Git and Github is good for long-term storage of private data.

2. Using Git at the Command Line

### Cloning a Repo

Select the steps necessary to:
1. create a directory called “project-clone”,
2. clone the contents of a git repo at the following URL into that directory (https://github.com/user123/repo123.git), and
3. list the contents of the cloned repo.
- [ ] A.
```
mkdir project-clone
git add https://github.com/user123/repo123.git
ls
```
- [ ] B.
```
mkdir project-clone
git clone https://github.com/user123/repo123.git
ls
```
- [X] C.
```
mkdir project-clone
cd project-clone
git clone https://github.com/user123/repo123.git
ls
```
- [ ] D.
```
mkdir project-clone
cd project-clone
git clone https://github.com/user123/repo123.git
less
```
3. Git Status

You have successfully cloned a Github repository onto your local system. The cloned repository contains a file called “heights.txt” that lists the heights of students in a class. One student was missing from the dataset, so you add that student’s height using the following command:
```
echo “165” >> heights.txt
```
Next you enter the command git status to check the status of the Github repository.

What message is returned and what does it mean?
- [X] A. modified: heights.txt, no changes added to commit This message means that the heights.txt file was modified, but the changes have not been staged or committed to the local repository.
- [ ] B. modified: heights.txt, no changes added to commit This message means that the heights.txt file was modified and staged, but not yet committed.
- [ ] C. 1 file changed This message means that the heights.txt file was modified, staged, committed, and pushed to the upstream repository.
- [ ] D. modified: heights.txt This message means that the heights.txt file was modified, staged, and committed.

4. Modifying a File in an Upstream Repo

You cloned your own repository and modified a file within it on your local system. Next, you executed the following series of commands to include the modified file in the upstream repository, but it didn’t work. Here is the code you typed:
```
git add modified_file.txt
git commit -m “minor changes to file” modified_file.txt
git pull
```
What is preventing the modified file from being added to the upstream repository?
- [ ] A. The wrong option is being used to add a descriptive message to the commit.
- [X] B. git push should be used instead of git pull.
- [ ] C. git commit should come before git add.
- [ ] D. The git pull command line needs to include the file name.

5. Creating a GitHub Repository Readme File

You have a directory of scripts and data files on your computer that you want to share with collaborators using GitHub. You create a new repository on your GitHub account called “repo123” that has the following URL: 
```
https://github.com/user123/repo123.git
```
Which of the following sequences of commands will convert the directory on your computer to a Github directory and create and add a descriptive “read me” file to the new repository?
- [ ] A.
```
git init
git add README.txt
git commit -m "First commit. Adding README file."
git remote add origin `https://github.com/user123/repo123.git`
git push
```
- [ ] B.
```
echo “A new repository with my scripts and data” > README.txt
git init
git add
git commit -m "First commit. Adding README file."
git remote add origin `https://github.com/user123/repo123.git`
git push
```
- [ ] C.
```
echo “A new repository with my scripts and data” > README.txt
git init
git add README.txt
git commit -m "First commit. Adding README file."
git remote add origin `https://github.com/user123/repo123.git`
git pull
```
- [X] D.
```
echo “A new repository with my scripts and data” > README.txt
git init
git add README.txt
git commit -m "First commit. Adding README file."
git remote add origin `https://github.com/user123/repo123.git`
git push
```
## Advanced Unix Arguments

1. Arguments

What will the command ls -lat produce?
- [X] A. A list of all file (names, sizes, and other information) arranged in chronological order with the most recently modified files at the top of the list.
- [ ] B. A list of visible files (names, sizes, and other information) arranged in chronological order with the oldest files at the top of the list.
- [ ] C. A list of all files (names only) arranged in chronological order with the oldest files at the top of the list.
- [ ] D. A list of visible files (names only) arranged in chronological order with the most recent files at the top of the list.

Note: The -l argument makes the list “long”, meaning that information other than just the filename will be provided. The -a argument says that you want to see “all” files, even the hidden ones. The -t argument sorts the list by time, with the most recent files at the top.

2. Arguments 2

What happens when you remove a directory using the command rm -r?
- [ ] A. You cannot remove a directory using the rm command.
- [X] B. You permanently remove the entire directory, including all files and subdirectories.
- [ ] C. You move the entire directory to a trash folder, but it can be restored later.
- [ ] D. You get a warning message asking if you want to proceed, then you delete the directory.

Note: Use remove commands with caution in Unix. You can permanently delete entire directories with no warning.

3. Advanced Unix Getting Help and Pipes

### Getting Help and Pipes

By default, the head command in Unix displays the first 10 lines of a specified file. You can change the number of lines using an argument that indicates the numeric value of the desired number of lines.

Which of the following commands displays only the first 6 lines of a manual for the ls command?
- [ ] A. man ls -6 | head
- [ ] B. head | man ls -6
- [ ] C. head -6 | man ls
- [X] D. man ls | head -6

4. Advanced Unix Wildcards

### Wildcards

You have a directory containing the following files.

data1.csv, data2.txt, data3.txt, Data8.csv, data13.csv, data18.txt, Data22.txt, Data34.csv

Which command will list only all of the .txt files that have “data” in their name? Remember that commands are case-sensitive.
- [ ] A. ls data*
- [X] B. ls data*.txt
- [ ] C. ls *.txt
- [ ] D. ls data?.txt

### Wildcards 2

You have a directory containing the following files.

data1.csv, data2.txt, data3.txt, Data8.csv, data13.csv, data18.txt, Data22.txt, Data34.csv

Which command will remove every file that begins with “D”?
- [X] A. rm D*
- [ ] B. rm D*.txt
- [ ] C. ls D*
- [ ] D. ls D*.txt

### Wildcards 3

Imagine you have multiple text files in the following directory: /Users/student/Documents/project.

You enter the following commands in sequence:
```
mkdir data
mv *.txt data
cd data
```
What will be printed to the screen if you enter the ls command after executing the three lines of code shown above?
- [ ] A. /Users/student/Documents/project/data
- [X] B. The file names that were moved from the “project” directory into the “data” directory.
- [ ] C. Nothing. You haven’t added anything to the new “data” directory yet.
- [ ] D. The file names that remain in the “project” directory.

5. Advanced Unix Environment Variables and Shells
    
### Environment Variables and Shells

What does the command echo $HOME do?
- [ ] A. Moves into to the home directory. 
- [ ] B. Makes the current directory the home directory. 
- [X] C. Prints the path to the home directory. 
- [ ] D. Prints “$HOME” to the screen.

### Environment Variables and Shells 2

Many systems operate using the Unix shell and command language, bash. Each time you start using bash, it executes the commands contained in a “dot” file. Your “dot” file may be called something like “.bash_profile” or “.bash_rc”.

Which command will let you see your “dot” files?
- [X] A. ls -a
- [ ] B. ls bash*
- [ ] C. head *bash*
- [ ] D. ls -l

6. Advanced Unix Executables, Permissions, and File Types
    
### Executables, Permissions, and File Types

Your colleague was editing his “dot” files when something went wrong. He first noticed there was an issue when he tried to execute the following line of code:
```
ls
```
He received the following error:
```
-bash: ls: command not found
```
What could have happened to cause this error?
- [ ] A. He is trying to execute ls which is a bash command, but his system isn’t running bash as a shell.
- [ ] B. The command ls doesn’t exist. He should be using the command ll.
- [ ] C. He forgot to specify a file name to be listed. The command ls * should work.
- [X] D. He changed the information contained in $PATH. Now the system cannot find the executable file for ls.

### Executables, Permissions, and File Types 2

The bash profile in your home directory contains information that the bash shell runs each time you use it. You can customize the information in your bash profile to tell your system to do different things. For example, you can make an “alias”, which acts like a keyboard shortcut.

Which line of code, when added to your bash profile, will let you print “seetop” to view the name, size, and file type of the 10 most recently added visible files?
- [ ] A. alias seetop=’ls -lt’
- [X] B. alias seetop=’ls -lt | head’
- [ ] C. alias seetop=’ls -t | head’
- [ ] D. alias seetop=’head | ls -l’
