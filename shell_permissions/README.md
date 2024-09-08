Create a script that switches the current user to the user betty.

You should use exactly 8 characters for your command (+1 character for the new line)
You can assume that the user betty will exist when we will run your script
julien@ubuntu:/tmp/h$ tail -1 0-iam_betty | wc -c
9
julien@ubuntu:/tmp/h$
root@d161cc58c15d:/# whoami
root
root@d161cc58c15d:/# touch hello
root@d161cc58c15d:/# chmod u+x hello
root@d161cc58c15d:/# chmod u+x,g+x,o+r hello
root@d161cc58c15d:/# chmod 751 hello
root@d161cc58c15d:/# 
