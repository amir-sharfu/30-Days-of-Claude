# 📚 30 Days of Claude — Prompt Library

A complete collection of every example prompt, template, and "Try this" exercise from the course. Use this as your personal reference — bookmark it, copy from it, and adapt it to your own needs.

> 💡 **How to use this file:** Find the skill or use case you need, copy the prompt, replace any `[PLACEHOLDERS]` with your real details, and paste into claude.ai.

---

## 🏗️ Phase 1 — Foundations (Days 1–7)

### Day 2 — Setting Up
**First conversation starter:**
```
Hello! I'm new here. Can you introduce yourself?
```

---

### Day 3 — Your First Conversation

**Start a conversation:**
```
Hello! I've just started learning how to use Claude.
Can you tell me a bit about yourself and what you can help me with?
```

**Simple factual question:**
```
What are three interesting facts about the ocean that most people don't know?
```

**Task help:**
```
I need to write a short email to my colleague thanking them for helping
me on a project. Can you write one for me? Keep it professional but warm.
```

**Follow-up to refine output:**
```
Can you make it a bit more formal and add a line about looking forward to
working together again?
```

---

### Day 4 — Claude's Capabilities

**Writing — improve a sentence:**
```
Rewrite this sentence to sound more professional:
"I want the raise because I've been working really hard and I think I deserve it."
```

**Explanation — adjust for audience:**
```
Explain climate change in simple terms that a 12-year-old could understand.
Use an analogy.
```

**Coding — write and explain:**
```
Write a simple Python program that asks for my name and says "Hello, [name]!"
Then explain each line of the code.
```

**Analysis — business:**
```
I'm thinking of starting a small online store selling handmade jewelry.
What are the main risks and opportunities I should consider?
```

**Creative:**
```
Write a short poem about rain from the perspective of a cat who hates getting wet.
Keep it funny and under 8 lines.
```

**Education:**
```
I want to learn about the stock market. I'm a complete beginner.
Can you explain it step by step, starting from the very basics?
```

**Translation:**
```
Translate this to French, Spanish, and German:
"Thank you for your help today. I really appreciate it."
```

**Maths with steps:**
```
If I invest £1,000 at 7% annual interest compounded yearly,
how much will I have after 10 years? Show the calculation step by step.
```

---

## ✍️ Phase 2 — The Art of Prompting (Days 8–14)

### Day 8 — What is a Prompt?

**Vague (avoid this):**
```
Tell me about dogs.
```

**Vague (avoid this):**
```
Write about healthy eating.
```

---

### Day 9 — Writing Clear & Specific Prompts

**Audience-aware prompt — beginner:**
```
Explain machine learning to someone who has no technical background
and has never studied computer science.
```

**Audience-aware prompt — expert:**
```
Explain machine learning to a senior software engineer who is new
to AI and wants a technical overview.
```

**Scoped prompt:**
```
Give me a 3-paragraph summary of the key causes of the French Revolution.
Focus on economic factors, not military events.
```

---

### Day 10 — Using Context & Instructions

**Context-rich prompt — job interview:**
```
I'm preparing for a job interview at a fintech startup. The role is Senior Product Manager.
The company builds B2B payment processing software. I have 4 years of product experience
but this would be my first fintech role.

With this in mind, help me answer the question: "Why do you want to work in fintech?"
```

**Audience-targeted explanation:**
```
Explain how a mortgage works. The audience is a group of recent university graduates
at a financial literacy workshop — smart, but with no experience of property or finance.
```

**No context (avoid this):**
```
Give me advice about sleep.
```

**Rich context (use this instead):**
```
I'm a 28-year-old software engineer who works remotely. I've been struggling to sleep
for 3 months — I lie awake for 1–2 hours every night despite feeling tired. I don't
drink coffee after 2pm and I exercise 3 times a week. I've tried melatonin but it didn't help.

Please give me 5 practical, evidence-based suggestions that I haven't likely already tried.
Focus on behavioral and environmental changes, not supplements.
```

