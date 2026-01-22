---
layout: essay
type: essay
title: "Reflecting on TypeScript, and WODs"
date: 2025-09-12
published: true
labels:
  - TypeScript
  - WODs
image: /img/typescript.jpg
permalink: /essays/typescript.html
---

<img src="{{ '/img/typescript.jpg' | relative_url }}" alt="TypeScript" class="img-fluid rounded float-start pe-4" style="width:300px; height:auto;" /> 

I like it. Coming from C/Java (and lots of plain JS), TypeScript feels like JavaScript with guardrails. The type system catches the exact types of bugs I tend to make—mixing strings and numbers, forgetting to handle undefined/null, or returning the wrong shape of an object. Features like union types, type narrowing, and interfaces make my intent clear, and strictNullChecks force me to be honest about edge cases. Compared to Java, TS is less formal with similar compile-time confidence; compared to C, I get safety without manual memory management.

In terms of ES6, I gained practical benefits from using const/let instead of var, arrow functions (and their lexical this), template literals, destructuring, default parameters, and modules. Simple habits—such as using object and array destructuring and the spread operator—made my code shorter and clearer. Tooling is also a significant advantage, as IntelliSense, refactoring, and ESLint/Prettier integrate smoothly.

From a software engineering point of view, TypeScript is primarily positive: it makes refactoring easier, provides clearer APIs as types, reduces runtime surprises, and helps teammates onboard faster. Drawbacks include types becoming "too clever" (complex generics/conditional types) and the any escape hatch potentially undermining guarantees if misused. Overall, the benefits outweigh the drawbacks.

The practice WODs are valuable. The time limits and repetition help develop fluency, just like drills do in real athletics—terminal/Git muscle memory, faster setup, fewer typos, calmer debugging. It’s a bit stressful, but the stress is constructive: it keeps me motivated. I enjoy the quick feedback cycle.

Will it work for me? Yes. The structure suits me: a warm-up (read the task, jot down a brief plan), a clean environment, run the reps, review what took time, and repeat. A couple of things that could help: 

- Keep a tiny personal checklist (setup, branch, run, test, commit). 

- Automate boring steps and memorize a few key shortcuts. 

- Do one slow "form" rep before starting the time trial. 

Net: TypeScript provides me with safer, clearer code; WODs give me anxiety. Together, they are trying to make me faster and more confident, but the stress is not helping.
