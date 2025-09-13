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




# JavaScript Mega Challenge – Popular & Important 150 Tasks

_Generated on 2025-09-13T12:32:41.888302Z_


## Beginner (50) – Fundamentals that appear in popular questions


### 1. Declare variables with let/const; swap two numbers without temp.

**Code**
```js
let a = 5, b = 9;
[a, b] = [b, a];
console.log(a, b);
```

**Output**
```text
9 5
```


### 2. Check if a string is a palindrome (ignore case & non-alphanumerics).

**Code**
```js
const isPal = (s) => {
  const t = s.toLowerCase().replace(/[^a-z0-9]/g, '');
  return t === [...t].reverse().join('');
};
console.log(isPal('A man, a plan, a canal: Panama'));
```

**Output**
```text
true
```


### 3. Find max/min in an array without sorting.

**Code**
```js
const arr = [3, 9, -2, 7, 0];
let max = -Infinity, min = Infinity;
for (const x of arr) { if (x > max) max = x; if (x < min) min = x; }
console.log(max, min);
```

**Output**
```text
9 -2
```


### 4. Count vowels in a string.

**Code**
```js
const countVowels = s => [...s].filter(c => 'aeiouAEIOU'.includes(c)).length;
console.log(countVowels('Beautiful Day'));
```

**Output**
```text
6
```


### 5. Reverse words in a sentence (keep word order; reverse each word).

**Code**
```js
const revWords = s => s.split(' ').map(w => [...w].reverse().join('')).join(' ');
console.log(revWords('JavaScript is fun'));
```

**Output**
```text
tpircSavaJ si nuf
```


### 6. Remove duplicates from array while preserving order.

**Code**
```js
const unique = (arr) => { const seen = new Set(); return arr.filter(x => (seen.has(x) ? false : (seen.add(x), true))); };
console.log(unique([1,2,2,3,1,4]));
```

**Output**
```text
[1,2,3,4]
```


### 7. Flatten a 1-level nested array using reduce.

**Code**
```js
const flat1 = arr => arr.reduce((a, b) => a.concat(b), []);
console.log(flat1([1, [2, 3], 4]));
```

**Output**
```text
[1,2,3,4]
```


### 8. Compute factorial iteratively.

**Code**
```js
const fact = n => { let f = 1; for (let i = 2; i <= n; i++) f *= i; return f; };
console.log(fact(6));
```

**Output**
```text
720
```


### 9. FizzBuzz (1..15) using map.

**Code**
```js
const out = Array.from({ length: 15 }, (_, i) => i + 1).map(n => (n % 15 === 0 ? 'FizzBuzz' : n % 3 === 0 ? 'Fizz' : n % 5 === 0 ? 'Buzz' : String(n)));
console.log(out);
```

**Output**
```text
["1","2","Fizz","4","Buzz","Fizz","7","8","Fizz","Buzz","11","Fizz","13","14","FizzBuzz"]
```


### 10. Sum of integers from 1..n (formula).

**Code**
```js
const sumTo = n => n * (n + 1) / 2;
console.log(sumTo(100));
```

**Output**
```text
5050
```


### 11. Get frequency map of elements in array.

**Code**
```js
const freq = (arr) => arr.reduce((m, n) => (m[n] = (m[n] || 0) + 1, m), {});
console.log(freq([1,2,2,3,3,3]));
```

**Output**
```text
{"1":1,"2":2,"3":3}
```


### 12. Capitalize first letter of each word.

**Code**
```js
const title = s => s.replace(/\b\w/g, c => c.toUpperCase());
console.log(title('make this title case'));
```

**Output**
```text
Make This Title Case
```


### 13. Check if two strings are anagrams (ignore case & spaces).

**Code**
```js
const norm = s => s.toLowerCase().replace(/\s+/g,'').split('').sort().join('');
const isAnagram = (a,b) => norm(a) === norm(b);
console.log(isAnagram('Listen','Silent'));
```

**Output**
```text
true
```


### 14. Chunk array into size k.

**Code**
```js
const chunk = (arr, k) => { const out=[]; for (let i=0;i<arr.length;i+=k) out.push(arr.slice(i,i+k)); return out; };
console.log(chunk([1,2,3,4,5],2));
```

**Output**
```text
[[1,2],[3,4],[5]]
```


### 15. Get unique values using Set.

**Code**
```js
const unique = arr => [...new Set(arr)];
console.log(unique(['a','b','a','c']));
```

**Output**
```text
["a","b","c"]
```


### 16. Find index of first non-repeating char.

**Code**
```js
const firstUnique = s => { const m = {}; for (const c of s) m[c]=(m[c]||0)+1; for (let i=0;i<s.length;i++) if (m[s[i]]===1) return i; return -1; };
console.log(firstUnique('swiss'));
```

**Output**
```text
1
```


### 17. Remove falsy values (0, '', null, undefined, NaN, false).

**Code**
```js
const compact = arr => arr.filter(Boolean);
console.log(compact([0,1,false,2,'',3,null,undefined,NaN]));
```

**Output**
```text
[1,2,3]
```


### 18. Find intersection of two arrays.

**Code**
```js
const inter = (a,b) => { const s=new Set(a); return b.filter(x => s.has(x)); };
console.log(inter([1,2,3,4],[3,4,5]));
```

**Output**
```text
[3,4]
```


### 19. Find union of two arrays (unique).

**Code**
```js
const union = (a,b) => [...new Set([...a,...b])];
console.log(union([1,2],[2,3]));
```

**Output**
```text
[1,2,3]
```


### 20. Reverse an array in place.

**Code**
```js
const arr = [1,2,3,4];
for (let l=0, r=arr.length-1; l<r; l++, r--) [arr[l],arr[r]]=[arr[r],arr[l]];
console.log(arr);
```

**Output**
```text
[4,3,2,1]
```


### 21. Binary search (iterative) to find 3 in sorted array.

**Code**
```js
const arr = [0, 3, 6, 9, 12, 15, 18, 21, 24, 27, 30, 33, 36, 39, 42, 45, 48, 51, 54, 57, 60, 63, 66, 69, 72, 75, 78, 81, 84, 87, 90, 93, 96, 99];
const target = 3;
let l = 0, r = arr.length - 1, idx = -1;
while (l <= r) {
  const m = (l + r) >> 1;
  if (arr[m] === target) { idx = m; break; }
  if (arr[m] < target) l = m + 1; else r = m - 1;
}
console.log(idx);
```

**Output**
```text
1
```


### 22. Remove duplicate objects by id.

**Code**
```js
const arr = [{ id: 1, n: 'a' }, { id: 1, n: 'A' }, { id: 2, n: 'b' }];
const map = new Map();
for (const o of arr) map.set(o.id, o);
console.log([...map.values()]);
```

**Output**
```text
[{"id":1,"n":"A"},{"id":2,"n":"b"}]
```


### 23. Find the second largest number.

**Code**
```js
const arr = [5, 1, 9, 9, 7, 3];
let first = -Infinity, second = -Infinity;
for (const x of arr) {
  if (x > first) { second = first; first = x; }
  else if (x < first && x > second) second = x;
}
console.log(second);
```

**Output**
```text
7
```


### 24. Rotate array right by k steps.

**Code**
```js
const rotate = (arr, k) => {
  k %= arr.length;
  return arr.slice(-k).concat(arr.slice(0, -k));
};
console.log(rotate([1,2,3,4,5], 2));
```

**Output**
```text
[4,5,1,2,3]
```


### 25. Remove nth character from string.

**Code**
```js
const removeAt = (s, n) => s.slice(0, n) + s.slice(n + 1);
console.log(removeAt('abcdef', 2));
```

**Output**
```text
abdef
```


### 26. Binary search (iterative) to find 18 in sorted array.

**Code**
```js
const arr = [0, 3, 6, 9, 12, 15, 18, 21, 24, 27, 30, 33, 36, 39, 42, 45, 48, 51, 54, 57, 60, 63, 66, 69, 72, 75, 78, 81, 84, 87, 90, 93, 96, 99];
const target = 18;
let l = 0, r = arr.length - 1, idx = -1;
while (l <= r) {
  const m = (l + r) >> 1;
  if (arr[m] === target) { idx = m; break; }
  if (arr[m] < target) l = m + 1; else r = m - 1;
}
console.log(idx);
```

**Output**
```text
6
```


### 27. Remove duplicate objects by id.

