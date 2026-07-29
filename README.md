# Awesome Gemini Notebook Slides Templates

A slide-deck-style gallery of prompt templates for **Gemini Notebook** (formerly NotebookLM) slide generation. Each template shows example images alongside its full prompt, ready to copy and paste.

**Browse the gallery:** https://juniorjbn.github.io/awesome-gemini-notebook-slides-templates/

## How to use

1. Open Gemini Notebook and create a new Notebook.
2. Load your sources.
3. Open the slide deck customization box.
4. Copy one full prompt from the gallery and paste it in.
5. Click Generate. Rerun with a different style to change styles.

## Sources & Credits

All templates are curated from these sources — full credit to the original authors:

- [The Gemini Notebook Style Pack (formerly NotebookLM)](https://truetraction.notion.site/The-Gemini-Notebook-Style-Pack-formerly-NotebookLM-3a4eca2dc63381eba726d5e10e15ca50) — by truetraction (22 styles)
- [awesome-notebookLM-prompts](https://github.com/serenakeyitan/awesome-notebookLM-prompts) — by serenakeyitan, CC BY 4.0 (18 templates, originally credited to designers Kawai, yoshifujidesign, mmmiyama_D, kottley, tetumemo and others)

This is a living collection — more templates will be added over time.

## Adding a new template

Edit `index.html` and append an object to the `TEMPLATES` array:

```js
{
  "group": "Category Name",
  "title": "Template Name",
  "desc": "Short description",
  "images": ["assets/my-image.png"],
  "prompt": "STYLE: ..."
}
```

Drop the example image(s) in `assets/` and the site renders the new slide automatically.
