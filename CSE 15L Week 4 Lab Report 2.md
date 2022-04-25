# CSE 15L
## Lab Report 2
### By: Bhakin Phanakesiri 

---
> **CODE 1**

![pic1](MarkdownParseCode1.png)

Here is the [link](https://github.com/bhakin/markdown-parser/commit/99c0c45dcad69a7a68ff6e10e3c2e7fcd25ce705) to the picture above.

Symptom:
![problem1](MardownParseProblem1.png)

- The symptom for this case is the infinite loop since no codes should be producing an infinite loop.
- Since the symptom is the infinite loop, the bug would also be the infinite loop.
- In this case, the failure-inducing input is the test_file.md, but this symptom will appear on a file that has an extra line at the end. 

---
> **CODE 2**

![pic2](MarkdownParseCode2.png)

Here is the [link](https://github.com/bhakin/markdown-parser/commit/006f6af6b2ac319e0990790aa5166f8f8b52a68c) to the picture above. 


Symptom: 
![problem2](MarkdownParseProblem2.png)
- The symptom here is that the codes give us the wrong answer. The answer we are looking for is an empty array, but instead, it gives us a link that appears after a paragraph. 
- A bug, in this case, is the code's inability to detect a paragraph between the brackets and the parenthesis. 
- In this case, the failure-inducing input is the test_file5.md, but this symptom will appear on a file that has something in between the brackets and the parenthesis. 

---
> **CODE 3**

![pic3](MarkdownParseCode3.png)

Here is the [link](https://github.com/bhakin/markdown-parser/commit/e53c26bf86ff1e4a6af833fbedfd5109e46c259f) to the picture above. 


Symptom:
![problem3](MarkdownParseProblem3.png)
- The symptom here is that the code gives us the wrong output. As we can see in the picture above, this is not a link, it is a picture so therefore the correct answer should be an empty array. 
- Similarly, the bug is the code's inability to differentiate a link and a picture. 
- In this case, the failure-inducing input is the test_file6.md, but this symptom will come up when we try to implement a picture on markdown.

---

# Thank You!