---

### Day 11 — Role Prompting

**Basic role prompt:**
```
Act as a senior software engineer. Review this code and identify
any performance issues or potential bugs.
```

**Expert strategist:**
```
You are an experienced marketing strategist. I'll describe my product,
and you'll give me 5 ideas for reaching my target audience on a small budget.
```

**Socratic teacher:**
```
Pretend you are a Socratic teacher. Don't give me the answers directly —
ask me guiding questions to help me figure out the solution myself.
```

**Harsh critic:**
```
Act as a senior recruiter with 15 years of experience in tech hiring.
Review my resume and give me specific, honest feedback on what's holding
it back. Don't soften the critique — I need to know what to fix.
```

**Patient tutor:**
```
Act as a patient tutor who explains everything from first principles.
I'm learning Python for the first time. Explain what a "for loop" is
using a real-life analogy before you show any code.
```

**Compound interest — Socratic mode:**
```
You are a Socratic teacher. I'm trying to understand how compound
interest works. Don't explain it to me — ask me questions one at a time
to help me figure it out myself.
```

**Creative director:**
```
You are a provocative creative director who challenges conventional thinking.
I'm working on a campaign for a new eco-friendly water bottle.
Give me 5 unconventional campaign angles that no one else would pitch.
```

**Devil's advocate:**
```
Act as a devil's advocate. I'll present a business idea, and your job
is to find every possible flaw, risk, and weakness in it. Don't hold back.
```

**Professional editor:**
```
Act as a professional editor with experience in business writing.
Review the following email and provide specific suggestions to make it
clearer, more concise, and more persuasive.
```

---

### Day 12 — Chain of Thought Prompting

**Without chain of thought (baseline):**
```
If I have 3 boxes with 12 apples each, and I give away 15 apples,
how many do I have left?
```

**With chain of thought:**
```
If I have 3 boxes with 12 apples each, and I give away 15 apples,
how many do I have left? Think through this step by step.
```

**Maths problem:**
```
A train travels at 80km/h for 2.5 hours, then at 60km/h for 1.5 hours.
What is the total distance? Think step by step.
```

**Career decision:**
```
I've been offered two job offers:
- Offer A: £60,000 salary, startup, fully remote, no bonus, high equity, uncertain future
- Offer B: £50,000 salary, established company, hybrid working, 10% annual bonus, good benefits, stable

Think step by step about the key factors I should weigh when making this decision.
Then give me a recommendation.
```

**Argument analysis:**
```
Here is an argument: "Social media is making young people less happy because
screen time reduces face-to-face interaction."

Think step by step: What are the premises? What evidence would we need to evaluate them?
What are the weaknesses in this argument? Then give your overall assessment.
```

**Event planning:**
```
I need to organize a team offsite for 20 people for one day. Budget is £2,000.
Think through the key things to plan for, step by step, then give me a complete checklist.
```

**How something works:**
```
Explain how a car engine works. Break your explanation into clear steps,
starting from fuel entering the engine to the wheels turning.
```

**Compound interest — step by step:**
```
I don't understand compound interest. Walk me through a concrete example step by step,
starting from first principles. Use £1,000 invested at 5% annual interest.
```

---

### Day 13 — Few-Shot Prompting

**Zero-shot (no examples):**
```
Classify the sentiment of this review as Positive, Negative, or Neutral:

"The product arrived quickly and works exactly as described."
```

**One-shot (one example):**
```
Classify the sentiment of customer reviews. Here is an example:

Review: "Shipping took 3 weeks and the box was damaged."
Sentiment: Negative

Now classify this one:
Review: "Decent product for the price, nothing special."
Sentiment:
```

