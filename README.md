# Are You Cooked? 🧠
> A Gen Z slang quiz for people who might be a little… boomer.

## How to Play
Pick 5 or 10 rounds, guess the correct meaning of each Gen Z slang word, and find out if you're cooked or lowkey a legend.

---

## Deploy in 2 Minutes (No Tech Skills Required)

1. Go to **[app.netlify.com/drop](https://app.netlify.com/drop)** in your browser
2. Drag the `index.html` file onto the page
3. Netlify gives you a free public link (e.g. `sunny-gecko-123.netlify.app`)
4. Share the link — it works on any phone, tablet, or computer

That's it. No sign-up required for a basic deploy. Optional: create a free Netlify account to get a custom link or update the file later.

---

## Want to Change the Questions?

Open `index.html` in any text editor (Notepad on Windows, TextEdit on Mac).
Find the `ALL_QUESTIONS` array near the top of the `<script>` section and edit away.

Each question looks like this:
```js
{
  word: "Slay",
  context: "\"She absolutely slayed that presentation.\"",
  correct: "To perform amazingly or look incredible",
  wrong: ["To attack with a sword", "A ride on a horse-drawn sleigh", "To take a very long nap"]
},
```

---

## What's In the Box

| File | What it does |
|---|---|
| `index.html` | The entire game — layout, styles, logic, and questions |
| `README.md` | This file |
