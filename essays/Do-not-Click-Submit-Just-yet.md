---
layout: essay
type: essay
title: Do not Click Submit Just Yet
date: 2020-09-24
draft: false
labels:
  - JavaScript
  - ESLINT
---

It was my second quiz for ICS 212 and there was only one question left with three minutes remaining. The question was a simple figure out the total for the variable count after looping through 5 times. The given pseudocode was as follow:
```
int main(int arg, char*[])
    int i = 0;
    int count = 0;
    while (i  < 5)
    count++; 
    i++;
```
And my first thought was count is 5. I clicked submit and got it wrong. It turns out the code does not even work properly. Instead it loops infinitely with count incrementing forever. So, after looking through the quiz again it turns out that the increment ‘i’ was not even inside the loop. Why? 'i' was not indented to indicate that ‘i’ was inside the loop. The count was technically still inside the loop because any loop can execute the next line without the braces. This was our professor’s way of teaching us a lesson on submitting codes that do not comply with the coding standard. This simple question taught me the valuable lesson that not following the coding standard can make you misinterpret codes and risk getting points deducted.
## My Previous Experience with Coding Standard
When I first started coding in Java, I would often just write out the code disregarding the amount of spaces and indentation used. The names I give to my variables would be a letter since the code we had to implement at the time were short and simple. Since Eclipse formats your code for you, I adopted the habits of just letting the IDE do the work for me. So, I never bothered to take notice of the coding standard. Our coding standard was the Eclipse’s format option, which it just indents and spaces out your code neatly. However, as soon as I was in a data structure and C/C++ class, we were following a different coding standard. We have to follow it, or we lose points. This was when I learned that the coding standards mattered. 

The coding standard for data structure was almost like Eclipse but added some new requirements. I had submitted codes before that had some violations to the coding standard. And to my surprise even though the program works I still get plenty of points deducted because it was not ‘formatted’ correctly. If it was not formatted correctly then it was a bug in your code. Just formatting the code with the Eclipse option was not enough. The good news was the check style we used on Eclipse would highlight the lines in the code that violates the coding standard. The bad news was every violation must be fixed manually. The most tedious work was, on top of every function definition, we had to include a comment summarizing the function. This includes the name of the function, parameters being passed, the function’s purpose, and its return value. Then for every variable created, we also had to comment its purpose briefly. As for each class created a short comment must be made that summarizes its purpose. So why did we bother to do all this? The simple reason was for organization and to make your code legible. The codes we had to implement were very long and sometimes complicated. So, by having these comments it helps me to organize each function and to quickly tell what each function does.

AAs for C and C++, we used Unix, which had to be done manually. From scripting to create a class file, source file, and header file, to compiling/linking and executing. For the source file we had to manually write the code on ‘Vi’, so that it follows the coding standard, which just added more work. There was a decent script provided by the TA that would check for violations, but it just tells you the lines that need to be fixed. All I can say is it was a pain having to look through 100+ lines of violations rather than fixing it. Manually trying to keep my code to follow the coding standard was a pain at first, but it soon became a habit. When I write out my pseudocode, following the coding standard allows me to organize my code so that I can easily trace it. Manually fixing coding violations was not fun but it is necessary to write efficient and organized codes. 


## Adjusting to ESLINT in Itellij
When it comes to coding, it is best to code in an Integrated Development Environment rather than in Unix. The coding standard for C and C++ is straight forward. Unfortunately, in Unix, this had to be done manually. Which is why I prefer writing my code in any IDE such as Eclipse or intellij. The coding standard we are following is ESLINT. The coding standard is straightforward as it adopts a similar coding standard as from Unix and Eclipse. Following the coding standard was also easy because, like Eclipse I was able to import a check style that would format my code. And there would be an indicator that notifies me for any violations. The best part is the violation tells me briefly as to why it violates the coding standard. And if I ever need to read up more on the violation, I can easily search it up to learn more. The downside to ESLINT is its automatic check. Just writing your first line of code immediately gives a violation stating that this variable is not in use. This gets worse when I start writing out my functions. The red squiggly lines can be very distracting. And I often lose track of the opening and closing parenthesis. Trying to get that green check, stating the code no longer violates any of the coding standards, can sometimes be challenging. Since I am still new to ESLINT, I sometimes need to look up the violation at the ESLINT documentation just so I can fix the error. But even though I must do the extra work, writing a well formatted code is all worth it.

Every programming language class I had taken enforces a strict coding standard. These coding standards depend on the type of language you are using. At the beginning of my journey in programming, following the coding standard was easy with the Eclipse format. With this option, I was free to write out my code without having to worry about any violation to the coding standard. However, as I progressed through the different programming courses, this option became obsolete as I had to adopt a new practice of manually fixing any coding standard violations. This was when it started to become a hassle, but in doing so it was worth the extra work.