**Code**
```js
const arr = [{ id: 1, n: 'a' }, { id: 1, n: 'A' }, { id: 2, n: 'b' }];
const map = new Map();
for (const o of arr) map.set(o.id, o);
console.log([...map.values()]);
```

**Output**
```text
[{"id":1,"n":"A"},{"id":2,"n":"b"}]
```


### 28. Find the second largest number.

**Code**
```js
const arr = [5, 1, 9, 9, 7, 3];
let first = -Infinity, second = -Infinity;
for (const x of arr) {
  if (x > first) { second = first; first = x; }
  else if (x < first && x > second) second = x;
}
console.log(second);
```

**Output**
```text
7
```


### 29. Rotate array right by k steps.

**Code**
```js
const rotate = (arr, k) => {
  k %= arr.length;
  return arr.slice(-k).concat(arr.slice(0, -k));
};
console.log(rotate([1,2,3,4,5], 2));
```

**Output**
```text
[4,5,1,2,3]
```


### 30. Remove nth character from string.

**Code**
```js
const removeAt = (s, n) => s.slice(0, n) + s.slice(n + 1);
console.log(removeAt('abcdef', 2));
```

**Output**
```text
abdef
```


### 31. Binary search (iterative) to find 33 in sorted array.

**Code**
```js
const arr = [0, 3, 6, 9, 12, 15, 18, 21, 24, 27, 30, 33, 36, 39, 42, 45, 48, 51, 54, 57, 60, 63, 66, 69, 72, 75, 78, 81, 84, 87, 90, 93, 96, 99];
const target = 33;
let l = 0, r = arr.length - 1, idx = -1;
while (l <= r) {
  const m = (l + r) >> 1;
  if (arr[m] === target) { idx = m; break; }
  if (arr[m] < target) l = m + 1; else r = m - 1;
}
console.log(idx);
```

**Output**
```text
11
```


### 32. Remove duplicate objects by id.

**Code**
```js
const arr = [{ id: 1, n: 'a' }, { id: 1, n: 'A' }, { id: 2, n: 'b' }];
const map = new Map();
for (const o of arr) map.set(o.id, o);
console.log([...map.values()]);
```

**Output**
```text
[{"id":1,"n":"A"},{"id":2,"n":"b"}]
```


### 33. Find the second largest number.

**Code**
```js
const arr = [5, 1, 9, 9, 7, 3];
let first = -Infinity, second = -Infinity;
for (const x of arr) {
  if (x > first) { second = first; first = x; }
  else if (x < first && x > second) second = x;
}
console.log(second);
```

**Output**
```text
7
```


### 34. Rotate array right by k steps.

**Code**
```js
const rotate = (arr, k) => {
  k %= arr.length;
  return arr.slice(-k).concat(arr.slice(0, -k));
};
console.log(rotate([1,2,3,4,5], 2));
```

**Output**
```text
[4,5,1,2,3]
```


### 35. Remove nth character from string.

**Code**
```js
const removeAt = (s, n) => s.slice(0, n) + s.slice(n + 1);
console.log(removeAt('abcdef', 2));
```

**Output**
```text
abdef
```


### 36. Binary search (iterative) to find 48 in sorted array.

**Code**
```js
const arr = [0, 3, 6, 9, 12, 15, 18, 21, 24, 27, 30, 33, 36, 39, 42, 45, 48, 51, 54, 57, 60, 63, 66, 69, 72, 75, 78, 81, 84, 87, 90, 93, 96, 99];
const target = 48;
let l = 0, r = arr.length - 1, idx = -1;
while (l <= r) {
  const m = (l + r) >> 1;
  if (arr[m] === target) { idx = m; break; }
  if (arr[m] < target) l = m + 1; else r = m - 1;
}
console.log(idx);
```

**Output**
```text
16
```


### 37. Remove duplicate objects by id.

**Code**
```js
const arr = [{ id: 1, n: 'a' }, { id: 1, n: 'A' }, { id: 2, n: 'b' }];
const map = new Map();
for (const o of arr) map.set(o.id, o);
console.log([...map.values()]);
```

**Output**
```text
[{"id":1,"n":"A"},{"id":2,"n":"b"}]
```


### 38. Find the second largest number.

**Code**
```js
const arr = [5, 1, 9, 9, 7, 3];
let first = -Infinity, second = -Infinity;
for (const x of arr) {
  if (x > first) { second = first; first = x; }
  else if (x < first && x > second) second = x;
}
console.log(second);
```

**Output**
```text
7
```


### 39. Rotate array right by k steps.

**Code**
```js
const rotate = (arr, k) => {
  k %= arr.length;
  return arr.slice(-k).concat(arr.slice(0, -k));
};
console.log(rotate([1,2,3,4,5], 2));
```

**Output**
```text
[4,5,1,2,3]
```


### 40. Remove nth character from string.

**Code**
```js
const removeAt = (s, n) => s.slice(0, n) + s.slice(n + 1);
console.log(removeAt('abcdef', 2));
```

**Output**
```text
abdef
```


### 41. Binary search (iterative) to find 63 in sorted array.

**Code**
```js
const arr = [0, 3, 6, 9, 12, 15, 18, 21, 24, 27, 30, 33, 36, 39, 42, 45, 48, 51, 54, 57, 60, 63, 66, 69, 72, 75, 78, 81, 84, 87, 90, 93, 96, 99];
const target = 63;
let l = 0, r = arr.length - 1, idx = -1;
while (l <= r) {
  const m = (l + r) >> 1;
  if (arr[m] === target) { idx = m; break; }
  if (arr[m] < target) l = m + 1; else r = m - 1;
}
console.log(idx);
```

**Output**
```text
21
```


### 42. Remove duplicate objects by id.

**Code**
```js
const arr = [{ id: 1, n: 'a' }, { id: 1, n: 'A' }, { id: 2, n: 'b' }];
const map = new Map();
for (const o of arr) map.set(o.id, o);
console.log([...map.values()]);
```

**Output**
```text
[{"id":1,"n":"A"},{"id":2,"n":"b"}]
```


### 43. Find the second largest number.

**Code**
```js
const arr = [5, 1, 9, 9, 7, 3];
let first = -Infinity, second = -Infinity;
for (const x of arr) {
  if (x > first) { second = first; first = x; }
  else if (x < first && x > second) second = x;
}
console.log(second);
```

**Output**
```text
7
```


### 44. Rotate array right by k steps.

**Code**
```js
const rotate = (arr, k) => {
  k %= arr.length;
  return arr.slice(-k).concat(arr.slice(0, -k));
};
console.log(rotate([1,2,3,4,5], 2));
```

**Output**
```text
[4,5,1,2,3]
```


### 45. Remove nth character from string.

**Code**
```js
const removeAt = (s, n) => s.slice(0, n) + s.slice(n + 1);
console.log(removeAt('abcdef', 2));
```

**Output**
```text
abdef
```


### 46. Binary search (iterative) to find 78 in sorted array.

**Code**
```js
const arr = [0, 3, 6, 9, 12, 15, 18, 21, 24, 27, 30, 33, 36, 39, 42, 45, 48, 51, 54, 57, 60, 63, 66, 69, 72, 75, 78, 81, 84, 87, 90, 93, 96, 99];
const target = 78;
let l = 0, r = arr.length - 1, idx = -1;
while (l <= r) {
  const m = (l + r) >> 1;
  if (arr[m] === target) { idx = m; break; }
  if (arr[m] < target) l = m + 1; else r = m - 1;
}
console.log(idx);
```

**Output**
```text
26
```


### 47. Remove duplicate objects by id.

**Code**
```js
const arr = [{ id: 1, n: 'a' }, { id: 1, n: 'A' }, { id: 2, n: 'b' }];
const map = new Map();
for (const o of arr) map.set(o.id, o);
console.log([...map.values()]);
```

**Output**
```text
[{"id":1,"n":"A"},{"id":2,"n":"b"}]
```


### 48. Find the second largest number.

**Code**
```js
const arr = [5, 1, 9, 9, 7, 3];
let first = -Infinity, second = -Infinity;
for (const x of arr) {
  if (x > first) { second = first; first = x; }
  else if (x < first && x > second) second = x;
}
console.log(second);
```

**Output**
```text
7
```


### 49. Rotate array right by k steps.

**Code**
```js
const rotate = (arr, k) => {
  k %= arr.length;
  return arr.slice(-k).concat(arr.slice(0, -k));
};
console.log(rotate([1,2,3,4,5], 2));
```

