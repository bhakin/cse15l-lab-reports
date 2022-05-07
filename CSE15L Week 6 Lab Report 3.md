# CSE 15L
## Lab Report 3
### By: Bhakin Phanakesiri 

---
> **Group Choice 1: Streamlining ssh Configuration**

![pic1](Configuration.png)
- First, I looked for the .SSH file on my computer and create a new file called config.
- Then, I copied the code below to the config file:
```
Host ieng6
    HostName ieng6.ucsd.edu
    User cs15lsp22zzz (use your username)
```

![pic2](LoggingInWithieng6.png)
- After, I saved the config file, I opened the terminal typed ssh ieng6 and the result is the picture above.
- ieng6 is the username I chose to replace my cs15l account.


![pic3](SCPusingieng6.png)
- Then, I copied MarkdownParse.java to the server using my new username. 
- As we can see in the picture above, I sucessfully copied MarkdownParse.java to my cs15l account. 


---
> **Group Choice 2: Setup Github Acess from ieng6**

![pic4](PublicKey.png)





> **Group Choice 3: Copy whole directories with scp -r**

![pic7](CopyingWholeDirectory.png)

![pic8](RunningMarkdownOnieng6.png)

![pic9](RunningInOneLine.png)
