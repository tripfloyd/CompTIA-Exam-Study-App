# CompTIA A+ Study App

This is the app version of a project I made to study for the CompTIA A+. It is public so that I can keep it as a browser-accessible homescreen app on my phone. 

A self-contained, single-file study tool for the CompTIA A+ exam, built in the style of Quizlet's "Learn" mode — plus a timed practice exam mode that simulates the real test, and a custom mixed-review mode for keeping older material fresh.

- **Core 1** — 22 practice tests + 8 acronym quizzes
- **Core 2** — 34 practice tests + 8 acronym quizzes
- **Practice Exam** — 90 randomized questions, 90-minute timer, scoped to whichever core you pick (Core 1 and Core 2 are separate exams, so each gets its own practice exam pulling only from that core's practice tests)
- **Custom Practice Test** — pick any combination of tests you've already studied and get a random 50-question mix pulled from just those, so you can review recent material without losing time on tests you haven't reached yet
- Over 1,800 questions total, each with a full explanation

Built to hold more than one certification down the line — right now "CompTIA A+" is the only option at the top level, but the structure supports adding others later.

## How it works

**Study mode (Core 1 / Core 2):**
1. Pick **CompTIA A+**
2. Pick **Core 1** or **Core 2**
3. Pick **Practice Tests** or **Acronym Quizzes**
4. Pick the specific test/quiz you want to study
5. Answer questions one at a time — get it right **twice in a row** and it's marked mastered and drops out of rotation
6. Get it wrong (or hit **"I don't know"**) and it resets, then comes back around a few questions later so you keep drilling your weak spots

Progress resets each time you reopen the file — it's meant for a single focused study session, not long-term tracking.

**Custom Practice Test mode:**
1. Pick **CompTIA A+** → **Core 1** or **Core 2** → **Custom Practice Test**
2. Check off any tests you want questions pulled from (e.g. the last 5 tests you've studied)
3. Hit **Generate practice set** — you'll get a random 50-question mix drawn only from your selected tests (fewer if your selection has less than 50 questions total)
4. Study it the same way as any other set: mastery tracking, requeueing, and the "I don't know" button all work the same

**Practice Exam mode:**
1. Pick **CompTIA A+** → **Practice Exam**
2. Pick **Core 1** or **Core 2** (each is simulated separately, matching how the real exams are taken)
3. Read the rules, then start
4. Answer 90 randomly selected questions (from that core's practice tests only — quizzes aren't included) in any order, with a live 90-minute countdown
5. No feedback while the exam is in progress, just like the real thing — the timer turns red under 5 minutes and **auto-submits at 0:00**
6. On submit, see your score, percentage, and a full review of every question you missed with the correct answer and explanation

## How to use it

No installation, no dependencies, no build step required.

**Option 1 — Download and open locally**
1. Click `aplus_study.html` in this repo
2. Click the **Download raw file** button (or **Raw** → save the page)
3. Double-click the downloaded file to open it in your browser

**Option 2 — Open it live in the browser (GitHub Pages)**
If this repo has GitHub Pages enabled, you can just visit:
```
https://<your-username>.github.io/<repo-name>/aplus_study.html
```
No download needed — it runs directly in the browser.

## Notes

- Works in any modern browser (Chrome, Edge, Firefox, Safari)
- All data is embedded in the single HTML file — nothing is loaded from external servers
- Feel free to fork this and add your own tests/quizzes, or another certification entirely, by editing the question bank inside the file