**Output**
```text
[4,5,1,2,3]
```


### 50. Remove nth character from string.

**Code**
```js
const removeAt = (s, n) => s.slice(0, n) + s.slice(n + 1);
console.log(removeAt('abcdef', 2));
```

**Output**
```text
abdef
```


## Intermediate (50) – Core patterns & data transforms


### 1. Implement debounce (trailing).

**Code**
```js
const debounce = (fn, wait = 300) => { let t; return (...args) => { clearTimeout(t); t = setTimeout(() => fn(...args), wait); }; };
const log = (...a) => console.log('debounced', ...a);
const d = debounce(log, 100);
d(1); d(2); setTimeout(() => d(3), 150);
```

**Output**
```text
debounced 3
```


### 2. Implement throttle (leading).

**Code**
```js
const throttle = (fn, wait = 300) => {
  let last = 0;
  return (...args) => {
    const now = Date.now();
    if (now - last >= wait) { last = now; fn(...args); }
  };
};
const t = throttle((x) => console.log('hit', x), 100);
t(1); t(2); setTimeout(() => t(3), 120);
```

**Output**
```text
hit 1
hit 3
```


### 3. Compose and pipe utilities.

**Code**
```js
const compose = (...fns) => x => fns.reduceRight((v, f) => f(v), x);
const pipe = (...fns) => x => fns.reduce((v, f) => f(v), x);
const double = x => x * 2, inc = x => x + 1;
console.log(compose(inc, double)(3), pipe(double, inc)(3));
```

**Output**
```text
7 7
```


### 4. Deep clone with JSON fallback.

**Code**
```js
const deepClone = (obj) => typeof structuredClone === 'function' ? structuredClone(obj) : JSON.parse(JSON.stringify(obj));
const a = { x: 1, b: { y: 2 } };
const b = deepClone(a); b.b.y = 9;
console.log(a.b.y, b.b.y);
```

**Output**
```text
2 9
```


### 5. Group array of objects by key.

**Code**
```js
const groupBy = (arr, key) => arr.reduce((m, o) => (m[o[key]] ||= []).push(o), m), {});
const arr = [{t:'A',v:1},{t:'B',v:2},{t:'A',v:3}];
console.log(groupBy(arr, 't'));
```

**Output**
```text
{"A":[{"t":"A","v":1},{"t":"A","v":3}],"B":[{"t":"B","v":2}]}
```


### 6. Flatten arbitrary depth using recursion.

**Code**
```js
const flatDeep = (arr) => arr.reduce((a, b) => a.concat(Array.isArray(b) ? flatDeep(b) : b), []);
console.log(flatDeep([1,[2,[3,[4]]]]));
```

**Output**
```text
[1,2,3,4]
```


### 7. Unique by key from array of objects.

**Code**
```js
const uniqBy = (arr, key) => Object.values(arr.reduce((m, o) => (m[o[key]] = o, m), {}));
console.log(uniqBy([{id:1,n:'a'},{id:1,n:'A'},{id:2,n:'b'}], 'id'));
```

**Output**
```text
[{"id":1,"n":"A"},{"id":2,"n":"b"}]
```


### 8. Partition array by predicate.

**Code**
```js
const partition = (arr, fn) => arr.reduce((a, x) => (a[fn(x)?0:1].push(x), a), [[],[]]);
console.log(partition([1,2,3,4,5], x => x%2===0));
```

**Output**
```text
[[2,4],[1,3,5]]
```


### 9. Zip two arrays (shortest length).

**Code**
```js
const zip = (a, b) => a.slice(0, Math.min(a.length, b.length)).map((x,i) => [x, b[i]]);
console.log(zip(['a','b','c'], [1,2]));
```

**Output**
```text
[["a",1],["b",2]]
```


### 10. Unzip pairs into arrays.

**Code**
```js
const unzip = (pairs) => pairs.reduce((acc,[x,y]) => (acc[0].push(x), acc[1].push(y), acc), [[],[]]);
console.log(unzip([["a",1],["b",2]]));
```

**Output**
```text
[["a","b"],[1,2]]
```


### 11. Deep equal (non-cyclic objects).

**Code**
```js
const isObject = x => x && typeof x === 'object';
const deepEqual = (a, b) => {
  if (a === b) return true;
  if (!isObject(a) || !isObject(b)) return false;
  const ka = Object.keys(a), kb = Object.keys(b);
  if (ka.length !== kb.length) return false;
  for (const k of ka) if (!deepEqual(a[k], b[k])) return false;
  return true;
};
console.log(deepEqual({x:1,y:{z:2}},{x:1,y:{z:2}}));
```

**Output**
```text
true
```


### 12. Top-K frequent elements.

**Code**
```js
const topK = (arr, k) => {
  const m = arr.reduce((o,x)=>(o[x]=(o[x]||0)+1,o),{});
  return Object.entries(m).sort((a,b)=>b[1]-a[1]).slice(0,k).map(([v])=>Number(v));
};
console.log(topK([1,1,1,2,2,3], 2));
```

**Output**
```text
[1,2]
```


### 13. Sliding window: longest substring without repeating characters.

**Code**
```js
const lengthOfLongestSubstring = s => {
  const idx = new Map(); let best = 0, start = 0;
  for (let i=0;i<s.length;i++) {
    if (idx.has(s[i]) && idx.get(s[i]) >= start) start = idx.get(s[i]) + 1;
    idx.set(s[i], i); best = Math.max(best, i - start + 1);
  }
  return best;
};
console.log(lengthOfLongestSubstring('abcabcbb'));
```

**Output**
```text
3
```


### 14. Two-pointer: container with most water (max area).

**Code**
```js
const maxArea = h => {
  let l = 0, r = h.length - 1, best = 0;
  while (l < r) {
    best = Math.max(best, Math.min(h[l], h[r]) * (r - l));
    if (h[l] < h[r]) l++; else r--;
  }
  return best;
};
console.log(maxArea([1,8,6,2,5,4,8,3,7]));
```

**Output**
```text
49
```


### 15. Merge overlapping intervals.

**Code**
```js
const merge = intervals => {
  intervals.sort((a,b)=>a[0]-b[0]);
  const res = [];
  for (const [s,e] of intervals) {
    if (!res.length || s > res[res.length-1][1]) res.push([s,e]);
    else res[res.length-1][1] = Math.max(res[res.length-1][1], e);
  }
  return res;
};
console.log(merge([[1,3],[2,6],[8,10],[15,18]]));
```

**Output**
```text
[[1,6],[8,10],[15,18]]
```


### 16. Array to object index by key (indexBy).

**Code**
```js
const indexBy = (arr, key) => arr.reduce((m,o)=> (m[o[key]] = o, m), {});
console.log(indexBy([{id:1,n:'a'},{id:2,n:'b'}], 'id'));
```

**Output**
```text
{"1":{"id":1,"n":"a"},"2":{"id":2,"n":"b"}}
```


### 17. Stable sort by multiple keys.

**Code**
```js
const sortBy = (arr, ...keys) => arr.slice().sort((a,b)=>{
  for (const [k, dir='asc'] of keys) {
    if (a[k] === b[k]) continue;
    return (a[k] < b[k] ? -1 : 1) * (dir==='asc'?1:-1);
  }
  return 0;
});
const data=[{n:'b',a:2},{n:'a',a:2},{n:'a',a:1}];
console.log(sortBy(data, ['a','asc'], ['n','asc']));
```

**Output**
```text
[{"n":"a","a":1},{"n":"a","a":2},{"n":"b","a":2}]
```


### 18. Curry and partial application.

**Code**
```js
const curry = fn => function curried(...a){ return a.length >= fn.length ? fn(...a) : (...b) => curried(...a,...b); };
const add3 = (a,b,c) => a + b + c;
console.log(curry(add3)(1)(2)(3));
```

**Output**
```text
6
```


### 19. Memoize sync function (by JSON key).

**Code**
```js
const memo = (fn) => {
  const cache = new Map();
  return (...args) => {
    const key = JSON.stringify(args);
    if (cache.has(key)) return cache.get(key);
    const v = fn(...args); cache.set(key, v); return v;
  };
};
const slow = (n) => { for (let i=0;i<1e6;i++); return n*n; };
const fast = memo(slow);
console.log(fast(9)); console.log(fast(9));
```

**Output**
```text
81
81
```


### 20. Once: ensure a function runs only once.