**Few-shot — tone conversion:**
```
Convert these informal messages to professional email language.

Informal: "Hey, can we push the meeting? I'm slammed today."
Professional: "Hi [Name], I hope you're doing well. Would it be possible to reschedule
our meeting? I have a heavy workload today and want to ensure I can give it my full attention."

Informal: "FYI the report's late, my bad"
Professional: "I wanted to inform you that the report will be delayed. I apologize for any
inconvenience this may cause and will send it through as soon as possible."

Informal: "Loved your idea in the meeting btw"
Professional: "I wanted to reach out to let you know that I found your contribution during
today's meeting particularly insightful. Thank you for sharing it."

Now convert this one:
Informal: "Can you send me that file asap? I need it for the presentation"
Professional:
```

---

## 🛠️ Phase 3 — Claude in Action (Days 15–21)

### Day 15 — Writing Assistant

**Get an outline first:**
```
Create a detailed outline for a blog post titled "5 Ways Remote Work
Has Changed Company Culture Forever." The audience is HR managers
at mid-sized companies. Include main sections and 2–3 bullet points per section.
```

**Draft a full document:**
```
Write a first draft of a project proposal for the following:

Project: Installing solar panels on our company's warehouse
Audience: The board of directors (non-technical, focused on ROI)
Length: One page
Sections needed: Executive summary, cost breakdown, projected savings, recommendation
Tone: Professional and persuasive, not overly technical
```

**Beat writer's block:**
```
I'm writing an introduction for an article about the mental health benefits of exercise.
I've been staring at a blank page for 20 minutes. Give me 5 different opening sentences
I could use — ranging from surprising stat to personal anecdote to thought-provoking question.
```

**Rewrite for clarity:**
```
Rewrite the following paragraph to be clearer and more concise. Remove any redundancy
and use simpler words where possible. Keep the same meaning.

[paste your paragraph]
```

**Proofread:**
```
Proofread the following text. Correct any grammar, spelling, and punctuation errors.
Also flag any sentences that are awkward or hard to read, and suggest rewrites.

[paste your text]
```

**Cold outreach email:**
```
Write a concise, professional email requesting a 30-minute meeting with a potential client
I met at a conference last week. I want to discuss how our data analytics software could help
their logistics company reduce costs. Keep it under 150 words.

My name: [your name]
Their name: [their name]
Company: [their company]
```

**Follow-up email:**
```
Write a polite follow-up email to a recruiter who I applied to 2 weeks ago.
I haven't heard back. I want to express continued interest without seeming pushy.
Keep it under 100 words.
```

**Delay notification email:**
```
Write a professional email to a client explaining that our project will be delayed
by 2 weeks due to unexpected technical issues. The tone should be: apologetic but not
groveling, honest about the cause, clear about the new timeline, and focused on solutions.
```

**Polite decline:**
```
Write an email declining a meeting invitation from a vendor. I'm not interested in
their product right now but want to leave the door open for the future.
Keep it brief and professional.
```

---

### Day 16 — Research & Summarization

**Bullet summary:**
```
Summarize the following article in 3 bullet points. Focus on the main argument and key evidence.

[paste article text]
```

**Executive summary:**
```
Write a one-paragraph executive summary of the following report. The audience is senior
management who won't read the full document. Highlight the key findings, recommendations,
and any risks.

[paste report]
```

**Structured extraction:**
```
Read the following research paper and extract:
1. The main research question
2. The methodology used
3. The key findings
4. The limitations the authors acknowledge
5. The implications for practitioners

[paste paper]
```

**Dual-audience summary:**
```
Summarize this scientific study twice:
1. For a general audience with no science background (plain English, no jargon, use an analogy)
2. For a professional audience in the same field (technical, use correct terminology)

[paste study]
```

**Layered explanation:**
```
Explain quantum computing. Give me:
1. A 2-sentence summary for a complete beginner
2. A 1-paragraph overview for someone with a basic science background
3. A more detailed explanation covering the key concepts: qubits, superposition, and entanglement
```

**Comparison table:**
```
Create a comparison table of these three project management methodologies:
Agile, Waterfall, and Kanban.

Columns: definition, best use case, main advantages, main disadvantages, team size it suits.
```

