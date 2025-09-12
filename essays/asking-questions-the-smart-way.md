---
layout: essay
type: essay
title: "Asking Questions That Get Answers"
# All dates must be YYYY-MM-DD format!
date: 2025-09-11
published: true
labels:
  - Communication
  - Stack-Overflow
  - Professional-Skills
---
# Asking Questions That Get Answers


## Introduction
One of the most important skills for software engineers is communication. This is extremely apparent when asking for help. As Eric Raymond emphasizes in *How to Ask Questions the Smart Way*, the quality of an answer is directly related to the way a question is asked. In communities such as Stack Overflow, volunteers donate their time and expertise, so asking questions the smart way is essential. Smart questions are well-researched, respectful to the community's time, and precise. Not-so-smart questions lack preparation and are much less likely to receive a quality answer.

## What Makes a Question Smart
Before asking a question, Raymond emphasizes in [*How To Ask Questions The Smart Way*](http://www.catb.org/esr/faqs/smart-questions.html) that the user should use all other avenues of finding the answer. This includes searching forum archives and the wider web, reading the manual or FAQs, inspecting or experimenting with the problem, asking a knowledgeable peer, and, for programmers, reading the source code. Not doing this makes the person who asked the question look like they are trying to leech off the community, rather than trying to participate in problem-solving.
Once preparation is done, the next step is finding the right forum. You should find a community that matches both the topic and the skill level of the question.
When writing the question, there are some key principles that should be followed. These include a meaningful subject line, clear and precise writing, detailed context, focusing on symptoms rather than theories, and maintaining a respectful tone. By following these principles, the user shows that they are competent and respectful of others’ time, which encourages people to provide help.

## Example of a Smart Question
One example of a smart question comes from Stack Overflow: [*How can I parse a string to a float in C in a way that isn't affected by the current locale?*](https://stackoverflow.com/questions/79744769/how-can-i-parse-a-string-to-a-float-in-c-in-a-way-that-isnt-affected-by-the-cur).
The asker explains that they are writing a program that parses configuration files and user input. The problem is that some locales use a period (.) for decimals, whereas others use a comma (,). In some locales, this caused parsing to return 0 instead of the floating-point number that was expected.
The developer further explains that the obvious fixes won't work. For example, they can't just set the locale to “C”, and they explained that their program needs to support many languages for the users, and it runs in multiple threads, so switching locales isn’t safe.

This is a good, smart question because the title is clear, the problem is explained in depth, the user showed what they tried and why it didn't work, and gave the programming environment. Because of this, the community was willing to take time out of their day and gave useful answers. There was even a back-and-forth conversation that ended in an accepted solution. 
Now, this post serves as a helpful reference for programmers who are having problems with the same issue.

## Example of a Not-So-Smart Question
On the other hand, consider this example:
[Resumable download file in java](https://stackoverflow.com/questions/79761495/resumable-download-file-in-java)  *(Note: This Stack Overflow post has since been removed, but the summary and comments reflect how it appeared before deletion.)*
The title implies a question about implementing resumable download files in Java, but the body is confusing and seems unrelated. The first line mentions “testing a washing machine without water” (whatever that means)  and then a massive block of Java code. After the code, the user seems to shift to the topic of hiding admin services in Swagger UI while keeping them in the Swagger JSON. 
The problems with this question are very apparent. The title does not match the body, the writing is incoherent with no clear description of the problem, there is no context, expected behavior, or specified errors, and the focus seems to be scattered, asking two unrelated questions. Due to these issues, the post was closed within minutes with a notice that it “needs details or clarity”.

The comments made before the question was closed show the obvious confusion. One user wrote:  


> 1) "Hi there my test washing machine without water and Activated Users Can See Links my test washing machine motor like admin" - What are you talking about?  
> 2) "I wanna hide some services like admin in swagger ui but keep them in swagger json file prevent all requests during first action." - What does that have to do with the code in your question? – Stephen C

Instead of enabling helpers to provide a solution, the community has to waste time just trying to figure out what the user meant.

## Conclusion

Comparing these two examples makes the difference extremely clear. A well-written question gets useful answers that can even help others in the future. An unclear and messy question just wastes everyone's time. This shows that if you do the preliminary research, clearly explain the problem, and respect the reader's time, the resulting answers will be much better. Asking smart questions isn’t just about trying to get help; it's about putting the very important skill of good communication into practice.


*Note: I used ChatGPT to help organize my drafts and suggest edits.*
