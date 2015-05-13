# Linux_issues

###How can you find the creation date of a file?

Linux offers three timestamps for files: time of last access of contents (atime), time of last modification of contents (mtime), and time of last modification of the inode (metadata, ctime).

http://moiseevigor.github.io/software/2015/01/30/get-file-creation-time-on-linux-with-ext4/

####But no creation date?!

Even though the file system ext4  adds support for date-created timestamps. The Linux kernel does not provide a kernel API for accessing the file creation times : (

http://unix.stackexchange.com/questions/91197/how-to-find-creation-date-of-file
