# Reading Friction Tracker

A single-file, no-dependency web activity for digital media studies students. Students mark moments of **friction** in a reading — confusion, agreement, skepticism, connection, importance, or a need for an example — respond to a short metacognitive prompt for each, and generate a copyable reflection summary describing how their thinking changed.

Created by **Marc Watkins**, University of Mississippi. Licensed **CC BY 4.0**.

## Features

- Select any text in the reading and tag it with **one or more** kinds of friction at once (mouse drag or press-and-hold on touch), then "Add to log."
- Each label on a passage opens its own tailored metacognitive reflection prompt.
- A live **synthesis matrix** lays every tagged passage against the six friction types, surfacing overlaps and reading habits to draw on while writing the reflection.
- Use the built-in sample reading or paste your own assigned text.
- Wrap-up synthesis questions about how your thinking changed.
- A **visual report** (friction snapshot, distribution chart, matrix, passage cards, and reflections) that students can **Save as PDF** or **Download as a self-contained .html web page** to upload to the Blackboard assignment — so instructors see a formatted, visual submission, not just text.
- A collapsible plain-text version is still available for copy/paste.
- No data storage, no tracking, no external libraries, no network calls. Everything runs in the browser tab.
- Clean, mobile-friendly, keyboard-accessible, high-contrast design in University of Mississippi colors.

## Use it

Just open `index.html` in any modern browser. That's the whole app.

## Host it on GitHub Pages

1. Create a new repository and add `index.html` (this file, `README.md`, and `LICENSE` are optional extras).
2. Push to the `main` branch.
3. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / `root` → Save.**
4. After a minute, your activity is live at `https://<your-username>.github.io/<repo-name>/`.

## Add it to Blackboard

**Link (recommended):** In a Content area, choose **Build Content → Web Link**, paste your GitHub Pages URL, and set it to open in a new window.

**Embed:** In the content editor, switch to the HTML/source view and paste:

```html
<iframe src="https://<your-username>.github.io/<repo-name>/"
        title="Reading Friction Tracker" width="100%" height="900"
        style="border:1px solid #ccc;border-radius:8px"></iframe>
```

Because the activity stores nothing, each student's work lives only in their own tab — they must copy their summary out before closing it.

## Privacy

No analytics, cookies, local storage, or server requests. Nothing students type ever leaves their device.

## License

This work is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You may share and adapt it, including for commercial purposes, with attribution to Marc Watkins, University of Mississippi.

## AI disclosure

This activity was developed by Marc Watkins with the assistance of a generative AI tool, which helped draft and structure the HTML, CSS, and JavaScript. All pedagogical design choices, prompts, and final review are the author's. The activity contains no AI features and transmits no student data.
