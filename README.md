# Switching-Proxies
Switch proxies in ubuntu system quickly just by one key-press.

1. Make a file similar to the sample.txt replacing only your proxy settings in it. (Try to make the file in home directory so that u can avoid the cd commands while changing directories in terminal for further steps.)
2. Remember if your proxy credentials contains symbols in it like !,@,#,etc. then type \ before it. (escape character)
3. If proxy doesn't require "username" and "password", then remove "username:password\@" part.
4. Then open terminal Ctrl + Alt + T and go to the directry which contains the .txt file by cd commands.
5. Type "chmod +x filename.extension" (makes the file executable).
 
You are done !!

Now to change the internal proxy anytime just go to the directory containing the .txt file and open it by "./filename.extension".Type your system password and then proxy is changed. 