**Balanced argument:**
```
Present the strongest arguments FOR and AGAINST remote work becoming the permanent default
for office jobs. Give each side equal weight. Don't tell me your conclusion — just present
both sides clearly.
```

---

### Day 17 — Code Understanding & Generation

**Explain code in plain English:**
```
Explain what this code does in plain English. Assume I have no programming background.

def calculate_discount(price, discount_percent):
    discount_amount = price * (discount_percent / 100)
    return price - discount_amount
```

**Line-by-line explanation:**
```
Explain this Python script line by line. For each line, tell me what it does and why it's there.

import csv

with open('sales.csv', 'r') as file:
    reader = csv.reader(file)
    total = 0
    for row in reader:
        total += float(row[2])
    print(f"Total sales: £{total:.2f}")
```

**Predict output:**
```
What does this function return? Give me 3 example inputs and what the output would be for each.

def grade(score):
    if score >= 90: return "A"
    elif score >= 80: return "B"
    elif score >= 70: return "C"
    else: return "F"
```

**Write a script:**
```
Write a Python script that:
1. Reads a list of names from a text file called "names.txt" (one name per line)
2. Sorts them alphabetically
3. Writes the sorted list to a new file called "sorted_names.txt"
4. Prints how many names were processed

Add comments explaining each step.
```

**Excel formula:**
```
I have an Excel spreadsheet. Column A has product names, Column B has sales figures,
Column C has target figures.

Write a formula for Column D that shows "Above target" if B is greater than C,
"On target" if they're equal, and "Below target" if B is less than C.
```

**SQL query:**
```
I have a database table called "orders" with these columns:
- order_id, customer_name, product, quantity, price, order_date

Write a SQL query that finds the top 5 customers by total spending in the last 30 days.
```

**Debug an error:**
```
This Python code is giving me an error. Here's the code and the error message.
What's wrong and how do I fix it?

Code:
numbers = [1, 2, 3, 4, 5]
print(numbers[10])

Error:
IndexError: list index out of range
```

---

### Day 18 — Translation & Language Tasks

**Direct translation:**
```
Translate the following to Spanish:

"Good morning. I have a meeting at 10am and would like to confirm the location.
Please let me know if anything has changed. Thank you."
```

**Formal register — Japanese:**
```
Translate this business email to formal Japanese. The recipient is a senior manager
at a Japanese company I'm partnering with.

"Dear Mr Tanaka, I hope this message finds you well. I am writing to follow up
on our conversation from last Tuesday regarding the supply agreement..."
```

**Multiple registers:**
```
Translate "I wanted to touch base and see how things are going" into French in three ways:
1. Formal (for a business partner)
2. Informal (for a friend)
3. Professional but warm (for a colleague you know well)
```

**Cultural adaptation:**
```
I've written this marketing tagline for a UK audience: "Get more bang for your buck."

Adapt this for:
1. A French audience (translate AND culturally adapt — the idiom won't translate directly)
2. A Japanese audience (consider cultural values around value and quality)
3. A Brazilian Portuguese audience (keep it energetic)
```

**Unknown language:**
```
What language is this text written in? Translate it to English and explain any
cultural references I might not understand.

[paste unknown text]
```

**Language learning:**
```
I'm learning Italian at a beginner level. Teach me 10 essential phrases for ordering
food at a restaurant. For each phrase:
- The Italian phrase
- The pronunciation (written phonetically)
- The literal translation
- When to use it
```

---

### Day 19 — Data Analysis & Explanation

**Trend analysis:**
```
Here is monthly sales data for our product line:

January: £12,400 | February: £11,200 | March: £14,800 | April: £13,600
May: £16,200 | June: £18,900 | July: £15,400 | August: £14,100
September: £17,300 | October: £19,800 | November: £22,400 | December: £28,600

Analyse this data and tell me:
1. The overall trend
2. Any seasonal patterns
3. The best and worst months
4. The average monthly revenue
5. Any anomalies worth investigating
```

