# 🤖 Day 13 — Few-Shot Prompting

[<< Day 12](../12_Day_Chain_Of_Thought/12_day_chain_of_thought.md) | [Day 14 >>](../14_Day_Week2_Review/14_day_week2_review.md)

---

## 🎯 What You Will Learn Today

- What few-shot prompting is and why it works
- The difference between zero-shot, one-shot, and few-shot prompting
- How to structure examples effectively
- When few-shot prompting is the right technique to use
- Common mistakes and how to build better example sets

---

## 🎯 What is Few-Shot Prompting?

**Few-shot prompting** means teaching Claude how you want something done by showing it examples — rather than (or in addition to) describing it in words.

The name comes from machine learning: "shots" = examples provided.

| Type | Examples Provided | When to Use |
|------|-----------------|-------------|
| **Zero-shot** | 0 — no examples | Simple tasks, Claude already knows the pattern |
| **One-shot** | 1 example | You want a specific style or format |
| **Few-shot** | 2–5 examples | Pattern is complex, unusual, or very specific |

> 💡 **Core insight:** Sometimes it's easier to show Claude what you want than to describe it. If you're struggling to explain a pattern in words, show an example instead.

---

## 📖 Zero-Shot: No Examples

Zero-shot prompting is what you've been doing by default — asking Claude without giving any examples.

```
Classify the sentiment of this review as Positive, Negative, or Neutral:

"The product arrived quickly and works exactly as described."
```

For common, well-understood tasks, zero-shot works well. Claude already knows what "sentiment classification" means.

But for unusual patterns, your own specific style, or non-standard formats, zero-shot often produces generic results.

---

## 📌 One-Shot: One Example

You show Claude one example of what you want, then give it a new case to apply it to.

```
Classify the sentiment of customer reviews. Here is an example:

Review: "Shipping took 3 weeks and the box was damaged."
Sentiment: Negative

Now classify this one:
Review: "Decent product for the price, nothing special."
Sentiment:
```

One example is often enough to establish the pattern — especially for format or style.

---

## 🎯 Few-Shot: Multiple Examples

You provide several examples to make the pattern unmistakable.

```
Convert these informal messages to professional email language.

Informal: "Hey, can we push the meeting? I'm slammed today."
Professional: "Hi [Name], I hope you're doing well. Would it be possible 
to reschedule our meeting? I have a heavy workload today and want to 
ensure I can give it my full attention."

Informal: "FYI the report's late, my bad"
Professional: "I wanted to inform you that the report will be delayed. 
I apologize for any inconvenience this may cause and will send it 
through as soon as possible."

Informal: "Loved your idea in the meeting btw"
Professional: "I wanted to reach out to let you know that I found your 
contribution during today's meeting particularly insightful. Thank you 
for sharing it."

Now convert this one:
Informal: "Can you send me that file asap? I need it for the presentation"
Professional:
```

Claude now has a very clear sense of your expected tone, structure, and level of formality — far better than if you had described it in words.

---

## 🏗️ How to Structure Good Examples

A few-shot prompt is only as good as the examples you choose. Here's how to build them well:

### ✅ Good Examples Are:

- **Representative** — they show the full range of what you're dealing with
- **Consistent** — they all follow the same pattern you want Claude to learn
- **Relevant** — they're similar to the actual task Claude will perform
- **Varied** — they show different cases, not just the same case rephrased

### ❌ Avoid:

