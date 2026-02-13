---
layout: essay
title: Why Coding Standards Matter
type: essay
date: 2026-02-12
description: "A reflection on the value of coding standards and learning from ESLint in ICS 314."
permalink: /essays/coding-standards.html
labels:
  - Software Engineering
  - Code Quality
  - ESLint
  - TypeScript
---

<figure style="text-align: center; margin: 20px 0;">
  <img src="{{ '/img/eslint.webp' | relative_url }}" alt="ESLint screenshot"
       style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;">
  <figcaption style="font-size: 0.9em; color: #555;">
    Figure: ESLint catching syntax issues in VS Code.
  </figcaption>
</figure>

## Introduction

When the term “coding standards” comes up in conversation, it often gets eye rolls and groans. Most people immediately think of trivial arguments like tabs versus spaces, where to place curly braces, or how many blank lines to leave between functions.

But brushing off coding standards as mere style points misses the bigger picture. They’re not just about aesthetics—they’re about clarity, consistency, and collaboration. If I had to choose one software engineering practice that most improves code quality across a team or project, it would be enforcing solid coding standards.

---

## Learning Through ESLint

In ICS 314, I began using ESLint with strict TypeScript settings and Airbnb style rules. At first, it felt overwhelming. My screen filled with red warnings about unused variables, quote styles, implicit types, and formatting issues. It felt like everything I wrote was wrong.

But ESLint wasn’t criticizing me—it was teaching me.

It didn’t just highlight problems; it explained why certain patterns were discouraged. It flagged unnecessary variables, suggested cleaner logic, and even caught moments when I was writing in a more C-like style instead of following JavaScript and TypeScript best practices.

Over time, I began to predict what ESLint would flag before saving the file. My code became cleaner, more intentional, and easier to read. I shifted from writing “code that works” to writing code that is maintainable and understandable by others.

In ICS 314 Workouts of the Day, especially when we were required to use functional programming methods like `map`, `filter`, and `reduce`, consistent structure made debugging faster and collaboration smoother. The standards weren’t just rules—they were scaffolding.

---

## Why Standards Matter for Teams

Good coding standards go far beyond formatting. They influence naming conventions, function design, file organization, documentation, and error handling.

When everyone on a team follows the same conventions, the codebase feels unified. Reading someone else’s file doesn’t feel like decoding a different dialect. Instead, it feels like continuing a shared conversation.

Working with Git branches and merging changes reinforced this lesson. Consistent formatting reduces unnecessary conflicts. Clear structure makes code reviews more meaningful. Standards reduce friction in collaboration.

Think of it like writing a book. If every chapter were written in a completely different tone and structure, the result would feel chaotic. Coding standards provide cohesion, allowing many contributors to build something that feels like it has a single voice.

---

## Reflection

Using ESLint wasn’t always comfortable. Like learning an instrument or training at the gym, it required adjustment. The friction between old habits and new expectations forced me to grow.

Eventually, the rules that once felt restrictive became intuitive. I now write cleaner code the first time because I understand the reasoning behind the standards.

Coding standards are not restrictions—they are foundations. They support learning, protect maintainability, and encourage thoughtful engineering.

ICS 314 has shown me that good software is not accidental. It is intentional, structured, and disciplined from the start.

That is why coding standards matter.

---

## Use of AI Tools

I used ChatGPT as a writing assistant to help revise and organize this essay for clarity and structure. The final content was reviewed and edited to reflect my own experience and perspective.
