# Learn JavaScript – A Practical, Challenge‑First Roadmap

This README gives you a hands‑on path to learn modern JavaScript through the **best free + high‑quality resources** and **curated coding challenges**. It’s split into stages so you can jump in at your current level.

---

## 🎯 Learning Goals
- Write clean, idiomatic ES6+ JavaScript
- Master the DOM, events, async (Promises/`async`–`await`), and modules
- Build small projects, then real apps (with tests)
- Learn just enough Node.js and tooling to be productive

---

## 🧰 Prerequisites & Setup
- **Install Node.js** (use **nvm** to manage versions): <https://github.com/nvm-sh/nvm>
- **Editor:** VS Code + extensions: Prettier, ESLint, GitLens
- **Format & Lint:** Prettier + ESLint (Airbnb or Standard config)
- **Browser DevTools:** Learn the Sources tab, breakpoints, Network panel

---

## 🗺️ Roadmap (8 Weeks, ~7–10 hrs/week)

### Week 1 – JS Basics & Syntax
- Variables (`let`/`const`), types, operators, conditionals, loops
- **Challenges:**
  - Recreate FizzBuzz
  - Reverse a string, check palindrome
- **Resources:**
  - **MDN JS Guide:** <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide>
  - **javascript.info (The Modern JS Tutorial):** <https://javascript.info>

### Week 2 – Functions, Arrays, Objects
- Functions, arrow funcs, array methods (`map/filter/reduce`), object patterns
- **Challenges:**
  - Implement `map`, `filter` from scratch
  - Frequency counter (anagrams)
- **Resources:**
  - **Eloquent JavaScript (chapters 1–5):** <https://eloquentjavascript.net/>

### Week 3 – DOM & Events
- Querying/manipulating DOM, events, delegation, forms
- **Project:**
  - **Vanilla To‑Do App** (add/edit/delete, filter, persist to `localStorage`)
- **Resources:**
  - **MDN – DOM:** <https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model>

### Week 4 – Async & APIs
- Callbacks → Promises → `async`/`await`, Fetch API, error handling
- **Project:**
  - **Weather Dashboard** (Fetch by city, loading/error states)
- **Resources:**
  - **MDN – Fetch:** <https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API>
  - **You Don’t Know JS Yet – Async & Performance (free):** <https://github.com/getify/You-Dont-Know-JS>

### Week 5 – Modules, Build, and Patterns
- ES Modules, bundlers (Vite), environment variables
- **Project:**
  - **Quiz App** (module split, state machine, timer)

### Week 6 – Testing Fundamentals
- Unit tests with **Jest**, DOM tests with **@testing-library/dom**
- **Challenges:**
  - TDD a simple calculator
  - Test the Quiz App
- **Resources:**
  - **Jest Docs:** <https://jestjs.io/docs/getting-started>
  - **Testing Library:** <https://testing-library.com/docs/dom-testing-library/intro/>

### Week 7 – Data Structures & Algorithms (DSA, optional but valuable)
- Time/space complexity, classic problem patterns (two pointers, sliding window)
- **Challenges:** 10–15 kata on arrays/strings/stacks
- **Resources:**
  - **Codewars:** <https://www.codewars.com/>
  - **LeetCode (Top Interview/Easy–Medium):** <https://leetcode.com/>
  - **Exercism – JavaScript track:** <https://exercism.org/tracks/javascript>
  - **JSChallenger:** <https://www.jschallenger.com/>

### Week 8 – Capstone & Portfolio
- **Pick one:**
  - **Movie Explorer** (search, details, favorites, pagination)
  - **Kanban Board** (drag‑drop, persistence)
- Add **README**, live demo (Netlify/Vercel), and tests

---

## 🧪 Daily Practice (15–30 min)
- 1–2 kata on **Codewars/Exercism/JSChallenger**
- Read 3–5 pages of **Eloquent JavaScript** or **javascript.info**
- Review notes, refactor yesterday’s code

---

## 📦 Challenge Playlists

