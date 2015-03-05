# Linkmanager
Little python script I made.

How to use it: 
1. Place Shells.py somewhere, for example in "/home/(yourusername)/Shells.py".
2. Make Shells.py executable, so run "sudo chmod +x /home/(yourusername)/Shells.py"
3. Now you can run it using "sudo /home/(yourusername)/./Shells.py".

To make it easier for you to run, make a symbolic link to where you have your Shells.py file, and link it to your /usr/bin with a name you choose. You can do this using Shells.py itself:
1. Run Shells.py: "sudo /home/(yourusername)/./Shells.py"
2. Type in "add".
3. Choose whether you'd like path assistance or not, type in y or n. I typed y.
4. Enter the start of your path to your Shells.py file, in my case, "home".
5. Then enter the next part, untill you reach "Shells.py"
6. Press CTRL + C, it will show you the full path to your Shells.py file. 
7. Give it a name, I went for "linkmanager".
8. Type in y to confirm. 
Now next time, you can run Linkmanager using "sudo linkmanager".
