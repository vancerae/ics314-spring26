---
layout: essay
type: essay
title: "Reflecting on TypeScript, and WODs"
date: 2025-09-12
published: true
labels:
  - TypeScript
  - WODs
image: img/typescript.jpg
permalink: /essays/typescript.html
---

<img src="{{ '/img/typescript.jpg' | relative_url }}" alt="TypeScript" class="img-fluid rounded float-start pe-4" style="width:300px; height:auto;" /> 

TypeScript has been a good transition for me because it adds structure without feeling heavy. Coming from C, Java, and a lot of untyped JavaScript, it feels like JavaScript that actively pushes back when I make predictable mistakes. The type system consistently catches issues I’m prone to—incorrect value types, forgotten null or undefined cases, or returning data that doesn’t match expectations. Union types and narrowing make intent explicit, while strict null checking removes the temptation to hand-wave edge cases. Compared to Java, TypeScript feels more flexible while still providing compile-time confidence; compared to C, it offers safety without the constant overhead of manual memory concerns.

Modern JavaScript features have also had a noticeable impact on how I write code. Using const and let instead of var, relying on arrow functions and their predictable this, and making use of template literals, destructuring, default parameters, and modules has improved readability and reduced boilerplate. Small habits—such as destructuring objects and arrays or using the spread operator—add up to cleaner, more maintainable code. The tooling ecosystem strengthens this further: editor support, IntelliSense, linting, and formatting create a feedback loop that catches problems early and keeps the codebase consistent.

From a software engineering perspective, TypeScript’s advantages are mostly practical. Types act as documentation, refactoring feels safer, runtime surprises are reduced, and shared code becomes easier for others to understand. There are tradeoffs. Types can become overly complex, especially with advanced generics, and the presence of any means to opt out of safety can make it possible to do so under pressure. Even so, these drawbacks feel manageable, and the overall cost-benefit balance is strongly in TypeScript’s favor.

The practice WODs play a different role. Their value is in repetition under constraint. The time limits force me to rely on habits rather than deliberation, which builds fluency: faster setup, fewer syntax errors, and more controlled debugging. The process is stressful, but the stress has a purpose—it pushes me to focus and improves consistency through immediate feedback.
Will this approach work for me? I think so. The structure fits how I learn best: read the task, sketch a brief plan, execute in a clean environment, then review what slowed me down. A few adjustments help reinforce this:

Maintain a short personal checklist (setup, branch, run, test, commit).
Automate routine steps and commit common shortcuts to memory.
Start with one slow, deliberate run to establish form before timing becomes an issue.

In the end, TypeScript reduces uncertainty and clarifies intent; WODs introduce pressure. Together, they aim to make me faster and more confident, even if the stress remains the hardest part of the process.
