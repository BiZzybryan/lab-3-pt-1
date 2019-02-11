# lab-3-pt-1Lab - Review
==========
Follow the instructions line-by-line.  

* Type in the commands as is, but ignore the beginning prompt.  
* Enter, tab, up and down are represented by <ENTER><TAB>,<UP> and <DOWN>.  
* "No output" or "nothing happens" are valid answers to any of the questions.
==========

==========
This lab will review downloading and uncompressing files, and it will get us set up for the remainder of the labs.
==========
==========
1. Go to your home directory.

Write the command that you used to do this below:
----------bryan.pierrelouis02$ ~
-bash: /Users/bryan.pierrelouis02: is a directory


==========
2. Prove that you're in your home directory.

Write the command that you used to do this - as well as its output - below :
----------pwd
/Users/bryan.pierrelouis02



==========
3. Are there any directories or files in your directory that have the word mtec1003 in it?

Write the command(s) that you used to determine this - as well as its output - below:
----------cd mtec1003
-bash: cd: mtec1003: No such file or directory


==========
4. If there are directories or files in your home directory that have the word mtec1003 in them, list them below (otherwise skip this step):
----------



==========
5. Delete these directories from your home folder by using this command:

$ rm -rf [name of directory/folder]

for example:

$ rm -rf mtec1003-labs-02

(skip if these directories don't exist)
----------



==========
6.  A compressed archive (.tar.gz) of the lab files can be found at this url: 

http://entertainmenttechnology.github.io/Wilson-MTEC1003/labs/03/mtec1003-lab-03.tar.gz

Download this file to your home directory into a file called mtec1003-lab-03.tar.gz   

Use a command that we learned to do this.

This command should have a *flag* to specify the output file.  MAKE SURE TO NAME YOUR OUTPUT FILE: mtec1003-lab-03.tar.gz

Write the command(s) that you used to download this file - as well as its output - below:
---------- bryan.pierrelouis02$ curl -o github.txt http://entertainmenttechnology.github.io/Wilson-MTEC1003/labs/03/mtec1003-lab-03.tar.gz
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  898k  100  898k    0     0   473k      0  0:00:01  0:00:01 --:--:--  473k


==========
7.  Uncompress the file that you just downloaded.

Write the command(s) that you used to do this - as well as its output - below:
----------tar: Error opening archive: Failed to open 'mtec1003-lab-03.tar.gz'


==========
8.  You should now have a directory called mtec1003-lab-03 in your home directory.  Verify that this directory exists.

If the directory does not exist:

a. go to your home folder
b. go back to step 6

Otherwise...

Write the command(s) that you used to do this - as well as its output - below:
----------cd /Users/bryan.pierrelouis02/Downloads/mtec1003-lab-03 
V217-M11:mtec1003-lab-03 bryan.pierrelouis02$ 



==========
9.  What directories are in the mtec1003-lab-03 folder?

Write the command(s) that you used to determine this - as well as its output - below:
----------drwxr-xr-x@   4 bryan.pierrelouis02  ACADEMIC\Domain Users   128 Feb 13  2013 books
drwxr-xr-x@ 129 bryan.pierrelouis02  ACADEMIC\Domain Users  4128 Feb 11 18:25 logs
drwxr-xr-x@   6 bryan.pierrelouis02  ACADEMIC\Domain Users   192 Feb 13  2013 web

==========
10.  Now... go back home.  Then change to the science-fiction directory using a relative path.  The directory is located in books... which is located in the mtec1003-lab-03 directory.  Verify you're in the right directory using pwd.

Write the command(s) (including going home) that you used to do this below:
---------- bryan.pierrelouis02$ cd books
V217-M11:books bryan.pierrelouis02$ cd science-fiction

==========
11.  Write the files that are in the science fiction directory below.

Write the command(s) that you used to do this - as well as its output - below:
-----------rw-r--r--@ 1 bryan.pierrelouis02  ACADEMIC\Domain Users  448685 Feb 13  2013 pg84.txt
-rw-r--r--@ 1 bryan.pierrelouis02  ACADEMIC\Domain Users  676440 Feb 13  2013 pg86.txt


==========
12.  Again, go back to your home directory.  Now... go to the science-fiction directory using an absolute path!  Verify that you're in the right directory using pwd.

Write the command(s) that you used to do this below:
----------

==========
13. Immediately change back to the mtec1003-lab-03 folder with a single command using a *relative* path.

Write the command(s) that you used to do this below:
----------

==========
14. Find out what the most recently modified directory is in mtec1003 (there are only 3 to choose from)?  How would you find this out?  Hint: perhaps using something to show the modified date... and sort it by time.

Write the command(s) that you used to do this below:
----------

==========
15. Create a compressed archive of the logs folder - that is... take the contents of logs and create a single archive (.tar), and compress (.gz)

Write the command(s) that you used to do this below:
----------
