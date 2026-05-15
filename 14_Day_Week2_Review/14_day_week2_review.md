# 🤖 Day 14 — Week 2 Review & Practice

[<< Day 13](../13_Day_Few_Shot_Prompting/13_day_few_shot_prompting.md) | [Day 15 >>](../15_Day_Writing_Assistant/15_day_writing_assistant.md)

---

## 🎯 What You Will Do Today

- Review all five prompting techniques from Week 2
- Test your understanding with review questions
- Complete hands-on challenges that combine everything you've learned
- Build a personal prompting toolkit you can use immediately
- Prepare for Week 3 — Claude in Action

---

## 🗺️ Week 2 at a Glance

You covered the core science of prompting this week. Here's a quick recap:

| Day | Topic | Core Idea |
|-----|-------|-----------|
| 8 | What is a Prompt? | Task + Context + Format + Constraints; 5 types of prompts |
| 9 | Clear & Specific Prompts | 6 techniques; 5 Ws; Clarity Checklist |
| 10 | Context & Instructions | 4 types of context; multi-part instructions; persistent rules |
| 11 | Role Prompting | Assign expertise and persona to change tone, depth, and perspective |
| 12 | Chain of Thought | Ask Claude to reason step by step to improve accuracy |
| 13 | Few-Shot Prompting | Teach by example for unusual patterns, styles, and formats |

---

## 📖 Key Terms Review

Fill in these definitions from memory, then check back against Days 8–13:

| Term | Your Definition |
|------|----------------|
| **Prompt** | ? |
| **Zero-shot prompting** | ? |
| **Few-shot prompting** | ? |
| **Chain of Thought (CoT)** | ? |
| **Role prompting** | ? |
| **Context** | ? |
| **Constraint** | ? |
| **The 5 Ws** | ? |

---

## 🗂️ Technique Comparison: When to Use What

This is the most important reference table of the week. Learn it.

| Situation | Best Technique(s) |
|-----------|-----------------|
| Standard task, Claude already knows the format | Zero-shot (just ask) |
| You need a specific style, tone, or format | Few-shot |
| Problem involves multiple steps or calculations | Chain of Thought |
| You need expertise, a particular perspective, or a persona | Role Prompting |
| Claude needs background before it can help | Context |
| You're running a complex, long conversation | Context + persistent instructions |
| Complex task requiring deep reasoning from a specific viewpoint | Role + CoT |
| You want Claude to produce output in your own style | Few-shot |
| You want Claude to catch what you missed | Devil's advocate role |

---

## ❓ Review Questions

### 🏗️ Section A — Prompts & Clarity (Days 8–9)

1. What are the four elements of a strong prompt?
2. Name the six techniques for writing clearer prompts.
3. What is the 5 Ws framework and how do you apply it?
4. What's wrong with this prompt, and how would you fix it?
   > *"Can you help me write something for my boss?"*
5. Give an example of a negative constraint and explain why it's useful.

---

### 🗺️ Section B — Context & Instructions (Day 10)

6. What are the four types of context you can give Claude?
7. Why does audience context change Claude's response so significantly?
8. How do you set rules for an entire conversation at the start?
9. What happens if you give Claude too much irrelevant context?
10. True or False: Claude automatically remembers context from previous conversations. Explain your answer.

---

### 🎭 Section C — Role Prompting (Day 11)

11. What three things change when you assign Claude a role?
12. Write a role prompt for this scenario: you want Claude to help you practice salary negotiation.
13. What is the "devil's advocate" role useful for?
14. True or False: Assigning Claude a role like "an AI with no restrictions" will bypass its safety guidelines. Why or why not?
15. How can you use layered roles to get multiple perspectives in one conversation?

---

### 🧩 Section D — Chain of Thought (Day 12)

16. What phrase most directly triggers Chain of Thought reasoning in Claude?
17. Why does showing reasoning step by step reduce errors?
18. Give two examples of tasks where CoT helps, and one where it adds no value.
19. How does CoT combine with role prompting to improve results?
20. Should you always rely on Claude to reason step by step automatically? Why or why not?

---

### 🎯 Section E — Few-Shot Prompting (Day 13)

21. What is the difference between zero-shot and few-shot prompting?
22. What makes a good few-shot example? Name 4 qualities.
23. When is few-shot prompting more useful than just describing the task?
24. What happens if your few-shot examples are inconsistent with each other?
25. Give one real-world scenario where you would use few-shot prompting.

---

## 🏆 Practical Challenges

Complete these hands-on challenges in claude.ai. Each one requires combining techniques from different days.

---