**Code**
```js
const once = (fn) => { let done = false, val; return (...a) => done ? val : (done = true, val = fn(...a)); };
const init = once(() => 'initialized');
console.log(init(), init());
```

**Output**
```text
initialized
initialized
```


### 21. Deep equal (non-cyclic objects).

**Code**
```js
const isObject = x => x && typeof x === 'object';
const deepEqual = (a, b) => {
  if (a === b) return true;
  if (!isObject(a) || !isObject(b)) return false;
  const ka = Object.keys(a), kb = Object.keys(b);
  if (ka.length !== kb.length) return false;
  for (const k of ka) if (!deepEqual(a[k], b[k])) return false;
  return true;
};
console.log(deepEqual({x:1,y:{z:2}},{x:1,y:{z:2}}));
```

**Output**
```text
true
```


### 22. Top-K frequent elements.

**Code**
```js
const topK = (arr, k) => {
  const m = arr.reduce((o,x)=>(o[x]=(o[x]||0)+1,o),{});
  return Object.entries(m).sort((a,b)=>b[1]-a[1]).slice(0,k).map(([v])=>Number(v));
};
console.log(topK([1,1,1,2,2,3], 2));
```

**Output**
```text
[1,2]
```


### 23. Sliding window: longest substring without repeating characters.

**Code**
```js
const lengthOfLongestSubstring = s => {
  const idx = new Map(); let best = 0, start = 0;
  for (let i=0;i<s.length;i++) {
    if (idx.has(s[i]) && idx.get(s[i]) >= start) start = idx.get(s[i]) + 1;
    idx.set(s[i], i); best = Math.max(best, i - start + 1);
  }
  return best;
};
console.log(lengthOfLongestSubstring('abcabcbb'));
```

**Output**
```text
3
```


### 24. Two-pointer: container with most water (max area).

**Code**
```js
const maxArea = h => {
  let l = 0, r = h.length - 1, best = 0;
  while (l < r) {
    best = Math.max(best, Math.min(h[l], h[r]) * (r - l));
    if (h[l] < h[r]) l++; else r--;
  }
  return best;
};
console.log(maxArea([1,8,6,2,5,4,8,3,7]));
```

**Output**
```text
49
```


### 25. Merge overlapping intervals.

**Code**
```js
const merge = intervals => {
  intervals.sort((a,b)=>a[0]-b[0]);
  const res = [];
  for (const [s,e] of intervals) {
    if (!res.length || s > res[res.length-1][1]) res.push([s,e]);
    else res[res.length-1][1] = Math.max(res[res.length-1][1], e);
  }
  return res;
};
console.log(merge([[1,3],[2,6],[8,10],[15,18]]));
```

**Output**
```text
[[1,6],[8,10],[15,18]]
```


### 26. Array to object index by key (indexBy).

**Code**
```js
const indexBy = (arr, key) => arr.reduce((m,o)=> (m[o[key]] = o, m), {});
console.log(indexBy([{id:1,n:'a'},{id:2,n:'b'}], 'id'));
```

**Output**
```text
{"1":{"id":1,"n":"a"},"2":{"id":2,"n":"b"}}
```


### 27. Stable sort by multiple keys.

**Code**
```js
const sortBy = (arr, ...keys) => arr.slice().sort((a,b)=>{
  for (const [k, dir='asc'] of keys) {
    if (a[k] === b[k]) continue;
    return (a[k] < b[k] ? -1 : 1) * (dir==='asc'?1:-1);
  }
  return 0;
});
const data=[{n:'b',a:2},{n:'a',a:2},{n:'a',a:1}];
console.log(sortBy(data, ['a','asc'], ['n','asc']));
```

**Output**
```text
[{"n":"a","a":1},{"n":"a","a":2},{"n":"b","a":2}]
```


### 28. Curry and partial application.

**Code**
```js
const curry = fn => function curried(...a){ return a.length >= fn.length ? fn(...a) : (...b) => curried(...a,...b); };
const add3 = (a,b,c) => a + b + c;
console.log(curry(add3)(1)(2)(3));
```

**Output**
```text
6
```


### 29. Memoize sync function (by JSON key).

**Code**
```js
const memo = (fn) => {
  const cache = new Map();
  return (...args) => {
    const key = JSON.stringify(args);
    if (cache.has(key)) return cache.get(key);
    const v = fn(...args); cache.set(key, v); return v;
  };
};
const slow = (n) => { for (let i=0;i<1e6;i++); return n*n; };
const fast = memo(slow);
console.log(fast(9)); console.log(fast(9));
```

**Output**
```text
81
81
```


### 30. Once: ensure a function runs only once.

**Code**
```js
const once = (fn) => { let done = false, val; return (...a) => done ? val : (done = true, val = fn(...a)); };
const init = once(() => 'initialized');
console.log(init(), init());
```

**Output**
```text
initialized
initialized
```


### 31. Deep equal (non-cyclic objects).

**Code**
```js
const isObject = x => x && typeof x === 'object';
const deepEqual = (a, b) => {
  if (a === b) return true;
  if (!isObject(a) || !isObject(b)) return false;
  const ka = Object.keys(a), kb = Object.keys(b);
  if (ka.length !== kb.length) return false;
  for (const k of ka) if (!deepEqual(a[k], b[k])) return false;
  return true;
};
console.log(deepEqual({x:1,y:{z:2}},{x:1,y:{z:2}}));
```

**Output**
```text
true
```


### 32. Top-K frequent elements.

**Code**
```js
const topK = (arr, k) => {
  const m = arr.reduce((o,x)=>(o[x]=(o[x]||0)+1,o),{});
  return Object.entries(m).sort((a,b)=>b[1]-a[1]).slice(0,k).map(([v])=>Number(v));
};
console.log(topK([1,1,1,2,2,3], 2));
```

**Output**
```text
[1,2]
```


### 33. Sliding window: longest substring without repeating characters.

**Code**
```js
const lengthOfLongestSubstring = s => {
  const idx = new Map(); let best = 0, start = 0;
  for (let i=0;i<s.length;i++) {
    if (idx.has(s[i]) && idx.get(s[i]) >= start) start = idx.get(s[i]) + 1;
    idx.set(s[i], i); best = Math.max(best, i - start + 1);
  }
  return best;
};
console.log(lengthOfLongestSubstring('abcabcbb'));
```

**Output**
```text
3
```


### 34. Two-pointer: container with most water (max area).

**Code**
```js
const maxArea = h => {
  let l = 0, r = h.length - 1, best = 0;
  while (l < r) {
    best = Math.max(best, Math.min(h[l], h[r]) * (r - l));
    if (h[l] < h[r]) l++; else r--;
  }
  return best;
};
console.log(maxArea([1,8,6,2,5,4,8,3,7]));
```

**Output**
```text
49
```


### 35. Merge overlapping intervals.

**Code**
```js
const merge = intervals => {
  intervals.sort((a,b)=>a[0]-b[0]);
  const res = [];
  for (const [s,e] of intervals) {
    if (!res.length || s > res[res.length-1][1]) res.push([s,e]);
    else res[res.length-1][1] = Math.max(res[res.length-1][1], e);
  }
  return res;
};
console.log(merge([[1,3],[2,6],[8,10],[15,18]]));
```

**Output**
```text
[[1,6],[8,10],[15,18]]
```


### 36. Array to object index by key (indexBy).

**Code**
```js
const indexBy = (arr, key) => arr.reduce((m,o)=> (m[o[key]] = o, m), {});
console.log(indexBy([{id:1,n:'a'},{id:2,n:'b'}], 'id'));
```

**Output**
```text
{"1":{"id":1,"n":"a"},"2":{"id":2,"n":"b"}}
```


### 37. Stable sort by multiple keys.

**Code**
```js
const sortBy = (arr, ...keys) => arr.slice().sort((a,b)=>{
  for (const [k, dir='asc'] of keys) {
    if (a[k] === b[k]) continue;
    return (a[k] < b[k] ? -1 : 1) * (dir==='asc'?1:-1);
  }
  return 0;
});
const data=[{n:'b',a:2},{n:'a',a:2},{n:'a',a:1}];
console.log(sortBy(data, ['a','asc'], ['n','asc']));
```

**Output**
```text
[{"n":"a","a":1},{"n":"a","a":2},{"n":"b","a":2}]
```


### 38. Curry and partial application.

