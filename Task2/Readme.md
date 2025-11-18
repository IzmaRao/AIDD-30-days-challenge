# 📁Part A — Theory (Short Questions)
## 1. Nine Pillars Understanding

### Q1. Why is using AI Development Agents (like Gemini CLI) for repetitive setup tasks
better for your growth as a system architect?

### Q2. Explain how the Nine Pillars of AIDD help a developer grow into an M-Shaped
Developer.

## 2. Vibe Coding vs Specification-Driven Development

### Q1. Why does Vibe Coding usually create problems after one week?
devolper ki lack of knowledge  jaisa ka kuch devolpers bas chatgpt sa kam karwata hen or phir jab bug ata hen to resollve nhi hota kio ka unho na na hi un languages ko master kiya hota na ai sa kam karwana ka tarekon ko master kiya hota.
aik or wajah bhi a sakti hen kio  ka sara kam ai kar rahi hen to devolper nhi pata ka error kaha par konsi module or file ma hen to is liya bhi time lag sakta hen Vibe Coding ma. 

### Q2. How would Specification-Driven Development prevent those problems?

## 3. Architecture Thinking

### Q1. How does architecture-first thinking change the role of a developer in AIDD?

### Q2. Explain why developers must think in layers and systems instead of raw code.

# 📁 Part B — Practical Task
<img width="1103" height="540" alt="image" src="https://github.com/user-attachments/assets/66481bfb-1aa0-449e-8a5b-2b2a9c6814b9" />

## Prompt:
Write a clear, one-paragraph spec for an email validation function that checks the email "izmarao99@gamil.com".  It must: Ensure "@" is present, Validate common domains (.com,etc.), Detect typos in popular providers (e.g., gamil → gmail), Return user-friendly error messages like "Missing @ symbol", "Invalid domain", or "Did you mean gmail.com?", and The function should return true only if the email is fully valid, otherwise a helpful string error.
## Output:
  The email validation function will analyze a string like "izmarao99 @gamil.com" to ensure it is a correctly formatted█
  and deliverable address. It must first confirm the presence of an "@" symbol, returning a "Missing @ symbol" error if█
  absent. The function will then validate the domain, checking for valid top-level domains (e.g., .com, .org) and      █
  flagging any issues with an "Invalid domain" message. Crucially, it will also detect common misspellings in popular  █
  email providers, so for an input like "gamil.com," it should suggest a correction by returning, "Did you mean        █
  gmail.com?". Only if the email format is completely valid and passes all checks, including the typo analysis, will   █
  the function return True; otherwise, it will return the appropriate user-friendly error string.


# 📁 Part C — Multiple Choice Questions
## 1. What is the main purpose of Spec-Driven Development?
1. Make coding faster
2. Clear requirements before coding begins ✅
3. Remove developers
4. Avoid documentation
## 2. What is the biggest mindset shift in AI-Driven Development?
1. Writing more code manually
2. Thinking in systems and clear instructions ✅
3. Memorizing more syntax
4. Working without any tools
## 3. Biggest failure of Vibe Coding?
1. AI stops responding
2. Architecture becomes hard to extend ✅
3. Code runs slow
4. Fewer comments written
## 4. Main advantage of using AI CLI agents (like Gemini CLI)?
1. They replace the developer completely
2. Handle repetitive tasks so dev focuses on design & problem-solving ✅
3. Make coding faster but less reliable
4. Make coding optional
## 5. What defines an M-Shaped Developer?
1. Knows little about everything
2. Deep in only one field
3. Deep skills in multiple related domains ✅
4. Works without AI tools
