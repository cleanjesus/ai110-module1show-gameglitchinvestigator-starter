# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?

  First run looked fine on the surface. The title, guess box, submit, and new game buttons all showed up. Once I started playing it fell apart. It felt delayed and incosistent and I noticed bugs below.

- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").
  - The hints are backwards
  - Score goes negative
  - Attempts left aren't respected
  - The new game button doesnt work
  - History is one step behind

**Bug Reproduction Log**

Document at least 3 bugs you found. Add rows as needed.

| Input | Expected Behavior | Actual Behavior | Console Output / Error |
|-------|-------------------|-----------------|------------------------|
| new game | start new game with refreshed attempts | no new game is started | NA |
| guess 60, secret 77 (from debug) | hint says go lower | hint says go higher | NA |
| submit wrong guesses a few times | score stays at 0 or goes up on wins | score goes negative | NA |
| submit a guess | history updates right away in debug tab | history is one step behind | NA |

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