**A/B test comparison:**
```
Here are conversion rates for our two landing pages last month:

Page A: 2.3%, 2.1%, 2.5%, 2.2%, 2.4%, 2.3%, 2.6%, 2.2%, 2.4%, 2.3%
Page B: 3.1%, 2.8%, 3.4%, 2.9%, 3.2%, 3.0%, 3.3%, 2.8%, 3.1%, 3.2%

Which page performs better? Is the difference consistent or variable?
What would you recommend based on this data?
```

**Investment comparison:**
```
I'm comparing two investment options:

Option A: Invest £10,000 at 6% annual interest, compounded monthly, for 10 years.
Option B: Invest £8,000 at 8% annual interest, compounded quarterly, for 10 years.

Which option gives the higher return? Show the calculation step by step.
```

---

### Day 20 — Education & Learning

**Context-aware explanation:**
```
Explain machine learning. I'm a software engineer with 5 years of experience but
I've never studied AI. Give me a technical overview that builds on programming concepts I already know.
```

**Bridge from known concept:**
```
I understand how a regular database works. Explain how a vector database is different,
using the relational database as a reference point. What problems does it solve that a regular database can't?
```

**Socratic learning:**
```
I want to learn about supply and demand in economics. Don't explain it directly —
ask me questions that guide me to figure it out myself. Start simple and build up.
```

**Quiz me:**
```
Quiz me on the causes of World War I. Ask me 5 questions one at a time.
After each of my answers, tell me if I'm right and explain anything I got wrong
before moving to the next question.
```

**Generate a quiz:**
```
Create a 10-question multiple choice quiz on Python basics for a beginner.
Include answer explanations for each question.
Topics: variables, data types, loops, functions, and lists.
```

**Spaced repetition:**
```
I just learned about photosynthesis. Create a review schedule for the next 2 weeks
using spaced repetition principles. Tell me what to review on each day and what kinds
of questions to ask myself.
```

**Personal learning plan:**
```
I want to learn Python programming from scratch. I have:
- 30 minutes per day to study
- A goal of building a simple web scraper in 8 weeks
- No prior programming experience

Create a week-by-week learning plan. Include:
- What to study each week
- Specific resources or exercises to complete
- A mini-project at the end of each week to reinforce learning
- Checkpoints to measure progress
```

---

### Day 21 — Creative Writing & Storytelling

**Story brainstorm:**
```
Give me 10 original short story premises in the genre of psychological thriller.
Each one should have:
- A one-line hook
- The central tension or mystery
- An unexpected twist element

Make them varied — different settings, protagonists, and themes.
```

**Title generation:**
```
I've written a novel about a marine biologist who discovers that a newly identified
deep-sea creature is the source of an ancient myth about sea monsters.

Generate 15 possible titles. Mix approaches: evocative, mysterious, clever wordplay, and direct.
```

**Write a short story:**
```
Write a 600-word short story based on this premise:

A lighthouse keeper discovers that the light she's been maintaining for 20 years
doesn't guide ships — it's been signalling something beneath the ocean.

Genre: literary fiction with elements of quiet horror.
Tone: melancholy and atmospheric.
End on an ambiguous note that leaves the reader unsettled.
```

**Opening sentence variations:**
```
Write 5 different opening sentences for a story about a disgraced lawyer returning
to their hometown after 10 years. Vary the technique:
1. Start in the middle of action (in medias res)
2. Start with a provocative statement
3. Start with a sensory description
4. Start with dialogue
5. Start with an intriguing question
```

**Subtext-driven scene:**
```
Write a tense scene between two estranged siblings meeting for the first time in 5 years
at their father's funeral. Neither wants to fight in public, but there's enormous unresolved
conflict beneath the surface. Show the tension through subtext — what they don't say matters
as much as what they do.
```

**Character profile:**
```
Create a detailed character profile for a morally ambiguous protagonist in a crime novel:

- Name, age, appearance
- Background and formative experiences
- Core motivation (what do they want?)
- Core fear (what do they avoid?)
- Fatal flaw that will create story conflict
- Speech patterns and quirks
- What they would never do — and what would make them do it anyway
```

