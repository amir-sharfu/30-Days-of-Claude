# 🤖 Day 9 — Writing Clear & Specific Prompts

[<< Day 8](../08_Day_What_Is_A_Prompt/08_day_what_is_a_prompt.md) | [Day 10 >>](../10_Day_Context_And_Instructions/10_day_context_and_instructions.md)

---

## 🎯 What You Will Learn Today

- Why clarity and specificity are the two most important prompt skills
- The six techniques for writing clearer prompts
- How to apply the "5 Ws" framework to any prompt
- Before-and-after examples you can learn from
- How to instantly improve almost any prompt

---

## 🔍 Clarity vs. Specificity

These two ideas work together — but they're different:

| Concept | What It Means | Example |
|---------|--------------|---------|
| **Clarity** | Your prompt is easy to understand. No ambiguity, no guesswork. | Instead of "make it good," say "make it more formal and concise" |
| **Specificity** | Your prompt includes enough detail that Claude knows exactly what you need. | Instead of "write an email," say "write a follow-up email to a client after our product demo" |

A prompt can be specific but unclear. It can be clear but vague. The goal is to be **both**.

> 💡 **Golden rule:** Write your prompt as if you're sending it to a very capable human assistant who knows nothing about your situation. Would they understand exactly what you need?

---

## 🛠️ Six Techniques for Clearer Prompts

### Technique 1: 🎯 Name the Task Explicitly

Don't hint — state what you want Claude to do.

| ❌ Vague | ✅ Clear |
|---------|---------|
| "My presentation" | "Create an outline for a 10-minute presentation" |
| "This isn't working" | "Explain why this code returns an error and fix it" |
| "Something about coffee" | "Write a 200-word product description for a new cold brew coffee" |

---

### Technique 2: 👥 Define Your Audience

Claude will change its tone, vocabulary, and depth depending on who the output is for.

```
❌ Explain machine learning.

✅ Explain machine learning to someone who has no technical background 
   and has never studied computer science.

✅ Explain machine learning to a senior software engineer who is new 
   to AI and wants a technical overview.
```

Same topic. Completely different appropriate responses.

---

### Technique 3: 📏 Set the Scope

Tell Claude how long, how deep, and how wide.

```
❌ Tell me about the French Revolution.

✅ Give me a 3-paragraph summary of the key causes of the French 
   Revolution. Focus on economic factors, not military events.
```

Without scope, Claude may go too broad, too deep, or miss what you needed.

---

### Technique 4: 📐 Specify the Format

Tell Claude how you want the output structured.

| Format Type | Example Instruction |
|-------------|-------------------|
| Bullet points | "List as bullet points" |
| Numbered list | "Number the steps" |
| Table | "Present this as a comparison table" |
| Paragraphs | "Write in 3 short paragraphs" |
| Code | "Provide the Python code with comments" |
| JSON | "Return the result as valid JSON" |
| Q&A | "Format this as a FAQ with questions and answers" |

---

### Technique 5: 🚫 State What You Don't Want

Negative instructions help Claude avoid common pitfalls.

```
Write a cover letter for this job application. 
Do NOT use generic phrases like "I am a team player" or "I am passionate about." 
Do NOT exceed 300 words. 
Do NOT mention salary expectations.
```

Negative constraints are often more powerful than positive ones.

---

### Technique 6: ✅ Give an Example of What Good Looks Like

Showing Claude an example is often more effective than describing it.

```
Rewrite the following sentence to match this style:

Example style: "Innovation isn't about having all the answers — it's 
about asking better questions."

Sentence to rewrite: "We should try to think more creatively at work."
```

You'll go deep on this technique on Day 13 (Few-Shot Prompting).

---

## 🗺️ The 5 Ws Framework

Before writing any prompt, ask yourself these five questions:

| W | Question | Why It Matters |
|---|----------|---------------|
| **Who** | Who is this for? Who is the audience? | Sets the tone and vocabulary level |
| **What** | What exactly do I want Claude to create/do? | Defines the task |
| **When** | Is there a time context? Deadline? Historical period? | Adds relevance and scope |
| **Where** | Is there a location, platform, or context? | Shapes the content |
| **Why** | What is the purpose? What will this be used for? | Helps Claude make better decisions |

**Example — applying the 5 Ws:**

You need to write a social media post about a product launch.

