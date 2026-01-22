# Zen Plumbing - Claude Code Instructions

## Project Type
Astro website with Tailwind CSS, deployed to Cloudflare Pages.

## Design System

### Typography
```css
@import url('https://fonts.googleapis.com/css2?family=Archivo%20Black:wght@400;700;900&family=DM%20Sans:wght@400;500;600&display=swap');

:root {
  --font-display: 'Archivo Black', sans-serif;
  --font-body: 'DM Sans', sans-serif;
}
```

### Colors
```css
:root {
  --color-primary: #1a2634;
  --color-accent: #ff6b35;
  --color-surface: #f8fafc;
  --color-text: #1a2634;
  --color-text-muted: #64748b;
}
```

### Effects to Include
- Grain texture
- Geometric shapes
- Bold lines
- High contrast

## Required Pages
1. Homepage (index.astro)
2. Services (/services)
3. About (/about)
4. Contact (/contact)

## Quality Checklist
- [ ] Lighthouse Performance > 90
- [ ] Mobile responsive (375px)
- [ ] LocalBusiness schema
- [ ] Distinctive design (NOT generic)
- [ ] Animations and hover states

## DO NOT
- Use Inter, Roboto, or Arial fonts
- Create cookie-cutter layouts
- Skip the design direction
- Use placeholder text (use scraped content)

## Workflow
1. Read prd.json for stories
2. Complete stories in order
3. Mark "passes": true when done
4. Deploy when all stories pass
