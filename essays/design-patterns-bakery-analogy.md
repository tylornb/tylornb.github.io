---
layout: essay
type: essay
title: "Reusable Techniques: From Pastries to Design Patterns"
date: 2025-12-04
published: true
labels:
  - Design Patterns 
  - Software Engineering
---

## Reusable Techniques: From Pastries to Design Patterns
Much like how baking in a work environment relies on established techniques like folding, proofing, or measuring specific ingredients to keep production consistent every day, software engineering uses design patterns to keep consistency and structure to recurring situations. These patterns are not full implementations, much like how a technique in baking is not a finished pastry, but they give developers approaches that they can use in similar problems.

## Recognizing Patterns in Software
Design patterns are used to simplify issues that arise in nearly every project, like managing state changes, creating objects, or avoiding duplicated logic. Once you understand the structure of these patterns, the focus can shift to how the system should behave and less on re-writing very similar solutions to problems that have the same design pattern, from scratch.

## In Our Final Project
In our Rainbow Recipes project, a few design patterns showed up naturally as the app got bigger. React itself uses an Observer-style pattern, and we relied on that heavily. Any time the user changed a filter or typed in the search bar, the UI automatically re-rendered based on the new state. Our filtering and sorting logic also used something like the Strategy pattern since we switched between different “ways” of sorting or narrowing down the recipes, depending on the user's action. When displaying the recipe list, we used a factory-like pattern by mapping each recipe into the same card layout, generating a consistent UI structure from raw data. Also, React’s component composition pattern was a large part of the project as well, since we combined smaller components like cards, panels, and vendor items to structure the UI. For the backend, we used Prisma, which acts like a Singleton because the entire app uses one shared database client. 

## The Value of Reusable Techniques
Overall, working on this project made it clear why design patterns matter in software engineering. They kept the code organized as the number of features grew, reduced a lot of duplicated logic, and made the app easier to update. Just like baking techniques guide the process behind a pastry, design patterns guided the structure behind our features as the project got more complicated. It helped with making the project feel more manageable and something I’ll utilize in future software engineering work.


*Note: I used ChatGPT to help organize my drafts and suggest edits.*
