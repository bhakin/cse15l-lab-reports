# CSE 15L
## Lab Report 5
### By: Bhakin Phanakesiri 
---
> ## Test 1 

#### Test-File: 547 : Link to the [test file](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/547.md) 


![test547](NewOutput1.png)

```Expected OutPut: [] ```

Output from my repo and the TA's repo: 
![output1](output1.png)
- The Left Part is the output from my MarkdownParse and the Right Part is the output from the TA's MarkdownParse. 
- My MarkdownParse gave me an infinite loop since it was not able to produce any list, so therefore, my MarkdownParse gave me the wrong answer. However, for the TA's MarkdownParse, it produce the right answer which is an empty list.


> How did I find the tests with different results? 

I found the tests with different results by using vim diff. As you can see in the picture above, I used vimdiff and found that my MarkdownParse produces a different answer from the TA's MarkdownParse.  

>How can I fix my the code? 

![fix1](FixCode1.png)
This is the code from my MarkdownParse. The part that is highlighted should be fixed since in this test-files, there is no close paren, so adding it to the currentIndex would not work. To fix this, I think that we should not use close paren, but instead use another variable like open or close brackets. OR the another way to fix this, is to add an if statement and see if there is an open paren and close paren or not. If there is an open paren and close paren, we know that there might be a link inside, but if there is no open paren or close paren then I should return an empty list. 


> ## Test 2

#### Test-File: 495 : Link to the [test file](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/495.md) 

![test495](Test495.png)

```Expected Output: [foo(and(bar))]```

Output from my repo and the TA's repo: 
![output1](output2.png)
- The Left Part is the output from my MarkdownParse and the Right Part is the output from the TA's MarkdownParse. 
- Both my MarkdownParse and my TA's MarkdownParse produce the wrong answer for this file. My MarkdownParse was able to get the name of the link, but didn't get the 2 parenthesis at the end. However, for the TA's MarkdownParse, it was not able to identify that foo and bar was a link, so it return an empty list. 

> How did I find the tests with different results? 

I found the tests with different results by using vim diff. As you can see in the picture above, I used vimdiff and found that my MarkdownParse produces a different answer from the TA's MarkdownParse.  

>How can I fix my the code? 

![fix2](FixCode2.png)
This is the code from my MarkdownParse. The part that is highlighted should be fixed. This if statement should be fixed because it only account for one close paren. This is why my code was not able to get the last 2 close parenthesis because it thought that the link was done when there is a close paren. To fix this code, I can create a new condition to my if statement saying that if there is a still close paren, ignore that one and stop when there is no more close paren. This will hopefully make my code to be able to get the last 2 close parenthesis from this test file. 

**_____________________________________________________________________________________________________________**
# Thank You!