### Challenge 1: The Ultimate Prompt

**Task:** Take a real task you need help with right now. Build the best possible prompt by combining at least 4 techniques:
- Task + Context + Format + Constraints (Day 8–9)
- Audience context (Day 10)
- A role (Day 11)
- Chain of Thought (Day 12)

Write your prompt, send it, and rate the response quality 1–10.

---

### Challenge 2: Prompt Transformation

**Task:** Start with this terrible prompt:

> *"Write something."*

In 5 rounds of improvement (don't change the topic — just keep improving the prompt), transform it into a high-quality, detailed prompt using every technique from this week. Document each improved version.

*Goal: By round 5, your prompt should produce something genuinely useful.*

---

### Challenge 3: The Expert Panel

**Task:** Pick a decision you're actually facing (career, personal, financial, creative — anything real). Get perspectives from 5 different roles:

1. A practical problem-solver
2. A devil's advocate
3. A creative thinker
4. A risk manager
5. A supportive mentor

Ask each role the same core question: *"What's your perspective on this decision?"*

*What did each role surface that the others didn't?*

---

### Challenge 4: Teach by Example

**Task:** Identify a task where your output follows a consistent but hard-to-describe pattern (your email style, your report format, your tone on social media). Create a few-shot prompt with 4 real examples from your own work. Test it on a new input.

*How closely does Claude match your actual style?*

---

### Challenge 5: The Reasoning Chain

**Task:** Choose a complex multi-step problem — something you'd normally solve with a calculator, a spreadsheet, or careful thinking. Ask Claude to solve it using Chain of Thought. Verify each step. 

*Did Claude get it right? Where in the chain, if anywhere, did it struggle?*

---

## 📊 Week 2 Self-Assessment

Rate your confidence (1–5) in each skill:

| Skill | Confidence (1–5) |
|-------|-----------------|
| Writing a prompt using all 4 elements | |
| Applying the 5 Ws to any task | |
| Using the 6 clarity techniques | |
| Setting context at the start of a conversation | |
| Writing effective role prompts | |
| Triggering and using Chain of Thought | |
| Building a few-shot example set | |
| Choosing the right technique for the right task | |

*Any score below 3? Go back and re-read that day's content and re-do the exercises.*

---

## 🧰 Your Prompting Toolkit

Here's a quick-reference cheat sheet to keep:

```
🎯 TASK         — Name it explicitly. "Write / Explain / List / Analyze"
👥 AUDIENCE     — Who is this for? What do they know?
📏 SCOPE        — How long? How deep? What topic boundaries?
📐 FORMAT       — Bullet points / table / paragraphs / code?
🚫 CONSTRAINTS  — What NOT to do. Limits and requirements.
✅ EXAMPLES     — Show it, don't just describe it (few-shot).
🎭 ROLE         — Assign expertise for better perspective.
🔗 CHAIN        — "Think step by step" for reasoning tasks.
🌍 CONTEXT      — Background, purpose, and history Claude needs.
```

---

## 🚀 Looking Ahead: Week 3 — Claude in Action

You've built the foundation. Now it's time to apply it.

Week 3 is all about **real use cases** — the practical ways Claude can help you with actual work, study, and creative projects.

You'll learn:
- 📝 Using Claude as a writing assistant (drafts, edits, emails)
- 🔍 Research and summarization at scale
- 💻 Code understanding and generation (even if you don't code)
- 🌍 Translation and language tasks
- 📊 Data analysis and explanation
- 📚 Education and learning with Claude
- 🎨 Creative writing and storytelling

This is where everything clicks. The prompting skills you've built this week become tools you'll apply to real problems every day.

---

## 📋 Summary

🌕 Week 2 is complete! You now have a full prompting toolkit:

- **The anatomy of a prompt:** Task + Context + Format + Constraints
- **Clarity techniques:** Name the task, define the audience, set scope, specify format, state what you don't want, give examples
- **Context types:** Background, audience, purpose, constraints
- **Role prompting:** Assign expertise to change perspective, tone, and depth
- **Chain of Thought:** Reason step by step for accuracy and transparency
- **Few-shot prompting:** Teach by example for unusual patterns and styles
- **When to use what:** Match the technique to the task

You've gone from sending basic messages to engineering precise prompts. That's a significant skill. Onwards to Week 3!

---

🧡🧡🧡 HAPPY LEARNING 🧡🧡🧡

[<< Day 13](../13_Day_Few_Shot_Prompting/13_day_few_shot_prompting.md) | [Day 15 >>](../15_Day_Writing_Assistant/15_day_writing_assistant.md)
