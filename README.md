# Still Standing

**AppADay #007 · Category: A — AI-Powered Tools**

A personal encouragement app. Type what is weighing on your heart, press the button, and receive a word of warmth and strength drawn from a curated library of 100 messages — each paired with a scripture verse. The input and response occupy the same space and flip like a physical card.

---

## What It Does

Still Standing accepts a short personal reflection and responds with an encouragement message selected from 100 hand-written entries covering themes of grief, loss, job transition, identity, resilience, rest, and hope. Each message is paired with a supporting scripture verse. The app never repeats the same message twice in a row and offers a "Draw another word" option to receive a second message without re-entering your reflection.

---

## How to Use

1. Type what is weighing on you into the text field — no right words required.
2. Press **Receive a word of encouragement**.
3. The card flips to reveal your message and scripture.
4. Press **Draw another word** to receive a different message.
5. Press **Share something else** to flip back and start over.

---

## Technical Notes

- Vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies, no API key required.
- 100 curated encouragement messages stored as a JavaScript array with paired scripture references.
- Card flip implemented with CSS `perspective` / `transform-style: preserve-3d` / `rotateY` — no JavaScript animation libraries.
- Fully self-contained single `index.html`. Works offline once loaded.
- Fonts loaded from Google Fonts: Cormorant Garamond and Jost.
- Responsive and usable at 375px viewport width.

---

## Stack

| Layer | Choice |
|---|---|
| Markup | HTML5 |
| Styles | CSS3 (custom properties, 3D transforms, keyframe animations) |
| Logic | Vanilla JavaScript (ES5-compatible) |
| Fonts | Google Fonts — Cormorant Garamond, Jost |
| Hosting | GitHub Pages |

---

## Definition of Complete

- [x] Functional — draws a non-repeating message on every button press without errors
- [x] Single purpose — one describable job: receive a word of encouragement
- [x] Mobile friendly — usable at 375px, tap targets sized correctly, no horizontal scroll
- [x] Visually polished — candlelit dark aesthetic, intentional typography, consistent visual language
- [x] Published — live at [augustineiacopelli.github.io/appaday-007-still-standing](https://augustineiacopelli.github.io/appaday-007-still-standing)

---

## Log Entry

```
007 2026-05-13 A Still Standing | augustineiacopelli.github.io/appaday-007-still-standing
```

---

*AppADay by Augustine Iacopelli — one complete app, every day, no exceptions.*