**Code**
```js
const curry = fn => function curried(...a){ return a.length >= fn.length ? fn(...a) : (...b) => curried(...a,...b); };
const add3 = (a,b,c) => a + b + c;
console.log(curry(add3)(1)(2)(3));
```

**Output**
```text
6
```


### 39. Memoize sync function (by JSON key).

**Code**
```js
const memo = (fn) => {
  const cache = new Map();
  return (...args) => {
    const key = JSON.stringify(args);
    if (cache.has(key)) return cache.get(key);
    const v = fn(...args); cache.set(key, v); return v;
  };
};
const slow = (n) => { for (let i=0;i<1e6;i++); return n*n; };
const fast = memo(slow);
console.log(fast(9)); console.log(fast(9));
```

**Output**
```text
81
81
```


### 40. Once: ensure a function runs only once.

**Code**
```js
const once = (fn) => { let done = false, val; return (...a) => done ? val : (done = true, val = fn(...a)); };
const init = once(() => 'initialized');
console.log(init(), init());
```

**Output**
```text
initialized
initialized
```


### 41. Deep equal (non-cyclic objects).

**Code**
```js
const isObject = x => x && typeof x === 'object';
const deepEqual = (a, b) => {
  if (a === b) return true;
  if (!isObject(a) || !isObject(b)) return false;
  const ka = Object.keys(a), kb = Object.keys(b);
  if (ka.length !== kb.length) return false;
  for (const k of ka) if (!deepEqual(a[k], b[k])) return false;
  return true;
};
console.log(deepEqual({x:1,y:{z:2}},{x:1,y:{z:2}}));
```

**Output**
```text
true
```


### 42. Top-K frequent elements.

**Code**
```js
const topK = (arr, k) => {
  const m = arr.reduce((o,x)=>(o[x]=(o[x]||0)+1,o),{});
  return Object.entries(m).sort((a,b)=>b[1]-a[1]).slice(0,k).map(([v])=>Number(v));
};
console.log(topK([1,1,1,2,2,3], 2));
```

**Output**
```text
[1,2]
```


### 43. Sliding window: longest substring without repeating characters.

**Code**
```js
const lengthOfLongestSubstring = s => {
  const idx = new Map(); let best = 0, start = 0;
  for (let i=0;i<s.length;i++) {
    if (idx.has(s[i]) && idx.get(s[i]) >= start) start = idx.get(s[i]) + 1;
    idx.set(s[i], i); best = Math.max(best, i - start + 1);
  }
  return best;
};
console.log(lengthOfLongestSubstring('abcabcbb'));
```

**Output**
```text
3
```


### 44. Two-pointer: container with most water (max area).

**Code**
```js
const maxArea = h => {
  let l = 0, r = h.length - 1, best = 0;
  while (l < r) {
    best = Math.max(best, Math.min(h[l], h[r]) * (r - l));
    if (h[l] < h[r]) l++; else r--;
  }
  return best;
};
console.log(maxArea([1,8,6,2,5,4,8,3,7]));
```

**Output**
```text
49
```


### 45. Merge overlapping intervals.

**Code**
```js
const merge = intervals => {
  intervals.sort((a,b)=>a[0]-b[0]);
  const res = [];
  for (const [s,e] of intervals) {
    if (!res.length || s > res[res.length-1][1]) res.push([s,e]);
    else res[res.length-1][1] = Math.max(res[res.length-1][1], e);
  }
  return res;
};
console.log(merge([[1,3],[2,6],[8,10],[15,18]]));
```

**Output**
```text
[[1,6],[8,10],[15,18]]
```


### 46. Array to object index by key (indexBy).

**Code**
```js
const indexBy = (arr, key) => arr.reduce((m,o)=> (m[o[key]] = o, m), {});
console.log(indexBy([{id:1,n:'a'},{id:2,n:'b'}], 'id'));
```

**Output**
```text
{"1":{"id":1,"n":"a"},"2":{"id":2,"n":"b"}}
```


### 47. Stable sort by multiple keys.

**Code**
```js
const sortBy = (arr, ...keys) => arr.slice().sort((a,b)=>{
  for (const [k, dir='asc'] of keys) {
    if (a[k] === b[k]) continue;
    return (a[k] < b[k] ? -1 : 1) * (dir==='asc'?1:-1);
  }
  return 0;
});
const data=[{n:'b',a:2},{n:'a',a:2},{n:'a',a:1}];
console.log(sortBy(data, ['a','asc'], ['n','asc']));
```

**Output**
```text
[{"n":"a","a":1},{"n":"a","a":2},{"n":"b","a":2}]
```


### 48. Curry and partial application.

**Code**
```js
const curry = fn => function curried(...a){ return a.length >= fn.length ? fn(...a) : (...b) => curried(...a,...b); };
const add3 = (a,b,c) => a + b + c;
console.log(curry(add3)(1)(2)(3));
```

**Output**
```text
6
```


### 49. Memoize sync function (by JSON key).

**Code**
```js
const memo = (fn) => {
  const cache = new Map();
  return (...args) => {
    const key = JSON.stringify(args);
    if (cache.has(key)) return cache.get(key);
    const v = fn(...args); cache.set(key, v); return v;
  };
};
const slow = (n) => { for (let i=0;i<1e6;i++); return n*n; };
const fast = memo(slow);
console.log(fast(9)); console.log(fast(9));
```

**Output**
```text
81
81
```


### 50. Once: ensure a function runs only once.

**Code**
```js
const once = (fn) => { let done = false, val; return (...a) => done ? val : (done = true, val = fn(...a)); };
const init = once(() => 'initialized');
console.log(init(), init());
```

**Output**
```text
initialized
initialized
```


## Advanced (50) – Real-world utilities, concurrency, and internals


### 1. Event loop: microtasks before timers.

**Code**
```js
console.log('A');
setTimeout(() => console.log('timeout'), 0);
Promise.resolve().then(() => console.log('microtask'));
console.log('B');
```

**Output**
```text
A
B
microtask
timeout
```


### 2. Promise.any polyfill.

**Code**
```js
const promiseAny = (promises) => new Promise((resolve, reject) => {
  let count = 0, errs = [];
  promises.forEach((p, i) => Promise.resolve(p).then(resolve, e => { errs[i] = e; if (++count === promises.length) reject(new AggregateError(errs)); }));
});

promiseAny([Promise.reject('x'), Promise.resolve(42)]).then(console.log);
```

**Output**
```text
42
```


### 3. Promise.allSettled polyfill.

**Code**
```js
const allSettled = (ps) => Promise.all(ps.map(p => Promise.resolve(p)
  .then(value => ({ status: 'fulfilled', value }))
  .catch(reason => ({ status: 'rejected', reason }))));
allSettled([1, Promise.reject('x')]).then(console.log);
```

**Output**
```text
[{"status":"fulfilled","value":1},{"status":"rejected","reason":"x"}]
```


### 4. Timeout wrapper for promises.

**Code**
```js
const withTimeout = (p, ms) => new Promise((res, rej) => {
  const id = setTimeout(() => rej(Error('timeout')), ms);
  Promise.resolve(p).then(v => { clearTimeout(id); res(v); }, e => { clearTimeout(id); rej(e); });
});
withTimeout(new Promise(r => setTimeout(()=>r('ok'), 20)), 50).then(console.log);
```

**Output**
```text
ok
```


### 5. Retry with exponential backoff.

**Code**
```js
async function retry(fn, { retries = 3, base = 100 } = {}) {
  let attempt = 0; let lastErr;
  while (attempt < retries) {
    try { return await fn(); } catch (e) { lastErr = e; await new Promise(r => setTimeout(r, base * 2 ** attempt)); attempt++; }
  }
  throw lastErr;
}
let tries = 0; retry(() => (++tries < 2 ? Promise.reject('fail') : Promise.resolve('ok'))).then(console.log);
```

**Output**
```text
ok
```


### 6. Semaphore for concurrency control.

**Code**
```js
class Semaphore { constructor(n) { this.n = n; this.q = []; }
  async acquire() { if (this.n > 0) { this.n--; return; } await new Promise(r => this.q.push(r)); }
  release() { this.n++; if (this.q.length) { this.n--; this.q.shift()(); } }
}

const sem = new Semaphore(2);
const wait = (ms) => new Promise(r => setTimeout(r, ms));
(async () => {
  const work = (i) => (async () => { await sem.acquire(); console.log('start', i); await wait(50); console.log('end', i); sem.release(); })();
  await Promise.all([1,2,3,4].map(work));
})();
```

