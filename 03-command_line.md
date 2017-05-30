# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> >  show current working directory path: pwd  
creating a directory: mkdir (directory)  
deleting a directory: rm -r (directory)  
creating a file using `touch` command: touch (file)  
deleting a file: rm (file)  
renaming a file: mv (old) (new)
listing hidden files: ls-a   
copying a file from one directory to another: cp (file) (directory)    
move to home directory: cd ~  
move up one directory: cd ..

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > `ls`: list directory  
`ls -a`: list all files including hidden file starting with '.'  
`ls -l`: list with long format    
`ls -lh`: list long format with readable file size  
`ls -lah`: list all files with long format and readable file size  
`ls -t`: sort by time & date  
`ls -Glp`: G inhibits the display of group information, l displays the contents in long format, and p shows which files have an indicator such as '/'

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > `ls-d`: displays only directories   
`ls-m`: displays the names as a comma-separated list  
`ls-p`: displays directories with /  
`ls-q`: displays all nonprinting characters as ?  
`ls-r`: displays files in reverse order  

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs is a command used to build and execute command lines from standard input.  
The following xargs command is to first find the files and then look for specific keyword on that file using grep command:  
find . -name "*.py" | xargs grep "Stock"



 

