---
title: Code for Human and Machine
tags: [Accessibility, AI, Human-Machine Interaction, Design]
---

It is increasingly becoming apparent that what is required for designing websites with accessibility in mind is equally useful for improving interactions between such browsers as Comet and Dia and the Internet.

For example, [a recently published article by Google](https://web.dev/articles/ai-agent-site-ux), devoted to optimizing websites for AI agents, mentions that it becomes easier for AI agents to interact with a website that is semantically and structurally organized, utilizes semantic HTML and has accessible interaction models.

Semantic HTML is a fundamental element of web accessibility design since it provides structure for content in order to enhance website readability for users as well as artificial intelligence software.

## The accessibility tree

The accessibility tree is essential to the process of making a website accessible to both humans and computers since it is the structured version of the page that assistive technology and AI agents rely upon.

Proper organization of the accessibility tree depends on having well-labeled landmarks, headings, forms, and controls. The semantics provided by semantic HTML are sufficient for most purposes, but ARIA is used when necessary.

## The problem: Most websites are still not accessible

While there is a high level of recognition of the importance of accessibility on the part of designers and developers, relatively few websites fully implement accessibility best practices. As per the [WebAIM Million report of this year](https://webaim.org/projects/million/), 95.9% of home pages contained at least one WCAG 2.1 failure in 2025, which was a noticeable increase from 94.8% recorded in 2024, reversing a six-year trend of gradual improvement (albeit a very small improvement). However, even these numbers are underestimated due to the use of automated tests, and the true picture might be even worse. This suggests that many websites still lack basic accessibility features, which may also make them harder for AI agents to navigate and interpret.

Optimizing websites for AI agents is closely aligned with optimizing websites for web accessibility. By investing time in semantic structure, labeling, and accessible interaction patterns, designers and developers can benefit both assistive technologies and AI systems, creating a more usable and inclusive web for all.