### Beginner
- FizzBuzz variants (3 rules → 5 rules)
- String utilities: reverse, capitalize, title‑case, isogram
- Arrays: chunk, flatten (1 level), unique values
- Objects: convert entries ↔ object, deep get by path

### Intermediate
- Debounce & throttle (implement from scratch)
- Event delegation utility
- Promise utilities: `all`, `race`, `allSettled` clones
- Infinite scroll with Fetch
- Drag‑and‑drop sortable list

### Advanced
- Memoization cache with eviction
- Simple state machine (finite states + transitions)
- Virtualized list (windowing)
- Build a tiny router (hash‑based)

> Treat each challenge like production: write a short spec, tests, and a README snippet.

---

## 📚 Core Learning Resources (Curated)
- **MDN Web Docs (canonical reference):** <https://developer.mozilla.org/>
- **javascript.info (narrative, modern):** <https://javascript.info>
- **Eloquent JavaScript (book, free):** <https://eloquentjavascript.net/>
- **The Odin Project (full‑stack, project‑based):** <https://www.theodinproject.com/paths/full-stack-javascript>
- **freeCodeCamp (certifications + projects):** <https://www.freecodecamp.org/learn>
- **Scrimba JS (interactive screencasts):** <https://scrimba.com/learn/learnjavascript>
- **Wes Bos – JavaScript30 (30 days of DOM projects):** <https://javascript30.com/>
- **JSChallenger (interactive coding puzzles):** <https://www.jschallenger.com/>

### Practice & Project Sites
- **Frontend Mentor (UI challenges):** <https://www.frontendmentor.io/challenges>
- **Codewars (kata):** <https://www.codewars.com/>
- **Exercism (mentor feedback):** <https://exercism.org/tracks/javascript>
- **Advent of Code (seasonal puzzles):** <https://adventofcode.com/>
- **freeCodeCamp Projects:** <https://www.freecodecamp.org/learn>

### YouTube Channels (free, high‑signal)
- **Web Dev Simplified:** <https://www.youtube.com/@WebDevSimplified>
- **Fireship:** <https://www.youtube.com/@Fireship>
- **The Net Ninja:** <https://www.youtube.com/@NetNinja>

### Node & Backend (light intro)
- **Node.js Docs:** <https://nodejs.org/en/docs>
- **Express Guide:** <https://expressjs.com/en/starter/installing.html>

---

## 🧱 Real‑World Project Ideas (progressive)
1. **Unit Converter** (pure DOM, no frameworks)
2. **Notes App** (CRUD + `localStorage`, search)
3. **Github Repo Explorer** (Fetch API + pagination + caching)
4. **Expense Tracker** (charts; persist; import/export JSON)
5. **Realtime Chat (bonus)** with WebSocket echo server

Each project should include:
- Clear **README** with features, screenshots, and setup
- **Accessibility** checks (keyboard, labels, contrast)
- **Tests** (Jest + DOM Testing Library)

---

## 🧑‍💻 Tooling Cheatsheet
- **Create a project quickly:** `npm create vite@latest my-app -- --template vanilla`
- **Add Jest:** `npm i -D jest @types/jest` (use `babel-jest` if transpiling)
- **Prettier + ESLint:** `npm i -D prettier eslint eslint-config-prettier` and add a basic config
- **Env variables (Vite):** `.env` with `VITE_*` keys → `import.meta.env.VITE_API_KEY`

---

## 🧠 Study Tips
- **Build > read.** Skim a chapter, then code a mini‑project immediately.
- **Spaced repetition:** revisit tricky topics (closures, `this`, prototypes).
- **Rubber‑duck debugging:** explain your code aloud; use DevTools breakpoints.
- **Publish** everything (GitHub + live demo). Feedback accelerates learning.

---

## ✅ What to Do Next (choose one)
- Start **Week 1** and push a repo named `js‑learning‑roadmap`
- Pick 3 **Beginner** challenges and implement with tests
- Clone **JavaScript30** and complete Day 1–3

> Need a personalized weekly plan or project review rubric? Ask and I’ll generate one based on your available hours and goals.

