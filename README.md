# Linkmanager
Little python script I made.

How to use it: 

1. Place Linkmanager.py somewhere, for example in "/home/(yourusername)/Linkmanager.py".

2. Make Linkmanager.py executable, so run "sudo chmod +x /home/(yourusername)/Linkmanager.py".

3. Now you can run it using "sudo /home/(yourusername)/./Linkmanager.py".

To make it easier for you to run, make a symbolic link to where you have your Linkmanager.py file, and link it to your /usr/bin with a name you choose. You can do this using Linkmanager.py itself:

1. Run Linkmanager.py: "sudo /home/(yourusername)/./Linkmanager.py".

2. Type in "add".

3. Choose whether you'd like path assistance or not, type in y or n. I typed y.

4. Enter the start of your path to your Linkmanager.py file, in my case, "home".

5. Then enter the next part, untill you reach "Linkmanager.py"

6. Press CTRL + C, it will show you the full path to your Linkmanager.py file. 

7. Give it a name, I went for "linkmanager".

8. Type in y to confirm. 

Now next time, you can run Linkmanager using "sudo linkmanager".
