---
layout: essay
type: essay
title: "Building Confidence Through TypeScript and ASE"
# All dates must be YYYY-MM-DD format!
date: 2025-09-03
published: true
labels:
  - TypeScript
  - Athletic Software Engineering
  - WODs
---

## Introduction
Starting at the beginning of this Fall 2025 semester, I have been challenged on two fronts: learning TypeScript as a new language and adapting to the athletic software engineering (ASE) pedagogy. Coming from a background of only Java, I first had to learn JavaScript before learning TypeScript’s stricter, but type-safe environment. At the same time, I was introduced to ASE and Workout Of the Days (WODs) in the context of software engineering. WODs are timed coding exercises that can be practiced or tested on to increase efficiency and correctness while coding. At first, TypeScript and ASE felt uncomfortable, but from the experience I’ve had with them so far, I believe that they can act as a strong training ground for improving accuracy, speed, and confidence as a software engineer.

## Learning TypeScript
JavaScript, compared to Java, feels like learning a new, but slightly easier language than Java. However, when coding in JavaScript, I would encounter errors in many cases where I wasn’t sure what was wrong with the code. When I started learning TypeScript, it was difficult to remember when and where to use things like typecasting, and learning the additional syntax in TypeScript was difficult as well. However, TypeScript gave me a sense of stability compared to JavaScript through compile-time errors. For example, JavaScript will execute code that has pitfalls that may not be that obvious. 
```javascript
let numberOne = 1;
let numberTwo = "2";
let sum = numberOne + numberTwo; //Acts as string concatenation because numberTwo is a string.
console.log(sum); //Will output 12 instead of the desired 3.
```

 On the other hand, TypeScript will flag the same issue before the code even runs.
```typescript
let numberOne: number = 1;
let numberTwo: string = "2";
let sum = numberOne + numberTwo; //Compile-time error
```

This led to a steep learning curve, but gave me a sense of clarity when writing code.

## Athletic Software Engineering and WODs
Athletic software engineering is a pedagogy in software engineering that assists coders to reach competency in software engineering skills through the use of intense, time-constrained, and stress-inducing situations in coding.

WODs, in the context of software engineering, are exercises that can be done to practice correctness while coding. These WODs are also timed, with an upper bound limit to practice efficiency. 

This style of learning is very stressful, especially when doing it for a graded assignment instead of practicing them outside of class. The first time I attempted a WOD, I encountered a small syntax error that I would have normally easily found, but with the stress, it took much longer than expected. However, I believe that both the in-class and at-home WODs have so far, and will continue to, increase my knowledge of both the syntax and use of the different aspects of TypeScript.

## Training Under Pressure
I think that as the semester goes on, and I do more WODs, it will only increase my knowledge and efficiency with TypeScript. The analogy to athletics is fitting; just as athletes perform with the stress of competition, software engineers need to work effectively to meet deadlines. Discomfort during WODs builds confidence in handling uncomfortable situations, which is likely the case during things like interviews, where you must show your skills in real time, similar to how the WODs function.

## Building Skills for the Future
Together, TypeScript and ASE both contribute to and shape my growth as a developer. Although stressful, they have increased my knowledge of TypeScript and how to use it. While demanding, both learning experiences are properly preparing me for some of the realities of professional software engineering, where efficiency and correctness are essential. Beyond this semester, I see ASE as both a pedagogy and a skill that I can continue to use when learning new coding languages and their complexities, while also practicing efficient and correct code.

*Note: I used ChatGPT to help organize my drafts and suggest edits.*
