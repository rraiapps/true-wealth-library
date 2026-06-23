# The True Wealth Library

An interactive, searchable web app of the curated reading list from *The Right Mountain: Practical Wisdom for Achieving True Wealth* by Matt Ludmer (with Kristin Kaye), published by [Aligned Wealth Management](https://alignedwealthmanagement.com).

Browse 75 resources across eight subject areas, filter by tier (Start Here / Foundational / Deeper Study) and format, and search by title or author.

## Live site

Once deployed, the page is served at:

```
https://<your-username>.github.io/<repo-name>/
```

## What's here

| File | Purpose |
|------|---------|
| `index.html` | The entire app — self-contained (embedded logo, CDN fonts, no build step) |
| `.nojekyll` | Tells GitHub Pages to skip Jekyll processing |
| `README.md` | This file |

## Deploy (GitHub web UI)

1. Create a new repository on GitHub.
2. Upload `index.html`, `.nojekyll`, and `README.md`.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
5. Save. The site goes live in ~1 minute at the URL above.

## Notes

- Resource data is currently hardcoded in `index.html`. For an editable version, wire it to the Supabase True Wealth Library table.
- Organized by subject area (as printed in the book), not by the Seven Essentials.
- Brand: navy `#1F3A5F`, gold `#C9A66B`, cream `#F4EFE6`; Cormorant Garamond + DM Sans.
