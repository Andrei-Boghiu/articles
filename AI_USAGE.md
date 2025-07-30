# AI_USAGE.md

## Overview

AI has become a key part of modern software development, and naturally, I’ve incorporated it into my workflow—especially with **ChatGPT**, which I use from ideation through implementation.

I deliberately chose **ChatGPT** over tools like Grok, Claude, Gemini, or even AI-powered IDEs like Cursor—not because I think it’s the best, but because I believe it’s _not_ the best. That’s intentional. Using a less integrated tool helps me stay more hands-on, write more code myself, and avoid falling into “vibe coding.” It keeps me grounded in the learning process and reinforces my identity as a developer, not just someone stitching together AI-generated snippets.

This file documents how I used ChatGPT, where it helped most, and the boundaries I set for myself to ensure I remain an active learner, not just a passive user.

## 🧠 Idea Generation

At the beginning of every project, I use ChatGPT to brainstorm potential ideas. The goal is to explore multiple directions quickly and find one that feels original, valuable, and well-aligned with my interests or skill goals.

One brainstorming technique I’ve found effective is to first write down my own ideas before consulting language models. Then, I prompt the models as if I had no ideas at all. This approach generates the widest range of suggestions. With both lists in hand, mine and the AI's, I can mix and match the best parts, calibrate trade-offs, and refine the direction with much more creativity.

## 🧱 Tech Stack & Tooling Decisions

I use AI to evaluate and refine my technology stack. Based on the goals and constraints of the project, ChatGPT helps surface relevant tools, libraries, and frameworks, especially those commonly used together in the ecosystem I'm working with. This helps me avoid decision paralysis and ensures I’m not missing standard solutions.

## 🧩 Schema / Structure Design

Most times I begin development by understanding the problem I’m solving and identifying how data needs to move through the system. This leads me to design a data flow-—whether as a schema, a database structure, or another format—-to visualize how related data points interact.

In most cases, a well-structured database schema is enough to anchor the architecture. I use ChatGPT to generate a starting schema tailored to the use case, then refine it based on my own considerations. I often complement this with a few database views to imagine how data might be displayed on the frontend. At this stage, I’ll also sketch out a quick Figma draft to share with non-technical stakeholders for early feedback.

By starting with data flow in mind and aligning both technical and visual elements early on, I can validate the direction of the project before writing a single line of application code—aside from the schema itself. This approach helps surface valuable feedback early, reducing the need for rework later.

## 🗺️ Roadmap & Planning

I often use AI to co-create a roadmap. It helps outline features, phases, and technical considerations I might overlook. These suggestions are never final, but they give me a structured starting point to refine and follow.

## 🗂️ Project Structure & Naming

I sometimes overthink file structure and naming conventions, especially when I am using unopinionated ecosystems. ChatGPT helps by providing example project trees or patterns that are practical and maintainable. Once I find a layout I like, I stick to it. I may miss a detail, but the structure is still clear and scalable.

## ✍️ Manual Review & Adaptation

I never copy and paste blindly, I did it before and it backfired. Every AI-generated code is manually reviewed and adjusted to fit the project. If something doesn’t make sense to me, I don’t use it. This ensures I maintain full understanding and control over the codebase.

## 🧪 Spot Checks & Code Review

As the project progresses, I gradually reduce AI involvement. I occasionally validate code snippets, logic, or patterns with ChatGPT—especially helpful when not using strongly typed systems where small errors can go unnoticed. These quick sanity checks save time and reduce bugs.

## 📌 My Personal Rules for Using AI

To keep myself sharp and avoid over-dependence, I’ve established a few personal constraints:

- ❌ **No in-editor AI tools**
  I only use AI in a separate browser tab. This breaks automatic flow and forces me to think before I paste.

- ✅ **Understand everything before using it**
  If ChatGPT gives me something I don’t understand, I don’t use it. Period.

## ⚠️ Bonus: How Vibe Coding Backfired at Me

I was working in a fast-paced environment (yep, it was FAANG) where quick delivery was critical, and I was exploring the **React Flow** library for a project. Instead of taking the time to read the documentation, I jumped straight into prompting ChatGPT for code—asking it to integrate React Flow in a specific way.

Fast forward: I spent **four hours in a coffee shop** vibe coding my way through a broken implementation. The results were mediocre at best, and I never got the outcome I wanted. I felt stuck, frustrated, and defeated.

The next day, I made the decision to go back to basics—**just me and the docs**. I gave myself permission to take as long as needed. Ironically, it took **only ~15 minutes of reading the docs** to figure out the exact solution I had been chasing the entire day before.

That experience taught me a critical lesson: **AI is a tool, not a substitute for deep understanding**. And while it can speed things up, skipping the fundamentals often leads to wasted time and shallow results. That wasn't the only time this happened either—every time I tried to vibe code my way through something I didn’t fully understand, it backfired almost immediately.

## Final Thoughts

ChatGPT accelerates my development process—-especially in the early stages and environments I already understand deeply—-but it never replaces my thinking. I use it as a mentor, not a crutch. Every project I build with AI starts with curiosity but is grounded in intention, review, and accountability. This approach ensures I keep improving as a developer while still taking advantage of modern tools.
