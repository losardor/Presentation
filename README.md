# Team Presentation

A reveal.js presentation for showcasing team work.

## Quick Start

### Option 1: Using Python (Simplest)
```bash
python3 -m http.server 8000
```
Then open http://localhost:8000 in your browser.

### Option 2: Using Node.js
```bash
npx serve
```

### Option 3: Using PHP
```bash
php -S localhost:8000
```

## Keyboard Shortcuts

- **Arrow Keys**: Navigate between slides
- **Space**: Next slide
- **ESC / O**: Toggle overview mode
- **S**: Open speaker notes (if added)
- **F**: Fullscreen mode
- **B / .**: Pause/blackout presentation

## Editing Your Presentation

Edit `index.html` to customize your presentation:

1. **Add a new slide**: Add a `<section>` element inside `<div class="slides">`
2. **Vertical slides**: Nest `<section>` elements to create vertical navigation
3. **Fragments**: Add `class="fragment"` to elements to reveal them step-by-step
4. **Speaker notes**: Add `<aside class="notes">` inside slides for presenter view

## Themes

Change the theme by modifying the CSS link in index.html:
- black (default)
- white
- league
- beige
- sky
- night
- serif
- simple
- solarized

Replace `/theme/black.css` with `/theme/[theme-name].css`

## Tips for a 15-Minute Presentation

- Aim for 10-15 slides maximum
- Use visuals over text
- Keep bullet points concise
- Practice timing with the actual slides
- Use speaker notes (press 'S') for talking points