---

## 🚀 Phase 4 — Advanced Claude (Days 22–28)

### Day 22 — Structured Output

**JSON extraction:**
```
Extract the following information from this job posting and return it as a JSON object:

Fields: job_title, company, location, salary_range, required_experience_years,
key_skills (array), remote (boolean), application_deadline

Job posting:
[paste job posting text]
```

**Batch JSON parsing:**
```
I have 5 customer complaints below. Parse each one into a JSON array.
Each object should have: id (1-5), category, sentiment (positive/negative/neutral),
priority (high/medium/low), and a one-sentence summary.

Complaint 1: [text]
Complaint 2: [text]
...
```

**Comparison table:**
```
Create a comparison table of these 5 project management tools:
Jira, Trello, Asana, Monday.com, and Notion.

Columns: Tool, Best for (team size), Pricing model, Key strength, Key weakness, Free tier available (yes/no)
Format it as a Markdown table.
```

**Formatted list:**
```
List the 10 most important keyboard shortcuts in VS Code.
Format as a bulleted list with the shortcut on the left and the function on the right.
Group by category (Navigation, Editing, Search).
```

**Meeting notes extraction:**
```
Read these rough meeting notes and extract:
1. A bulleted list of all decisions made
2. A table of action items with columns: Task, Owner, Deadline
3. A bulleted list of open questions that still need answers

Meeting notes:
[paste notes]
```

**CV to JSON:**
```
Parse this CV into a JSON object with the following structure:
{
  "name": "", "email": "", "phone": "", "summary": "",
  "experience": [{"company": "", "role": "", "dates": "", "bullets": []}],
  "education": [{"institution": "", "degree": "", "year": ""}],
  "skills": []
}

CV text:
[paste CV]
```

---

### Day 24 — Claude for Business & Productivity

**Client delay email:**
```
Draft a professional email to a client explaining that their project will be delayed
by 2 weeks due to a supplier issue. Tone: apologetic but confident. Include:
- An acknowledgement of the inconvenience
- A brief, honest explanation (no technical jargon)
- A revised timeline
- What we're doing to prevent this happening again
- An offer for a call to discuss further
```

**Complaint response:**
```
I've received this complaint email from a customer. Draft a response that:
- Acknowledges their frustration without admitting liability
- Offers a concrete next step
- Keeps the door open for resolution
- Is polite but not overly apologetic

Email: [paste email]
```

**Email triage:**
```
I have these 8 emails in my inbox. For each one, give me:
1. A one-sentence summary
2. Priority (high/medium/low)
3. Suggested action (reply, forward, archive, delegate)
4. A draft reply if action is "reply"

[paste email list]
```

**Meeting prep:**
```
I have a meeting tomorrow with a new client — a retail company that wants to improve
their online presence. The meeting is 60 minutes. Help me:
1. A list of 10 questions to ask them
2. A suggested agenda with time allocations
3. Key information I should know about the retail industry's current digital challenges
```

**Meeting notes → action items:**
```
Here are my rough notes from today's project kickoff meeting. Please extract:
1. A bullet list of all decisions made
2. A table of action items with: Task | Owner | Deadline
3. A list of open questions that still need answers
4. A 3-bullet summary I can send to the team

Meeting notes:
[paste notes]
```

---

### Day 25 — System Prompts

**Customer support bot system prompt:**
```
You are Max, the support assistant for Brewly — a UK-based coffee subscription service.

Your job: Help customers with account issues, subscription changes, delivery questions,
and product recommendations.

Always:
- Greet customers warmly by name if they share it
- Confirm what you understood before answering
- Offer to escalate to a human agent if needed
- Mention our free 30-day trial when relevant

Never:
- Make promises about specific delivery dates
- Process cancellations directly (send to brewly.com/cancel)
- Discuss competitors

Tone: Friendly, warm, and knowledgeable — like a barista who really knows their coffee.
Use British English. Keep responses under 150 words unless the question requires more.
```

