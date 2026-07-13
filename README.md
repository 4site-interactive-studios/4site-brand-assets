# 4Site Brand Assets

Canonical repository for 4Site Studios brand assets: logos, marks, the sticker shape library, illustrated scenes, decorative rules, licensed fonts, and feature-image templates.

This repo pairs with the `4site-visual-brand` Claude skill. The skill bundles the small, high-frequency assets (logo SVGs, icon, avatar, shapes, templates) and links here for everything heavier (fonts, full illustrations, rules, print masters). Update assets here first; regenerate the skill when the visual identity itself changes.

Raw file URL pattern (requires auth while this repo is private — works via `gh`, `git`, or an authenticated fetch, not anonymous browsers):

```
https://raw.githubusercontent.com/4site-interactive-studios/4site-brand-assets/main/<path>
# e.g.
gh api repos/4site-interactive-studios/4site-brand-assets/contents/fonts/humoresque/Humoresque-00Plain.otf --jq .download_url
```

## Structure

| Folder | Contents |
|---|---|
| `logo/` | All approved logo colorways (SVG + PNG), EPS print master, 500×500 square PNG, Internal variant, cloud version, tagline lockup, standalone arced tagline |
| `icon/` | The "4" brandmark alone — blue, orange, white SVG |
| `avatar/` | Circular brand-mark avatars — blue, orange SVG |
| `shapes/` | 27-piece sticker shape library (the brand's flourish vocabulary), flat brand colors, some with white line texture |
| `illustrations/` | Full illustrated brand scenes (`bg-partyintheback`, `layout-img-2col-full`) and the minimal mascot face (`face-creepypasta`) |
| `rules/` | "Loopy rule" squiggle section dividers (2 SVG, 1 PNG) |
| `templates/` | Ready-to-adapt 1200×628 blog feature image SVGs, one per brand layout pattern, real logo embedded |

Not stored here: **licensed fonts** (Humoresque, Lazzer, Bariol — commercially licensed, kept in the internal Google Drive font folder; never publish the binaries), P22 Mackinac Pro (Adobe Fonts — activate via Adobe), and Hanken Grotesk / Inter / Noto Sans (free on Google Fonts).

## Related

- Figma brand guide — canonical source for visual identity decisions
- "4Site Brand Language Content Guide" (Google Drive) — voice, messaging, tagline, UVP/USP
- `4site-visual-brand` Claude skill — encodes the brand rules for AI-generated visuals
- Team avatar library (Google Drive) — teammate portrait avatars (not brand marks)
