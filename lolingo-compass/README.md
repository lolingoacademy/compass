# Lolingo Compass 🧭

**Find the right English material — for exactly you.**

A curated English learning platform for Chinese learners. Filter by level (A1–C1), age group, topic, and format. Every material includes a video or audio embed, vocabulary, culture notes, read-aloud practice, and a quiz.

## Live site

Once deployed: `https://lolingoacademy.github.io/home`

## How to deploy (GitHub Pages)

1. Go to your repo: https://github.com/lolingoacademy/home
2. Upload all files keeping the folder structure:
   ```
   index.html
   materials/
     rome.html
     (add more here)
   ```
3. Go to **Settings → Pages**
4. Under "Source" select **Deploy from a branch**
5. Choose **main** branch, **/ (root)** folder
6. Click Save — your site will be live in ~2 minutes

## Adding new materials

1. Duplicate `materials/rome.html`
2. Fill in the content (use the Lolingo prompt template to generate it)
3. Add a new card in `index.html` with the correct `data-level`, `data-age`, `data-topic`, `data-format` attributes
4. Push to GitHub

## File structure

```
index.html          ← content browser with filters
materials/
  rome.html         ← sample B1 material (Roman Empire)
  bbc-news.html     ← (placeholder)
  animals.html      ← (placeholder)
  ...
README.md
```

## Tech stack

Plain HTML + CSS + vanilla JS. No frameworks, no build step, no dependencies. Loads fast everywhere, works on mobile.
