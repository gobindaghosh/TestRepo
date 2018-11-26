# TestRepo

Modifying this file for comparing with last commit without staging.
Ok, $git difftool command showed the comparison between this modified file and last commited file.
Now let me stage it and compare it again.
After staging using $git difftool command is not showing any output.
When I wrote the line above, and then run $git difftool then the comparison showed the result between staged version and the modified version. 
Now let me stage it.
We can compare to commit using their first 8 characters of their commit hash 
Now let me add another file and commit this line change in this README.md file and add some content into test1.txt file. Let me see what happens.
after staging I am writing this line
only the content of the readme file is showing, then test1.txt now lets change the command into $ git difftool test1.txt and voila!! It is now comparing between staged and modified version
When we need to compare with staged and commited file, we need to provide the commited id by which we want to compare the modified file.
$ git difftool d13dc90->First 7 characters of commit id got using  $git log