**Output**
```text
start 1
start 2
end 1
start 3
end 2
start 4
end 3
end 4
```


### 7. Async pool (mapLimit).

**Code**
```js
async function mapLimit(items, limit, fn) {
  const res = []; let i = 0; const running = new Set();
  async function launch() {
    if (i >= items.length) return;
    const idx = i++;
    const p = fn(items[idx], idx).then(v => { res[idx] = v; running.delete(p); });
    running.add(p);
    p.finally(launch);
  }
  const n = Math.min(limit, items.length);
  for (let k = 0; k < n; k++) await launch();
  await Promise.all([...running]);
  return res;
}

const wait = (ms) => new Promise(r => setTimeout(r, ms));
mapLimit([100,50,80,10], 2, ms => wait(ms).then(()=>ms)).then(console.log);
```

**Output**
```text
[100,50,80,10]
```


### 8. LRU cache (Map-based).

**Code**
```js
class LRU {
  constructor(limit = 3) { this.limit = limit; this.map = new Map(); }
  get(k) { if (!this.map.has(k)) return undefined; const v = this.map.get(k); this.map.delete(k); this.map.set(k, v); return v; }
  set(k, v) { if (this.map.has(k)) this.map.delete(k); this.map.set(k, v); if (this.map.size > this.limit) this.map.delete(this.map.keys().next().value); }
}
const lru = new LRU(2); lru.set('a',1); lru.set('b',2); lru.get('a'); lru.set('c',3); console.log([...lru.map.keys()]);
```

**Output**
```text
["a","c"]
```


### 9. Deep clone with cycles (WeakMap).

**Code**
```js
function deepClone(obj, seen = new WeakMap()) {
  if (obj === null || typeof obj !== 'object') return obj;
  if (seen.has(obj)) return seen.get(obj);
  const out = Array.isArray(obj) ? [] : {};
  seen.set(obj, out);
  for (const k of Object.keys(obj)) out[k] = deepClone(obj[k], seen);
  return out;
}
const a = { x: 1 }; a.self = a;
const b = deepClone(a);
console.log(b !== a, b.x, b.self === b);
```

**Output**
```text
true 1 true
```


### 10. Deep equal with cycles (WeakMap pairs).

**Code**
```js
function deepEqual(a, b, seen = new WeakMap()) {
  if (a === b) return true;
  if (a && b && typeof a === 'object' && typeof b === 'object') {
    const pair = seen.get(a);
    if (pair === b) return true; seen.set(a, b);
    const ka = Object.keys(a), kb = Object.keys(b);
    if (ka.length !== kb.length) return false;
    for (const k of ka) if (!deepEqual(a[k], b[k], seen)) return false;
    return true;
  }
  return false;
}
const x = { a: 1 }; x.self = x; const y = { a: 1 }; y.self = y;
console.log(deepEqual(x, y));
```

**Output**
```text
true
```


### 11. Priority queue via binary heap (min-heap).

**Code**
```js
class MinHeap {
  constructor(){ this.a = []; }
  push(v){ this.a.push(v); this.up(this.a.length-1); }
  up(i){ const a=this.a; while(i){ const p=(i-1)>>1; if(a[p] <= a[i]) break; [a[p],a[i]]=[a[i],a[p]]; i=p; } }
  pop(){ const a=this.a; if(!a.length) return; const v=a[0], last=a.pop(); if(a.length){ a[0]=last; this.down(0); } return v; }
  down(i){ const a=this.a; for(;;){ let l=i*2+1, r=l+1, s=i; if(l<a.length && a[l]<a[s]) s=l; if(r<a.length && a[r]<a[s]) s=r; if(s===i) break; [a[i],a[s]]=[a[s],a[i]]; i=s; } }
}
const h=new MinHeap(); [5,3,8,1].forEach(x=>h.push(x)); console.log(h.pop(), h.pop(), h.pop(), h.pop());
```

**Output**
```text
1 3 5 8
```


### 12. Topological sort (Kahn's algorithm).

**Code**
```js
function topoSort(edges){
  const g=new Map(), indeg=new Map();
  for(const [u,v] of edges){ (g.get(u)||g.set(u,[]).get(u)).push(v); indeg.set(v,(indeg.get(v)||0)+1); indeg.set(u,indeg.get(u)||0); }
  const q=[...indeg].filter(([,d])=>d===0).map(([k])=>k), res=[];
  for(let i=0;i<q.length;i++){ const u=q[i]; res.push(u); for(const v of (g.get(u)||[])){ indeg.set(v, indeg.get(v)-1); if(indeg.get(v)===0) q.push(v); } }
  return res.length===indeg.size?res:[];
}
console.log(topoSort([["a","b"],["a","c"],["b","d"],["c","d"]]));
```

**Output**
```text
["a","b","c","d"]
```


### 13. Trie (prefix tree): insert & search.

**Code**
```js
class Trie {
  constructor(){ this.root = {}; }
  insert(w){ let n=this.root; for(const c of w) n=n[c]||(n[c]={}); n.$=1; }
  search(w){ let n=this.root; for(const c of w){ if(!n[c]) return false; n=n[c]; } return !!n.$; }
}
const t=new Trie(); t.insert('cat'); t.insert('car'); console.log(t.search('car'), t.search('cap'));
```

**Output**
```text
true false
```


### 14. Dijkstra (small graph).

**Code**
```js
function dijkstra(g, s){
  const dist={}, vis=new Set(); for(const k in g) dist[k]=Infinity; dist[s]=0;
  while(true){ let u=null, best=Infinity; for(const k in dist) if(!vis.has(k)&&dist[k]<best){best=dist[k];u=k;}
    if(u===null) break; vis.add(u);
    for(const [v,w] of g[u]) if(dist[u]+w<dist[v]) dist[v]=dist[u]+w;
  } return dist; }
const g={A:[['B',1],['C',4]],B:[['C',2],['D',5]],C:[['D',1]],D:[]};
console.log(dijkstra(g,'A'));
```

**Output**
```text
{"A":0,"B":1,"C":3,"D":4}
```


### 15. EventEmitter (on/off/emit once).

**Code**
```js
class Emitter{
  constructor(){ this.m=new Map(); }
  on(t,f){ const s=this.m.get(t)||new Set(); s.add(f); this.m.set(t,s); return () => s.delete(f); }
  once(t,f){ const off=this.on(t,(...a)=>{ off(); f(...a); }); }
  emit(t,...a){ (this.m.get(t)||[]).forEach(fn=>fn(...a)); }
}
const bus=new Emitter(); bus.once('ready',x=>console.log('ready',x)); bus.emit('ready',1); bus.emit('ready',2);
```

**Output**
```text
ready 1
```


### 16. Pattern matching (poor-man) using object of handlers.

**Code**
```js
const match = (value, cases, def) => (value in cases ? cases[value] : def)();
console.log(match('OK', { OK: ()=>'200', FAIL: ()=>'500' }, ()=>'default'));
```

**Output**
```text
200
```


### 17. Router (hash-based).

**Code**
```js
const routes = { '#/': ()=>'Home', '#/about': ()=>'About', _404: ()=>'Not Found' };
const render = () => console.log((routes[location.hash]||routes._404)());
addEventListener('hashchange', render);
console.log('Ready'); // change location.hash manually
```

**Output**
```text
Ready
```


### 18. Abortable fetch via AbortController (sketch).

**Code**
```js
const controller = new AbortController();
const { signal } = controller;
setTimeout(()=>controller.abort(), 10);
fetch('https://example.com', { signal }).then(r=>r.text()).then(console.log).catch(e=>console.log('aborted'));
```

**Output**
```text
aborted
```


### 19. Pipeline: compose async/sync steps.

**Code**
```js
const pipe = (...fns) => (x) => fns.reduce((p, f) => Promise.resolve(p).then(f), x);
const step1 = x => x + 1; const step2 = async x => x * 2; const step3 = x => `v=${x}`;
pipe(step1, step2, step3)(2).then(console.log);
```

**Output**
```text
v=6
```


### 20. Immutable update of nested object (path set).

**Code**
```js
const setPath = (obj, path, val) => {
  const keys = Array.isArray(path)?path:path.split('.');
  return keys.reduceRight((acc, k, i) => ({ [k]: i ? acc : val }), {});
};
const merge = (a, b) => ({ ...a, ...Object.fromEntries(Object.keys(b).map(k => [k, typeof a[k]==='object'&&typeof b[k]==='object'?merge(a[k],b[k]):b[k]])) });
const state = { user:{ profile:{ name:'Ada' } } };
const patch = setPath(state, 'user.profile.name', 'Lovelace');
console.log(merge(state, patch));
```

