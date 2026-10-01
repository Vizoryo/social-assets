# Vizoryo — social assets

Public images used in Vizoryo's social media posts (Instagram, Facebook, LinkedIn, X, Threads, Bluesky, Pinterest, TikTok).
Scheduling tools such as Metricool pull each image from its public URL.

**Everything in this repository is public.** Anyone with the link can open any file here.

## Public URL of a file

```
https://raw.githubusercontent.com/Vizoryo/social-assets/main/<path-to-file>
```

Example: `posts/2026/10/2026-10-05_ig_fuller-profile.png` →
`https://raw.githubusercontent.com/Vizoryo/social-assets/main/posts/2026/10/2026-10-05_ig_fuller-profile.png`

## Folders

| Folder | What goes there |
| --- | --- |
| `brand/` | Logo, profile pictures, banners and covers for every network |
| `posts/YYYY/MM/` | Images for feed posts, one folder per month |
| `stories/YYYY/MM/` | Vertical images (9:16) for Instagram and Facebook stories |
| `data-cards/` | Reusable data cards (facts, numbers, short explanations) |
| `ai-clinic/thumbnails/` | AI Clinic episode thumbnails |
| `ai-clinic/stills/` | Stills from AI Clinic episodes for text posts |
| `templates/` | Empty templates (frames, backgrounds) for building new images |

## File names

```
YYYY-MM-DD_<network>_<short-slug>.<ext>
```

- Date = the publishing date.
- Network codes: `ig` Instagram · `fb` Facebook · `li` LinkedIn · `x` X · `th` Threads · `bs` Bluesky · `pin` Pinterest · `tt` TikTok · `all` the same image everywhere.
- Slug: lowercase English words joined with hyphens. No spaces, no Hebrew, no special characters.
- Formats: `.png` or `.jpg`. Keep each image under 5 MB.

Examples: `2026-10-05_all_we-build-you-verify.png`, `2026-10-06_li_index-reads-september.jpg`

## Rules

1. **Never rename, move or delete a file that a scheduled or published post uses.** The post links to the exact URL, and the image will break.
2. **No personal or private data** — no customer details, internal numbers, screenshots of the admin panel or anything not meant for the public.
3. **Nothing ahead of its release.** Upload an unreleased episode still or announcement only when it is fine for it to be seen early, since the URL is public from the moment the file is uploaded.
4. **Images only.** Videos stay in Higgsfield / YouTube / Metricool — not here.
5. Every post image carries the Vizoryo logo (see `brand/`).
