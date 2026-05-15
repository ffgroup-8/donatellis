# Donatelli's — Project Tracker

**Client:** Donatelli's
**GitHub:** `ffgroup-8/donatellis` → https://github.com/ffgroup-8/donatellis
**Local:** `~/Desktop/Git Repo/Donatelli's/index.html`
**Live:** https://ffgroup-8.github.io/donatellis/

---

## Master Rules

Follow all rules in `../_Project Tracker Master/CLAUDE.md`. That file is the source of truth for:
- Box hierarchy (`seo-box` → `content-created-box` as siblings)
- CSS patterns (green seo-box, blue content-created-box, dark mode)
- Status pill system (6 categories)
- SEO standards
- Push-automatically rule
- Content writing standard (actual copy, not design annotations)

**Pipeline:** If you add a new pattern here that isn't in Master, also apply it to `../_Project Tracker Master/index.html` and commit both.

---

## Current Progress

| Category        | Progress |
|-----------------|----------|
| Design          | (check tracker) |
| Dev             | (check tracker) |
| SEO             | (check tracker) |
| Content Input   | (check tracker) |
| Sanity Dev      | (check tracker) |
| Content Created | (check tracker) |

---

## Pages

| # | Page | Slug | Content Created |
|---|------|------|-----------------|
| 1 | 🏠 Home | `/` | ⬜ needed |
| 2 | 🍽️ Menus & Location | `/menu` | ⬜ needed |
| 3 | 🥡 Catering | `/catering` | ⬜ needed |
| 4 | ⭐ Rewards | `/rewards` | ⬜ needed |
| 5 | 🎁 Gift Cards | `/gift-cards` | ⬜ needed |
| 6 | 🤝 Donations | `/donations` | ⬜ needed |
| 7 | 💼 Careers | `/careers` | ⬜ needed |
| 8 | 🎟️ Events & Offers | `/events` | ⬜ needed |
| 9 | 📬 Contact | `/contact` | ⬜ needed |

---

## Content Module Template

```html
<p><strong>📌 Module 1 — Hero</strong></p>
<ul>
  <li><strong>Headline:</strong> ...</li>
  <li><strong>Subheadline:</strong> ...</li>
  <li><strong>CTA:</strong> ...</li>
</ul>
```

After adding content for a page:
1. Mark Content Created pill `completed` in both nav-item AND sitemap node
2. Recalculate `data-target` on Content Created progress bar: `(N / 9 * 100).toFixed(0)%`
3. Commit and push automatically
