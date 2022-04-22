# CSE 15L
## Lab Report 2
### By: Bhakin Phanakesiri 

---
> **CODE 1**

![pic1](MarkdownParseCode1.png)

Here is the [link](https://github.com/bhakin/markdown-parser/commit/99c0c45dcad69a7a68ff6e10e3c2e7fcd25ce705) to the picture above.

Symtom:
![problem1](MardownParseProblem1.png)

- The symtom for this case is the infinite loop since no codes should be producing an infinite loop.
- Since the symtom is the infinite loop, the bug would also be the program the infinite loop.
- In this case, the failure-inducing input is the test_file.md, but this symtom will appear on a file that has an extra line on the file. 

---
> **CODE 2**

![pic2](MarkdownParseCode2.png)

Here is the [link](https://github.com/bhakin/markdown-parser/commit/006f6af6b2ac319e0990790aa5166f8f8b52a68c) to the picture above. 


Symtom: 
![problem2](MarkdownParseProblem2.png)
- The symtom is that this codes give us a wrong answer. The answer we are looking for is an empty array, but instead it gives us a link that apeears after a paragraoh. 
- A bug in this case is the code inability to detect a paragraph between the brackets and the parenthesis. 
- In this case, the failure-inducing input is the test_file5.md, but this symtom will appear on a file that has something in between of the brackets and the parenthesis. 

---
> **CODE 3**

![pic3](MarkdownParseCode3.png)

Here is the [link](https://github.com/bhakin/markdown-parser/commit/e53c26bf86ff1e4a6af833fbedfd5109e46c259f) to the picture above. 


Symtom:
![problem3](MarkdownParseProblem3.png)
- The symtom for this case is that it gives us a wrong output. As we can see in the picture above, this is not a link, it is a picture so therefore the correct answer should be an empty array. 
- Similary, the bug is code inability to differentiate a link and a picture. 
- For this case, teh failure-inducing input is the test_file6.md, but this symtom will pop up when we tried to implement a picture on markdown. 

---

# Thank You