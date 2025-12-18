---
layout: essay
type: essay
title: "Reflecting on Software Engineering Beyond Web Development."
date: 2025-12-17
published: true
labels:
  - Reflection
  - Software Engineering
  - ICS 314
---
## Introduction
Going into ICS 314, I expected software engineering to be more than just learning how to build web applications, even though the class mainly focused on web development. By the end of the course, this idea was solidified. Software engineering is not just about writing frontend and backend code, but also about how developers organize their work, work with other people, and handle growing projects. Two concepts from this class that stood out to me beyond just web development were coding standards and design patterns.

## Coding Standards
Before this class, I didn’t really know what coding standards meant. I mostly thought it just meant that the code should be written “well” or look clean, not knowing much about why it mattered. Throughout the course, though, I learned that coding standards are not just things like spacing or formatting, but more about making consistent and easy-to-read code.

Having shared coding standards helps reduce the number of ways code can be written. When everyone follows the same general guidelines, it becomes much easier to understand others’ code. This becomes even more important when working in teams, because constantly switching between styles in the same project would make things very confusing and slow down development.

Using tools such as ESLint and VSCode makes coding standards much more noticeable. ESLint errors were often frustrating and sometimes felt like they got in the way of actually coding. However, throughout the semester, I realized that these rules helped build better habits. Code became easier to read, debug, and more uniform. When everything has the same structure, spotting simple mistakes like missing brackets or syntax errors becomes much easier to find. These benefits are broader than just web applications, especially when multiple people are working on the same codebase.

## Design Patterns
Before taking ICS 314, I had no idea what design patterns in software engineering were. Now, I understand them to be reusable solutions to common problems that show up in many software projects. They are not complete pieces of code, but approaches that developers can apply to different situations.

Design patterns help simplify problems that appear many times, like managing state, organizing code, or avoiding repeated logic. Using these design patterns, developers can focus more on what the program should do, rather than constantly rewriting similar solutions from scratch.

In our Rainbow Recipes final project, several design patterns showed up naturally as the application grew. React itself follows an Observer-style pattern, where changes in state automatically update the user interface. This happened when users did things like change filters or typed into the search bar, which caused the UI to update automatically. Our filtering and sorting logic also worked like a Strategy pattern, since the app switched between ways of sorting or narrowing down results, according to the user's actions. We also used a factory-like approach by mapping recipe data into consistent card components. React component composition also enabled us to build the interface using smaller, reusable components. On the backend, Prisma acted like a Singleton because the same database client was shared across the entire application.

Working with these patterns showed me that they are not just abstract ideas/patterns; they are actually practical tools that are widely used. They helped keep the project organized, reducing duplicated code and making it easier to add new features as the project grew. These ideas are not only useful in web development, since many software projects face similar structural problems.

## Conclusion
By the end of ICS 314, my understanding of software engineering changed from thinking it was mostly about writing code to realizing that it also involves communication, teamwork, structure, and planning. Coding standards and design patterns showed me how shared rules and reusable solutions make working on larger projects easier, especially when working with a team. These concepts apply beyond web applications, and are ideas that I expect to use in future projects.

*Note: I used ChatGPT to help organize my drafts and suggest edits.*
