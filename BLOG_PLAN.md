# Portfolio to Blog - Extension Plan

## How This Portfolio Was Built (Step by Step)

1. **Created `index.html`** — Single-page dark theme with hero section
2. **Added sections** — Projects, Work Photos, Hobbies & Research, Shop Drawings
3. **Photo galleries** — Used grid layout + lightbox for viewing images
4. **PDF links** — Shop drawing PDFs hosted in `shop-drawings/` folder
5. **GitHub Pages** — Pushed to GitHub, enabled Pages for free hosting

---

## Future Plan: Extend to Blog

### Phase 1: Add Blog Section
- Create `blog.html` page
- Add blog card grid with thumbnails, titles, dates
- Add individual blog post pages (`blog/post-1.html`, etc.)

### Phase 2: Blog Content
- ELV system tutorials (CCTV, Fire Alarm, BMS)
- Shop drawing reading guide
- Project case studies
- Equipment reviews

### Phase 3: Better Architecture
```
portfolio/
├── index.html          (main portfolio)
├── blog.html           (blog listing)
├── blog/
│   ├── post-1.html
│   └── post-2.html
├── shop-drawings/      (PDFs)
├── FTB/                (photos)
├── THV2/
├── GDT project/
└── css/
    └── style.css       (shared styles)
```

### Phase 4: Advanced Features
- Search function
- Categories/tags
- Comments section
- RSS feed
- SEO optimization
