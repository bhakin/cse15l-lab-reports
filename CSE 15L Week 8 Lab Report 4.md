# CSE 15L
## Lab Report 4
### By: Bhakin Phanakesiri 

**_____________________________________________________________________________________________________________**
**Repo**

[My Repo](https://github.com/bhakin/markdown-parser)

[The person I reviewed repo](https://github.com/Trinnnn/markdown-parser)

**_____________________________________________________________________________________________________________**
**Snippet 1**

![pic1](snippet1.png)
- Expected Output: ```[google.com, google.com, ucsd.edu]```
> Tester Method:

![test1](Tester1.png)


> My Output: 

![output1](myoutput1.png)

- My code fails the test because it was not able to detect the ucsd.edu link, but instead got url.com which is wrong. 



> The person I reviewed Output" 

![output2](Reviewed1.png)

- Thier code fails the test because their code was able to pick up url.com when it shouldn't have. 




**_____________________________________________________________________________________________________________**
**Snipper 2**

![pic2](snippet2.png)
- Expected Output: ```[a.com, a.com(()), example.com]```

> Tester Method:

![test2](Tester2.png) 


> My Ouput:

![output3](myoutput2.png)
- My code failes 




> The person I reviewed Output: 

![output4](Reviewed2.png)
- Their coee fails the test because for the second link, it should be a.com(()), but instead it got a.com((.




**_____________________________________________________________________________________________________________**
**Snippet 3**

![pic3](snippet3.png)
- Expected Output: ```[https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule]```

> Tester Method:

![test3](Tester3.png)


> My Output:

![output5](myoutput3.png)


> The person I reviewed Output: 

![output6](Reviewed3.png)

- Their code fails the test because it returns an empty list even though there is a link in this file which is https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule




**Questions**
1. Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change.

>Answer: 

2. Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.

>Answer:


3. Do you think there is a small (<10 lines) code change that will make your program work for snippet 3 and all related cases that have newlines in brackets and parentheses? If yes, describe the code change. If not, describe why it would be a more involved change.

>Answer:

4. If your code already works on some/all test cases, include an explanation of what were the code changes that allowed the tests to pass.

>Answer