**Personal writing assistant system prompt:**
```
You are my personal writing assistant. You help me write and edit professional communications.

My role: Senior product manager at a B2B software company
My writing style: Clear, direct, and confident — never fluffy
My audience: Usually technical stakeholders or C-suite

When I give you a task:
1. Ask one clarifying question if you need more context
2. Produce a draft
3. Offer 1–2 suggestions for improvement

Format: Markdown unless I say otherwise.
Length: Match what the task requires — no padding.
Tone: Professional but never corporate or jargony.
British English spelling always.
```

---

## 🎓 Phase 5 — Projects (Days 29–30)

### Day 29 — Mini Projects

**Project 1: Personal Learning Guide**

```
You are an expert educator and curriculum designer. I want to learn [TOPIC] from scratch.
My current level: [COMPLETE BEGINNER / SOME FAMILIARITY / INTERMEDIATE]
Time available: [X hours per week]

Think step by step. List the 5 most important concepts I need to learn in [TOPIC],
ordered from foundational to advanced. For each concept, explain in one sentence
why it matters and what understanding it unlocks.
```

```
Now create a structured study guide for these 5 concepts. For each one include:
- A simple 2-sentence explanation (no jargon)
- One real-world analogy that makes it intuitive
- One hands-on exercise I can do this week
- One type of resource to look for (book, video, article, course)

Format as a table: Concept | Explanation | Analogy | Exercise | Resource Type
```

```
Now write a 4-week learning plan based on [X hours per week].
Give each week a single theme and list 3 specific actions for that week.
Present as a table: Week | Theme | Action 1 | Action 2 | Action 3
```

---

**Project 2: Weekly Content Calendar**

```
You are a professional social media strategist with 10 years of experience
growing audiences on [PLATFORM].

I run [DESCRIBE YOUR ACCOUNT OR BUSINESS].
My target audience: [DESCRIBE AUDIENCE]
My goal: [GROW FOLLOWERS / BUILD AUTHORITY / DRIVE SALES / EDUCATE]

Suggest 5 content themes that would resonate strongly with this audience.
For each theme, explain in one sentence why it works for my specific goal.
```

```
Using those 5 themes, create a 7-day content calendar.
For each day include: Day | Theme | Post Idea | Hook | CTA
Present as a table.
```

```
Pick the strongest post idea. Write the full post text, ready to copy and paste.
Keep it under [WORD LIMIT]. Include 3–5 relevant hashtag suggestions.
```

---

**Project 3: Job Application Pack**

```
I'm applying for the following job.

JOB TITLE: [TITLE]
COMPANY: [COMPANY NAME]
JOB DESCRIPTION:
[PASTE THE FULL JOB DESCRIPTION]

MY BACKGROUND:
[PASTE YOUR RESUME OR 3–5 SENTENCE SUMMARY]

Analyse the job description. List the top 5 skills they are looking for.
Tell me which I clearly demonstrate, which I partially have, and which I'm missing.
```

```
Write a professional cover letter for this role. Use my top 3 matching skills.
Structure: 3 paragraphs — excitement, experience, closing CTA.
Tone: professional but warm. No clichés. Under 350 words.
```

```
Predict the 5 most likely interview questions for this role.
Write a STAR method answer for each based on my background.
Format: Question → STAR Answer (4–6 sentences each)
```

---

**Project 4: Mini Business Plan**

```
I have a business idea: [DESCRIBE IN 2–3 SENTENCES]

Think step by step. Identify:
1. The core problem it solves
2. Who exactly has this problem
3. Why existing solutions fall short
4. How significant this problem is
```

```
Build a simple business model:
- Product/Service, Revenue model, Cost structure
- Competitive advantage, Top 3 competitors and differentiation
Present as clearly labelled sections.
```