- Examples that contradict each other
- Too few examples for a complex or nuanced pattern
- Examples that all look identical (Claude won't learn the range)
- Examples that don't represent the real inputs Claude will see

---

## 🌍 Real-World Use Cases

### 📊 Data Formatting

```
Convert product descriptions to a standard JSON format.

Input: "Classic leather wallet, brown, 3 card slots, coin pocket"
Output: {"name": "Classic Leather Wallet", "color": "brown", 
         "features": ["3 card slots", "coin pocket"]}

Input: "Running shoes, size 42, navy blue, waterproof"
Output: {"name": "Running Shoes", "size": 42, "color": "navy blue",
         "features": ["waterproof"]}

Now convert this:
Input: "Ceramic coffee mug, 350ml, dishwasher safe, white with floral pattern"
Output:
```

---

### 🎨 Matching a Writing Style

```
I write social media posts in a specific style. Learn it from these examples:

Post 1: "Your inbox is full. Your attention is precious. Choose deliberately."
Post 2: "Productivity isn't about doing more. It's about doing fewer things, better."
Post 3: "Every expert was once a beginner who didn't quit."

Now write a post in the same style about the value of rest and recovery.
```

---

### 🏷️ Labelling & Classification

```
Label each customer message with one of these categories:
BILLING, TECHNICAL, RETURNS, GENERAL

Message: "My invoice shows double the amount I should have been charged."
Category: BILLING

Message: "The app crashes every time I try to upload a photo."
Category: TECHNICAL

Message: "I'd like to send back the item I ordered last week."
Category: RETURNS

Message: "What are your business hours?"
Category: GENERAL

Now label this:
Message: "I received the wrong size — can I exchange it?"
Category:
```

---

### ✍️ Transforming Tone

```
Rewrite academic sentences in conversational English.

Academic: "The empirical data suggests a statistically significant 
correlation between sleep deprivation and cognitive performance degradation."
Conversational: "The research clearly shows that not getting enough 
sleep makes it harder to think and perform well."

Academic: "Sustained aerobic exercise has been demonstrated to confer 
significant benefits to cardiovascular health outcomes."
Conversational: "Regular cardio exercise is genuinely good for your heart."

Now rewrite this:
Academic: "Preliminary findings indicate that dietary interventions may 
play a role in mitigating the onset of metabolic syndrome."
Conversational:
```

---

## ⚠️ Common Mistakes

| Mistake | Problem | Fix |
|---------|---------|-----|
| **Only 1 vague example** | Not enough for Claude to learn the pattern | Use 3+ examples that show the range |
| **Inconsistent examples** | Claude learns a mixed pattern and produces inconsistent output | All examples must follow the same rule |
| **Examples too similar** | Claude only learns one case, not the general pattern | Include varied examples |
| **Copying examples into final output** | Claude may parrot your examples | Make new inputs clearly distinct from examples |
| **No separator between examples** | Claude can't distinguish where one ends and the next begins | Use blank lines and consistent labels |

---

## 🔄 Combining Few-Shot with Other Techniques

Few-shot works especially well when combined with:

**Few-Shot + Role Prompting:**
```
Act as a professional copywriter. Learn my brand voice from these examples:

[Example 1]
[Example 2]
[Example 3]

Now write a product description for [new product].
```

**Few-Shot + Format Constraints:**
```
Write tweet-length (under 280 characters) summaries of articles 
in this style:

[Article 1] → [Summary 1]
[Article 2] → [Summary 2]

Now summarize this: [Article 3]
```

---

## 🗺️ Choosing the Right Technique

Now that you know four techniques, here's a quick guide for choosing:

| Situation | Best Technique |
|-----------|---------------|
| Standard task, no special format | Zero-shot (just ask) |
| Specific output style or format | Few-shot |
| Complex reasoning or multi-step problem | Chain of Thought |
| You need a specific expertise or perspective | Role Prompting |
| Long conversation with a specific goal | Context + Instructions |

Most powerful prompts combine two or more techniques together.

---

## 📋 Summary

🌕 Day 13 complete! Here's what you learned:

- **Few-shot prompting** teaches Claude by example rather than (or alongside) description
- The three levels: **zero-shot** (no examples), **one-shot** (one example), **few-shot** (2–5 examples)
- Good examples are representative, consistent, relevant, and varied
- Few-shot is most useful when the pattern is complex, unusual, or hard to describe in words
- Combine few-shot with role prompting, CoT, and context for maximum power
- Use the technique-selection guide to choose the right approach for each situation

---

## 🏋️ Exercises

### 🟢 Level 1 — Beginner

1. Write a few-shot prompt with 3 examples to classify 5 customer reviews as Positive, Negative, or Neutral. Run it and check Claude's accuracy.
2. Show Claude 3 examples of your own writing style, then ask it to write a new paragraph in that style. How closely does it match?
3. Compare zero-shot vs. few-shot on the same task: (a) ask Claude to rewrite a sentence formally with no examples; (b) provide 2 examples first. Which output is closer to what you wanted?

### 🟡 Level 2 — Intermediate

4. Create a few-shot prompt for a real task you do repeatedly at work or school. Design 3–4 varied examples, then test it on 3 new inputs. Is it consistent?
5. Intentionally create a few-shot prompt with 2 contradictory examples. What does Claude do? What does this teach you about consistency?
6. Design a few-shot prompt that converts data from one format to another (e.g., a list to a table, a paragraph to bullet points). Test it on at least 5 varied inputs.

### 🔴 Level 3 — Challenge

7. Build a "style guide prompt" for a piece of content you create regularly (blog posts, emails, social media). Use 4–5 examples, then test it on a new topic. How well does Claude capture your voice?
8. Design a few-shot prompt for a classification task with 5+ categories. How many examples do you need per category to get consistent results?
9. Research: What is "in-context learning" in large language models? How does few-shot prompting relate to how LLMs are actually trained? What are the limits of in-context learning?

---

🧡🧡🧡 HAPPY LEARNING 🧡🧡🧡

[<< Day 12](../12_Day_Chain_Of_Thought/12_day_chain_of_thought.md) | [Day 14 >>](../14_Day_Week2_Review/14_day_week2_review.md)
