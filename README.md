# bash_file_truncate


Linux How To Truncate A File
It is easy to truncate a file from the command line on Linux

# >echo > test.log
You can also just use the redirection operator by itself like this.


# > test.log
There also exists a truncate command which allows you to truncate a file to whatever size you want. In this case we are setting the size to zero which will effectively empty the file.


# >truncate -s 0 test.log
