---
layout: project
type: project
image: img/booklist_project_thumbnail.jpg
title: "BookList Application"
# All dates must be YYYY-MM-DD format!
date: 2025-09-11
published: true
labels:
  - Java
  - Coursework
  - Linked Lists
  - GUI
summary: "A Java app to manage books with a linked list."
---


## Project Overview

As a part of my ICS 211 coursework under Professor Blanca Polo in Summer 2025, I developed the BookList Application. This is a Java program that manages books stored in a sorted linked list. The goal of this project was to design a system that could add, remove, and display books by their ISBN and price, as well as ensure that input was valid and that there were no duplicates. It included both back-end data structure (a recursive linked list implementation) as well as a front-end interface (a Swing GUI) for interaction. 

## My Role

My role was to expand and implement the project beyond the starter `Book.java` file provided by Professor Polo. I extended the `Book` class with validation for ISBNs, titles, and prices. I also created and used custom exceptions set by `BookException` to enforce constraints. I then made the BookList class, a recursive linked list that inserts nodes in ISBN order, prevents duplicates, removes entries, and prints subsets of books above a threshold. I also created the `BookGUI`, a Swing interface that lets users interact with the list to add, remove, and filter books with the use of buttons and text fields. Using the `BookListMethodTester.java` provided by Professor Polo, I ensured that error cases would give the correct output.

<img src="/img/booklist_project_flow.png" alt="BookList Application Flow" width="450"/>

## Lessons Learned
From this project, I became more familiar with linked lists, recursion, and exception handling in Java. Using recursive functions in a few helper methods, like inserting into the list and printing it, helped me think about how to set up both the base cases and the recursive steps. Implementing a GUI also helped me think about how aspects of a menu with buttons can affect the look of the whole GUI. This project also helped me practice writing clear comments. Overall, the BookList Application gave me stronger insight into the design and usability of GUIs, sorted linked lists, and recursion.

## Source Code  
The full source code is available on [GitHub](https://github.com/tylornb/BookList-Application).

*Note: I used ChatGPT to help organize my drafts and suggest edits.*