```
Write a 3-sentence executive summary.
Answer: What is it? Who is it for? Why will it win?
No buzzwords. No jargon.
```

---

**Project 5: Custom Flashcard Deck**

```
You are an expert teacher creating study flashcards. Here are two examples:

Q: What is a Large Language Model (LLM)?
A: A type of AI trained on vast amounts of text that can understand and
   generate human language in conversation.

Q: What is a "prompt" in the context of AI?
A: The instruction, question, or input you give to an AI model to get a response.

Now create 20 flashcards on the topic of [YOUR TOPIC].
Cover: key definitions, core concepts, "how it works" questions, one common misconception.
Use the exact same Q / A format. Number each card.
```

```
Cards [X], [Y], and [Z] cover the most complex concepts.
For each, add: "💡 Remember it like this:" — a simple analogy or memory trick.
```

---

### Day 30 — Final Project

**Day 1 vs Day 30 reflection:**
```
I just completed a 30-day course on using Claude AI. Help me reflect on my growth.

On Day 1, I knew: [what you knew about AI before starting]
On Day 1, my first prompt was probably: [a sample of how you used to prompt]

Today, I understand: [what you know now]
Today, I would prompt the same request like this: [rewrite with new skills]

Analyse the difference between my Day 1 and Day 30 approaches.
What specifically improved, and why does it matter?
```

**Track A — Personal AI Toolkit (Phase 1):**
```
I've just completed a 30-day course on Claude AI. I want to build a personal
AI playbook for how I use Claude going forward.

My situation: [describe your job, studies, or main daily activities]
My biggest time drains: [list 3 tasks]
My biggest goals right now: [list 2–3 things you're working toward]

Identify the top 5 areas of my life where Claude could save me the most time
or have the biggest positive impact. For each area, give one specific example.
```

**Track B — Professional AI Playbook (Phase 1):**
```
I work as [JOB TITLE] at [TYPE OF COMPANY].
My main responsibilities: [LIST 3–5 KEY TASKS]
My team's biggest challenges: [LIST 2–3 PAIN POINTS]

You are a senior AI strategy consultant. Map the top 10 tasks in my role
that Claude could assist with. For each, estimate time saved, quality improvement,
and risk to watch for. Present as a prioritised table.
```

**Track C — Developer Launchpad (Phase 1):**
```
I want to build a Claude-powered application. My idea:
[DESCRIBE IN 2–3 SENTENCES]

Target users: [WHO WILL USE IT]
Core problem it solves: [THE PAIN POINT]

You are a senior AI engineer. Help me define the minimum viable version.
What is the single most important thing it must do? What can be left for later?
```

---

## 🔑 Quick Reference — Universal Templates

These work for almost any task. Swap in your details.

**The Universal Briefing:**
```
You are a [ROLE WITH YEARS OF EXPERIENCE].
Context: [YOUR SITUATION IN 2–3 SENTENCES]
Task: [EXACTLY WHAT YOU WANT]
Format: [TABLE / BULLETS / PARAGRAPHS / JSON]
Constraints: [LENGTH, TONE, AUDIENCE, WHAT TO AVOID]
```

**The Iterative Refinement:**
```
[paste Claude's previous output]

That's good. Now:
- Make it [shorter / longer / more formal / more casual]
- Add [something specific]
- Remove [something specific]
- Change the [section/paragraph/tone] to [desired change]
```

**The Critique Round:**
```
Review the output you just gave me. Find:
1. Three weaknesses or gaps
2. One thing that could be misunderstood
3. The single most important improvement

Then rewrite it with those improvements applied.
```

**The Persona Lock:**
```
For this entire conversation, you are [ROLE]. Do not break character.
Every response should come from that perspective, vocabulary, and set of priorities.

Understood? If so, introduce yourself briefly and ask what I need help with.
```

---

*This prompt library covers all 30 days of the course. Every prompt is designed to work in claude.ai — no coding or API access required. Replace `[PLACEHOLDERS]` with your real details for best results.*
