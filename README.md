# Omanshi — Personal Portfolio

A single-file portfolio website built with HTML, CSS, and vanilla JavaScript.

## How to run
Just open `index.html` in any browser. No build step, no dependencies.

## How to edit

### Change your photo
Find `class="hero-photo-inner"` and replace the `O` with:
```html
<img src="your-photo.jpg" style="width:100%;height:100%;object-fit:cover;border-radius:50%;" />
```

### Change your name in the nav logo
Find `class="nav-logo-circle"` and update the letter.

### Update project GitHub links
In the `<script>` section, find the `PROJECTS` array and update each `url:` field.

### Add your resume PDF
Find the two buttons in the Resume section and replace `#` with your PDF link.

### Change the quote on the hero
Find `class="hero-quote"` and update the text.

## Sections
- Hero (landing page)
- About
- Resume
- Projects (cards → GitHub links)
- Writing (cards → in-page article reader)
- Journey (timeline)
- Achievements (gallery)

## Fonts used
- IM Fell English (Google Fonts)
- Cormorant Garamond (Google Fonts)

## Colors
- Background: #080808
- Accent: #F97316 (orange)
- Gold: #FBBF24
- Text: #FFF5E6