**Output**
```text
{"user":{"profile":{"name":"Lovelace"}}}
```


### 21. JSON diff (shallow keys).

**Code**
```js
const diff = (a,b) => {
  const keys = new Set([...Object.keys(a), ...Object.keys(b)]);
  const out = {};
  for (const k of keys) if (JSON.stringify(a[k]) !== JSON.stringify(b[k])) out[k] = { from: a[k], to: b[k] };
  return out;
};
console.log(diff({a:1,b:2},{a:1,b:3,c:4}));
```

**Output**
```text
{"b":{"from":2,"to":3},"c":{"from":undefined,"to":4}}
```


### 22. Batching microtasks with queueMicrotask.

**Code**
```js
console.log('A'); queueMicrotask(()=>console.log('micro')); console.log('B');
```

**Output**
```text
A
B
micro
```


### 23. Promise.all with mapLimit semantics (concurrency 2).

**Code**
```js
const wait = (ms) => new Promise(r => setTimeout(r, ms));
async function allLimit(tasks, limit = 2) {
  const res = []; let i = 0; const running = new Set();
  function launch(){ if (i >= tasks.length) return; const idx = i++; const p = tasks[idx]().then(v => { res[idx]=v; running.delete(p); }); running.add(p); p.finally(launch); }
  for (let k=0;k<Math.min(limit,tasks.length);k++) launch();
  await Promise.all([...running]);
  return res;
}
allLimit([() => wait(30).then(()=>1), () => wait(10).then(()=>2), () => wait(20).then(()=>3)]).then(console.log);
```

**Output**
```text
[1,2,3]
```


### 24. Token bucket rate limiter (async).

**Code**
```js
class TokenBucket { constructor(rate, burst){ this.rate=rate; this.capacity=burst; this.tokens=burst; this.last=Date.now(); }
  async remove(n=1){ while(true){ const now=Date.now(); const delta=(now-this.last)/1000; this.last=now; this.tokens=Math.min(this.capacity,this.tokens+delta*this.rate); if(this.tokens>=n){ this.tokens-=n; return; } await new Promise(r=>setTimeout(r,10)); } } }
const bucket=new TokenBucket(5,5);
(async()=>{ for(let i=0;i<8;i++){ await bucket.remove(); console.log('call',i); } })();
```

**Output**
```text
call 0
call 1
call 2
call 3
call 4
call 5
call 6
call 7
```


### 25. Scheduler by priority using MinHeap.

**Code**
```js
class MinHeap{constructor(){this.a=[]} push(v){this.a.push(v);this.up(this.a.length-1)} up(i){const a=this.a;while(i){const p=(i-1)>>1;if(a[p].p<=a[i].p)break;[a[p],a[i]]=[a[i],a[p]];i=p}} pop(){const a=this.a;if(!a.length)return;const v=a[0],last=a.pop();if(a.length){a[0]=last;this.down(0)}return v} down(i){const a=this.a;for(;;){let l=i*2+1,r=l+1,s=i;if(l<a.length&&a[l].p<a[s].p)s=l;if(r<a.length&&a[r].p<a[s].p)s=r;if(s===i)break;[a[i],a[s]]=[a[s],a[i]];i=s}}}
const q=new MinHeap(); q.push({p:2,job:'B'}); q.push({p:1,job:'A'}); q.push({p:3,job:'C'});
console.log(q.pop().job, q.pop().job, q.pop().job);
```

**Output**
```text
A B C
```


### 26. Immutable array operations (insert/remove/update).

**Code**
```js
const insertAt = (arr, i, v) => [...arr.slice(0,i), v, ...arr.slice(i)];
const removeAt = (arr, i) => [...arr.slice(0,i), ...arr.slice(i+1)];
const updateAt = (arr, i, v) => arr.map((x,idx)=> idx===i ? v : x);
console.log(insertAt([1,2,3],1,9), removeAt([1,2,3],1), updateAt([1,2,3],1,9));
```

**Output**
```text
[1,9,2,3] [1,3] [1,9,3]
```


### 27. Event delegation utility.

**Code**
```js
function delegate(root, type, selector, handler){
  root.addEventListener(type, e => { const t = e.target.closest(selector); if (t && root.contains(t)) handler(e, t); });
}
console.log('delegate attached');
```

**Output**
```text
delegate attached
```


### 28. Virtualized list concept (windowing indices).

**Code**
```js
const getWindow = (total, itemH, viewH, scroll) => {
  const start = Math.floor(scroll / itemH);
  const visible = Math.ceil(viewH / itemH);
  return { start, end: Math.min(total - 1, start + visible) };
};
console.log(getWindow(1000, 20, 300, 180));
```

**Output**
```text
{"start":9,"end":24}
```


### 29. Simple parser: evaluate + and * (left-to-right).

**Code**
```js
function evalExpr(s){
  const tokens = s.match(/\d+|[+*]/g);
  let acc = Number(tokens[0]);
  for (let i=1;i<tokens.length;i+=2){ const op=tokens[i], v=Number(tokens[i+1]); acc = op==='+' ? acc+v : acc*v; }
  return acc;
}
console.log(evalExpr('2+3*4+5'));
```

**Output**
```text
25
```


### 30. Small reactive store (subscribe & set).

**Code**
```js
function createStore(state){
  const subs=new Set();
  return {
    get: ()=>state,
    set: (patch)=>{ state = { ...state, ...patch }; subs.forEach(fn=>fn(state)); },
    subscribe: (fn)=> (subs.add(fn), ()=>subs.delete(fn))
  };
}
const store=createStore({count:0});
const off=store.subscribe(s=>console.log('state',s.count));
store.set({count:1}); off(); store.set({count:2});
```

**Output**
```text
state 1
```


### 31. Transducer-like pipeline (map then filter in one pass).

**Code**
```js
const transduce = (mapFn, filterFn, arr) => {
  const out = [];
  for (const x of arr) { const y = mapFn(x); if (filterFn(y)) out.push(y); }
  return out;
};
console.log(transduce(x=>x*x, y=>y%2===0, [1,2,3,4]));
```

**Output**
```text
[4,16]
```


### 32. Safe HTML tagged template (escape).

**Code**
```js
const escape = s => s.replace(/[&<>"']/g, c => ({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
function html(strings, ...vals){ return strings.reduce((a,s,i)=> a + s + (i<vals.length?escape(String(vals[i])):''), ''); }
const user = '<img onerror=1>';
console.log(html`<p>${user}</p>`);
```

**Output**
```text
<p>&lt;img onerror=1&gt;</p>
```


### 33. Immutable sorted insertion (binary search).

**Code**
```js
function insertSorted(arr, x){
  let l=0,r=arr.length; while(l<r){ const m=(l+r)>>1; if(arr[m]<x) l=m+1; else r=m; }
  return [...arr.slice(0,l), x, ...arr.slice(l)];
}
console.log(insertSorted([1,3,5,9], 7));
```

**Output**
```text
[1,3,5,7,9]
```


### 34. Batching microtasks with queueMicrotask.

**Code**
```js
console.log('A'); queueMicrotask(()=>console.log('micro')); console.log('B');
```

**Output**
```text
A
B
micro
```


### 35. Promise.all with mapLimit semantics (concurrency 2).

**Code**
```js
const wait = (ms) => new Promise(r => setTimeout(r, ms));
async function allLimit(tasks, limit = 2) {
  const res = []; let i = 0; const running = new Set();
  function launch(){ if (i >= tasks.length) return; const idx = i++; const p = tasks[idx]().then(v => { res[idx]=v; running.delete(p); }); running.add(p); p.finally(launch); }
  for (let k=0;k<Math.min(limit,tasks.length);k++) launch();
  await Promise.all([...running]);
  return res;
}
allLimit([() => wait(30).then(()=>1), () => wait(10).then(()=>2), () => wait(20).then(()=>3)]).then(console.log);
```

**Output**
```text
[1,2,3]
```


### 36. Token bucket rate limiter (async).

