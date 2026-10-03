# Every prompt from the video

These are the exact prompts typed into Claude Code (v2.1.287) to build this website, in order.
No code was written by hand.

## Lesson 2 · Install it and open your project

```bash
curl -fsSL https://claude.ai/install.sh | bash      # macOS, Linux, WSL (Windows: see code.claude.com/docs/en/quickstart)
claude --version
mkdir marigold && cd marigold
claude
```

## Lesson 3 · Plan before you build (Shift+Tab until "plan mode on")

> I run a small neighborhood bakery called Marigold Bakery. I want a website for it, but I don't know how to code. It needs a home page, our menu with prices, an about page with our story, and a contact page with opening hours and our address. Keep it simple: plain files I can open in a browser, no build tools. Ask me anything you need before you start.

Answers to Claude's questions: Warm and cozy · Use placeholders · Phone and email + Map link · No photos for now.
Then: "Yes, and use auto mode".

## Lesson 4 · Make it beautiful

```
/plugin install frontend-design@claude-plugins-official      (project scope)
```

> Now make it beautiful. Redesign the whole site so it feels like a real, special neighborhood bakery, not a template. Keep the four pages and the same content, and keep it plain files with no build tools.

## Lesson 5 · Let Claude see your site

```bash
claude mcp add playwright --scope project -- npx @playwright/mcp@latest --browser chromium --headless
claude --continue
```

> My site is running at http://localhost:8088. Open it in the browser and look at every page the way a customer would, on a phone and on a laptop. Take screenshots, tell me what looks off, and fix it.

(To serve the folder locally: `python3 -m http.server 8088`, or just double-click index.html.)

## Lesson 6 · Change anything, safely

> Add a new page called Custom Cakes. Show three cake styles we make for birthdays and weddings, with a starting price for each, and a button that emails us to order. Add it to the menu bar on every page.

> Yes, on a phone the menu bar should fit on one line. Fix that and check it in the browser.

> What would the whole site look like in pink and lavender instead of green and gold? Try it.

> Nice, but I'll keep green and gold. Delete the pink preview.

> I love it. Save this version with git so I can always come back to it.

> Change the big headline on the home page to: Baked before the sun comes up.

Then Esc Esc → Rewind → "Restore code and conversation".

> How could I put this site online? Just explain my options in plain English. Don't change anything yet.
