# Project 5 File System Checker

## Description

In this project, I made a file system checker, which can read through the system image and check if the file has any following errors listed in our website: http://pages.cs.wisc.edu/~swift/classes/cs537-fa17/wiki/pmwiki.php/Site/Project5a. 

I used the structure listed in fs.h, such like superblock, dinode and dirent. 

Also I watched the tutorial video made by professor remzi: https://www.youtube.com/watch?v=ycyM6fuRFhY.

For test 20-22, I failed several times, and eventually, I found that there might be gap between directory so I fixed it.

For extra credit part, I tried to use the images provided to test, but I keep getting errors of bad references. I used ls -l to check the status of the files but it turns out that I cannot write it in. I think there is something wrong with mmap function but I have not figured it out yet.