**Code**
```js
class TokenBucket { constructor(rate, burst){ this.rate=rate; this.capacity=burst; this.tokens=burst; this.last=Date.now(); }
  async remove(n=1){ while(true){ const now=Date.now(); const delta=(now-this.last)/1000; this.last=now; this.tokens=Math.min(this.capacity,this.tokens+delta*this.rate); if(this.tokens>=n){ this.tokens-=n; return; } await new Promise(r=>setTimeout(r,10)); } } }
const bucket=new TokenBucket(5,5);
(async()=>{ for(let i=0;i<8;i++){ await bucket.remove(); console.log('call',i); } })();
```

**Output**
```text
call 0
call 1
call 2
call 3
call 4
call 5
call 6
call 7
```


### 37. Scheduler by priority using MinHeap.

**Code**
```js
class MinHeap{constructor(){this.a=[]} push(v){this.a.push(v);this.up(this.a.length-1)} up(i){const a=this.a;while(i){const p=(i-1)>>1;if(a[p].p<=a[i].p)break;[a[p],a[i]]=[a[i],a[p]];i=p}} pop(){const a=this.a;if(!a.length)return;const v=a[0],last=a.pop();if(a.length){a[0]=last;this.down(0)}return v} down(i){const a=this.a;for(;;){let l=i*2+1,r=l+1,s=i;if(l<a.length&&a[l].p<a[s].p)s=l;if(r<a.length&&a[r].p<a[s].p)s=r;if(s===i)break;[a[i],a[s]]=[a[s],a[i]];i=s}}}
const q=new MinHeap(); q.push({p:2,job:'B'}); q.push({p:1,job:'A'}); q.push({p:3,job:'C'});
console.log(q.pop().job, q.pop().job, q.pop().job);
```

**Output**
```text
A B C
```


### 38. Immutable array operations (insert/remove/update).

**Code**
```js
const insertAt = (arr, i, v) => [...arr.slice(0,i), v, ...arr.slice(i)];
const removeAt = (arr, i) => [...arr.slice(0,i), ...arr.slice(i+1)];
const updateAt = (arr, i, v) => arr.map((x,idx)=> idx===i ? v : x);
console.log(insertAt([1,2,3],1,9), removeAt([1,2,3],1), updateAt([1,2,3],1,9));
```

**Output**
```text
[1,9,2,3] [1,3] [1,9,3]
```


### 39. Event delegation utility.

**Code**
```js
function delegate(root, type, selector, handler){
  root.addEventListener(type, e => { const t = e.target.closest(selector); if (t && root.contains(t)) handler(e, t); });
}
console.log('delegate attached');
```

**Output**
```text
delegate attached
```


### 40. Virtualized list concept (windowing indices).

**Code**
```js
const getWindow = (total, itemH, viewH, scroll) => {
  const start = Math.floor(scroll / itemH);
  const visible = Math.ceil(viewH / itemH);
  return { start, end: Math.min(total - 1, start + visible) };
};
console.log(getWindow(1000, 20, 300, 180));
```

**Output**
```text
{"start":9,"end":24}
```


### 41. Simple parser: evaluate + and * (left-to-right).

**Code**
```js
function evalExpr(s){
  const tokens = s.match(/\d+|[+*]/g);
  let acc = Number(tokens[0]);
  for (let i=1;i<tokens.length;i+=2){ const op=tokens[i], v=Number(tokens[i+1]); acc = op==='+' ? acc+v : acc*v; }
  return acc;
}
console.log(evalExpr('2+3*4+5'));
```

**Output**
```text
25
```


### 42. Small reactive store (subscribe & set).

**Code**
```js
function createStore(state){
  const subs=new Set();
  return {
    get: ()=>state,
    set: (patch)=>{ state = { ...state, ...patch }; subs.forEach(fn=>fn(state)); },
    subscribe: (fn)=> (subs.add(fn), ()=>subs.delete(fn))
  };
}
const store=createStore({count:0});
const off=store.subscribe(s=>console.log('state',s.count));
store.set({count:1}); off(); store.set({count:2});
```

**Output**
```text
state 1
```


### 43. Transducer-like pipeline (map then filter in one pass).

**Code**
```js
const transduce = (mapFn, filterFn, arr) => {
  const out = [];
  for (const x of arr) { const y = mapFn(x); if (filterFn(y)) out.push(y); }
  return out;
};
console.log(transduce(x=>x*x, y=>y%2===0, [1,2,3,4]));
```

**Output**
```text
[4,16]
```


### 44. Safe HTML tagged template (escape).

**Code**
```js
const escape = s => s.replace(/[&<>"']/g, c => ({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
function html(strings, ...vals){ return strings.reduce((a,s,i)=> a + s + (i<vals.length?escape(String(vals[i])):''), ''); }
const user = '<img onerror=1>';
console.log(html`<p>${user}</p>`);
```

**Output**
```text
<p>&lt;img onerror=1&gt;</p>
```


### 45. Immutable sorted insertion (binary search).

**Code**
```js
function insertSorted(arr, x){
  let l=0,r=arr.length; while(l<r){ const m=(l+r)>>1; if(arr[m]<x) l=m+1; else r=m; }
  return [...arr.slice(0,l), x, ...arr.slice(l)];
}
console.log(insertSorted([1,3,5,9], 7));
```

**Output**
```text
[1,3,5,7,9]
```


### 46. Batching microtasks with queueMicrotask.

**Code**
```js
console.log('A'); queueMicrotask(()=>console.log('micro')); console.log('B');
```

**Output**
```text
A
B
micro
```


### 47. Promise.all with mapLimit semantics (concurrency 2).

**Code**
```js
const wait = (ms) => new Promise(r => setTimeout(r, ms));
async function allLimit(tasks, limit = 2) {
  const res = []; let i = 0; const running = new Set();
  function launch(){ if (i >= tasks.length) return; const idx = i++; const p = tasks[idx]().then(v => { res[idx]=v; running.delete(p); }); running.add(p); p.finally(launch); }
  for (let k=0;k<Math.min(limit,tasks.length);k++) launch();
  await Promise.all([...running]);
  return res;
}
allLimit([() => wait(30).then(()=>1), () => wait(10).then(()=>2), () => wait(20).then(()=>3)]).then(console.log);
```

**Output**
```text
[1,2,3]
```


### 48. Token bucket rate limiter (async).

**Code**
```js
class TokenBucket { constructor(rate, burst){ this.rate=rate; this.capacity=burst; this.tokens=burst; this.last=Date.now(); }
  async remove(n=1){ while(true){ const now=Date.now(); const delta=(now-this.last)/1000; this.last=now; this.tokens=Math.min(this.capacity,this.tokens+delta*this.rate); if(this.tokens>=n){ this.tokens-=n; return; } await new Promise(r=>setTimeout(r,10)); } } }
const bucket=new TokenBucket(5,5);
(async()=>{ for(let i=0;i<8;i++){ await bucket.remove(); console.log('call',i); } })();
```

**Output**
```text
call 0
call 1
call 2
call 3
call 4
call 5
call 6
call 7
```


### 49. Scheduler by priority using MinHeap.

**Code**
```js
class MinHeap{constructor(){this.a=[]} push(v){this.a.push(v);this.up(this.a.length-1)} up(i){const a=this.a;while(i){const p=(i-1)>>1;if(a[p].p<=a[i].p)break;[a[p],a[i]]=[a[i],a[p]];i=p}} pop(){const a=this.a;if(!a.length)return;const v=a[0],last=a.pop();if(a.length){a[0]=last;this.down(0)}return v} down(i){const a=this.a;for(;;){let l=i*2+1,r=l+1,s=i;if(l<a.length&&a[l].p<a[s].p)s=l;if(r<a.length&&a[r].p<a[s].p)s=r;if(s===i)break;[a[i],a[s]]=[a[s],a[i]];i=s}}}
const q=new MinHeap(); q.push({p:2,job:'B'}); q.push({p:1,job:'A'}); q.push({p:3,job:'C'});
console.log(q.pop().job, q.pop().job, q.pop().job);
```

**Output**
```text
A B C
```


### 50. Immutable array operations (insert/remove/update).

**Code**
```js
const insertAt = (arr, i, v) => [...arr.slice(0,i), v, ...arr.slice(i)];
const removeAt = (arr, i) => [...arr.slice(0,i), ...arr.slice(i+1)];
const updateAt = (arr, i, v) => arr.map((x,idx)=> idx===i ? v : x);
console.log(insertAt([1,2,3],1,9), removeAt([1,2,3],1), updateAt([1,2,3],1,9));
```

**Output**
```text
[1,9,2,3] [1,3] [1,9,3]
```
