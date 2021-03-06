# Welcome to CSE 15L
## Tutorial for incoming CSE 15L students
### By Bhakin Phanakesiri 

---
> **`Step 1: Install VS Code`**

![pic1](vscode.png)

- Download VS Code [here](https://code.visualstudio.com/download)!
- Open up VS Code on your device and it should look something like the picture above.


---
> **`Step 2: Connecting to the Server`**

![pic2](connectingToServer.png)

- Go to this [website](https://sdacs.ucsd.edu/~icc/index.php) to set up your password for your cs15l account. 
- Then go on your terminal and type ```ssh (your cs15l account)```
- Then enter your password for your account.
- If you log in to your account successfully, your terminal should look like the picture above. 


---
> **`Step 3: Trying Some Commands`**

![pic3](commands.png)


- When you are connected to the server, run some commands to see what will happen.
- Some Commands that you could run: ```cd, ls, pwd, mkdir, cp, ls -lat, ls -a```
- Example: when we run ```pwd```,  we would get our current working dictionary. And when we run ```ls```, we would get the list of files on the server. For more examples of the commands, refer to the picture above. 


---
> **`Step 4: Moving Files with scp`**

![pic4](movingFiles.png)


- Create a file on your computer and save it.
- Then go on your terminal and type ```scp (the file name) cs15lsp22zz@ieng6.ucsd.edu:~/``` 
- To check if the file has been copied to your cs15l account, type ```ls``` and see if the name of your file is listed there or not. 
- In the picture above, I created a file on my computer called WhereAmI.java and moved the file into my cs15l account. 


---
> **`Step 5: Setting an SSH Key`**

![pic5](SSHKey.png)


- Create a new key on your computer by typing ```ssh-keygen``` on your terminal. 
- Then type ```scp /Users/<user-name>/.ssh/id_rsa.pub cs15lsp22zz@ieng6.ucsd.edu:~/.ssh/authorized_keys```
with your name and cs15l account on your terminal.
- Lastly, enter your cs15l account's password and if you did it correctly, your output would look like the picture above and you wouldn't need to enter your password to log in to the server again. 


---
> **`Step 6: Optimizing Remote Running`**

![pic6](optimizing.png)


- We can optimize remote running by writing more than one command in a line.
- For example from the picture above, when we run: ```cp WhereAmI.java OtherMain.java; javac OtherMain.java; java WhereAmI```. We would get all of the output from each of the commands.  


# Thank You!
