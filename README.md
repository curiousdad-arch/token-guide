# Tokens: The Currency Your AI Runs On

An interactive, single-page explainer that teaches non-technical senior leaders what AI tokens are, where they get consumed, what they cost, and how to manage that cost.

Built as one self-contained `index.html` file — no build step, no dependencies to install, no server-side code. Just open it in a browser.

## What's inside

The page walks through five ideas, in order:

1. **What a token is** — an interactive demo: type a prompt and watch it break into tokens in real time.
2. **Where tokens get used** — a clean input-vs-output breakdown, with the key insight that output (the AI's reply) is the pricier side, usually several times the cost of input per token.
3. **What it costs** — a live calculator. Adjust team size, usage, and model, and see an estimated monthly bill. Numbers are illustrative and clearly tagged as an example.
4. **Model comparison** — a reference table of current per-million-token prices across common models (Anthropic, OpenAI, Google).
5. **Two kinds of savings** — practical levers to manage cost, split into habits anyone can adopt today and infrastructure controls worth building once. Ordered by impact.

## Viewing it

Just open `index.html` in any modern web browser (Chrome, Safari, Edge, or Firefox).

> **Note:** Don't open it from inside an email preview or a text editor — those won't run the styling or interactivity, and the page will look like plain black-and-white text. It needs to open in an actual browser. If it looks unstyled, download the file first, then right-click it and choose *Open with → your browser*.

## Publishing with GitHub Pages

This repo is set up to be hosted for free on GitHub Pages:

1. In the repo, go to **Settings → Pages**.
2. Under **Source**, choose **Deploy from a branch**.
3. Set the branch to `main` and the folder to `/ (root)`, then **Save**.
4. Wait a minute or two, then refresh. Your live link will appear at the top of the Pages settings, in the form:

   ```
   https://<your-username>.github.io/<repo-name>/
   ```

Because the file is named `index.html`, it serves automatically at the root of that URL — clean and shareable.

## Editing it

Everything lives in one file: `index.html`. The HTML content, the CSS styling, and the JavaScript are all in that single document.

- **To change wording or numbers** (for example, updating the pricing table or the calculator's default values), edit the relevant text directly in the HTML.
- **To change colors or fonts**, look at the `:root` block near the top of the `<style>` section — all the colors and font choices are defined there as variables in one place.
- After editing, commit the change and GitHub Pages will redeploy automatically within a minute or two.

## A note on the numbers

The costs, percentages, and usage figures on the page are **illustrative** — they're there to build intuition and support a conversation, not to serve as a precise quote. Two sections are explicitly tagged as examples. Model prices change often, so the comparison table links out to each vendor's official pricing page; confirm current rates there before using any figure for actual budgeting.

## Fonts and offline use

The page uses Google Fonts for its typography, loaded over the internet. If a viewer's network blocks Google Fonts (some corporate networks do), the page falls back automatically to high-quality system fonts and still renders correctly in full color — only the exact typeface changes. All colors, layout, and interactivity are embedded in the file and work with or without an internet connection.
