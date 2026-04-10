# Prompt Templates

Ready-to-use prompts for your data science and AI studies. Copy, paste, and fill in the `[brackets]`.

> All templates follow Google’s **Gemini Prompt 101** framework: **Persona · Task · Context · Format**  
> Source: [Gemini Prompting Guide 101](https://services.google.com/fh/files/misc/gemini-for-google-workspace-prompting-guide-101.pdf)

---

## 📚 Understanding Research Papers

### Get a Plain-English Summary
```
You are a science journalist who explains AI research to general audiences.  [Persona]
Summarise the key idea of this paper in 3 short paragraphs:   [Task]
(1) the problem it addresses, (2) the solution proposed, (3) why it matters.
The paper is: [title]. I have no math or coding background.   [Context]
Use plain language and one everyday analogy. No bullet points. [Format]
```

### Explain a Specific Section
```
You are a patient university tutor.
Explain [section name or concept] from the paper [paper title].
I’m confused by this section and have no math or coding background.
Use a real-world analogy. Keep it under 150 words.
```

### Build a Study Q&A
```
You are an exam coach for adult learners.
Create 5 comprehension questions based on the paper [title].
The questions should test whether a beginner understands the core ideas — not the technical details.
List each question followed immediately by its answer.
```

---

## 🧠 Understanding Concepts

### Beginner Explanation
```
You are an experienced data science educator teaching adult learners with no technical background.
Explain [concept] in plain English.
I’m new to this field and want to understand the core idea, not the maths.
Use one analogy from everyday life. Keep it under 200 words.
```

### Compare Two Concepts
```
You are a data science tutor.
Explain the difference between [concept A] and [concept B] using a concrete example.
I keep confusing these two and want a simple rule of thumb to tell them apart.
Format as: (1) a one-line definition of each, (2) the key difference, (3) a memory tip.
```

### Go One Level Deeper
```
You are a patient technical educator.
I understand the basics of [concept]. Now explain what’s actually happening "under the hood."
Assume I have no coding or maths background.
Use simple language and a concrete example.
```

---

## 🔍 Assign a Role (Who Is the Expert?)

### Step 1 — Find the Right Expert
```
Who would be the best type of expert to explain [topic] 
to someone with a [your background, e.g. business / healthcare / arts] background?
Once you’ve identified the expert, respond as that expert.
```

### Step 2 — Reframe for Your Background
```
You are a [expert role from Step 1].
Explain [concept] using examples and analogies from [your field or background].
My goal is to understand this well enough to [what you want to do with it].
Keep it concise — no more than 3 short paragraphs.
```

---

## 💬 Prompt Iteration Templates

These are follow-up prompts to refine an answer you’ve already received. Use them *after* a first response.

### Make It Simpler
```
That’s still a bit technical. Simplify it further — imagine I’ve never studied science.
```

### Change the Format
```
Now rewrite that as [bullet points / a table / a numbered list / a short story].
```

### Change the Tone
```
Rewrite that in a [more casual / more formal / more encouraging] tone.
```

### Make It Shorter
```
Summarise that in 3 sentences or fewer.
```

### Ask for a Memorable Analogy
```
Give me one memorable analogy I could use to explain this to someone else.
```

### Challenge My Understanding
```
Here is my understanding of [concept]: [write your explanation]
What have I got right? What am I missing or wrong about?
Be specific and constructive — I’m still learning.
```

---

## 📝 Study & Exam Prep

### Turn Notes into a Study Guide
```
You are a study skills coach.
Turn these notes into a structured study guide: [paste notes]
The guide should include: key definitions, the 3 most important concepts, and 3 practice questions with answers.
Format it clearly with headings for each section.
```

### Prepare for a Class Discussion
```
You are a discussion facilitator.
I have a class discussion coming up on [topic].
Give me 3 insightful questions I could raise, and a brief talking point for each.
My audience are fellow learners who are also new to this field.
Keep each point to 2–3 sentences.
```

### Ask AI for Feedback on Your Prompt
```
Here is a prompt I wrote: [your prompt]
How can I improve it to get a clearer, more useful answer?
Rewrite it using best practices: clear persona, specific task, relevant context, defined format.
```

---

## 🤖 Meta Prompts (Ask AI to Help You Prompt)

### Generate a Better Prompt from Scratch
```
I want to ask an AI about [your topic].
Help me write a clear, detailed prompt that will get the best possible answer.
My goal is: [what you’re trying to achieve].
My background: [your level and context].
```

### Improve a Prompt You Already Have
```
Here is a prompt I wrote: [your prompt]
Improve it using the Persona, Task, Context, Format framework.
My goal is to get a clear, beginner-friendly explanation of [topic].
```

---

## 💡 Quick Tips (from Google’s Gemini Guide 101)

These habits improve every prompt you write:

- **Use a verb in your task** — *summarise, explain, draft, compare, list, rewrite*
- **State your level** — always say you’re a beginner or describe your background
- **Give constraints** — "under 100 words", "exactly 3 options", "no bullet points"
- **Assign a role** — "You are a..." dramatically shapes the response
- **Make it a conversation** — follow up, refine, and iterate
- **Ask for feedback** — "What questions do you have that would help you give a better answer?"
- **Break it up** — if you need several things, use separate prompts

---

*← [Back to Prompting Lesson](../lessons/02-prompting.md) | [Back to Home](../README.md)*