| W | Your Answer |
|---|------------|
| Who | Young professionals aged 25–35 who use Instagram |
| What | A launch announcement for a new project management app |
| When | Launching next Monday |
| Where | Instagram caption (under 2200 characters, tone should be casual and energetic) |
| Why | To drive downloads and generate excitement |

**Prompt you'd write:**
```
Write an Instagram caption announcing the launch of a new project management 
app called "FlowDesk" next Monday. The audience is young professionals aged 
25–35. The tone should be casual, energetic, and exciting — not corporate. 
Include a call to action and 5 relevant hashtags. Keep it under 150 words.
```

---

## 📊 Before & After: Real Examples

Study these transformations. Each shows a common weak prompt improved using today's techniques.

---

**Before:**
```
Write an email.
```
**After:**
```
Write a professional email from me (a project manager) to a client (a small 
business owner) to reschedule our meeting from Thursday to the following 
Monday. Keep the tone apologetic but confident. Do not exceed 100 words.
```

---

**Before:**
```
Explain artificial intelligence.
```
**After:**
```
Explain artificial intelligence in simple terms for a 65-year-old retired 
teacher who is curious but has no tech background. Use a real-world analogy 
and keep it under 200 words.
```

---

**Before:**
```
Help me with my resume.
```
**After:**
```
Review this resume summary section and rewrite it to be more impactful for 
a senior marketing manager role in the tech industry. Focus on quantifiable 
achievements and leadership. Keep it under 5 sentences.

[paste resume summary here]
```

---

**Before:**
```
Give me ideas.
```
**After:**
```
Give me 10 creative but realistic fundraising ideas for a local animal 
shelter with a small team and no budget for paid advertising. Organize 
them by effort required: low, medium, high.
```

---

## 💡 The Clarity Checklist

Before you send any important prompt, run through this quick check:

- [ ] Is the **task** clearly named?
- [ ] Have I defined the **audience** for the output?
- [ ] Have I set the **scope** (length, depth, topic boundaries)?
- [ ] Have I specified the **format**?
- [ ] Have I included relevant **context** Claude needs?
- [ ] Have I stated anything I **don't want**?

If you can check all six boxes, your prompt is in great shape.

---

## 📋 Summary

🌕 Day 9 complete! Here's what you learned:

- **Clarity** = no ambiguity. **Specificity** = enough detail. You need both.
- Six techniques: Name the task, define the audience, set the scope, specify the format, state what you don't want, give an example
- The **5 Ws** (Who, What, When, Where, Why) help you build complete prompts
- A weak prompt transformed into a strong one produces dramatically better results
- Use the **Clarity Checklist** before sending important prompts

---

## 🏋️ Exercises

### 🟢 Level 1 — Beginner

1. Take these 3 vague prompts and rewrite each using at least 3 of the 6 techniques: (a) "Write something funny", (b) "Help me with my presentation", (c) "Explain the news to me".
2. Apply the 5 Ws framework to a task you genuinely need help with right now. Write the resulting prompt and send it to Claude.
3. Use the Clarity Checklist on a prompt you wrote last week. How many boxes can you check? Rewrite it to check all six.

### 🟡 Level 2 — Intermediate

4. Find a prompt you've used before that gave a disappointing result. Apply all six techniques and send the improved version. What changed?
5. Write two prompts for the same task — one for a non-expert audience and one for an expert. Send both to Claude and compare how the responses differ in tone, vocabulary, and depth.
6. Write a prompt with deliberate negative constraints (what you don't want). How much does this change Claude's output compared to a version without those constraints?

### 🔴 Level 3 — Challenge

7. Design what you consider to be the "perfect prompt" for a professional task you care about. Apply every technique and all 5 Ws. Document your reasoning for each choice.
8. Collect 5 example prompts from colleagues, friends, or online communities. Rate each one for clarity and specificity (1–5). Rewrite the weakest one.
9. Create a "prompt template" for a task you do regularly (e.g., weekly status report, responding to customer complaints, writing meeting agendas). Include placeholders for the variable parts.

---

🧡🧡🧡 HAPPY LEARNING 🧡🧡🧡

[<< Day 8](../08_Day_What_Is_A_Prompt/08_day_what_is_a_prompt.md) | [Day 10 >>](../10_Day_Context_And_Instructions/10_day_context_and_instructions.md)
