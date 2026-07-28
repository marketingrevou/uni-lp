# Extracted images — BINUS × RevoU landing page

All images pulled from the original page at full/original resolution
(Wix transform suffixes stripped to fetch originals, not the blurred thumbnails).

## Logos
| File | What it is |
|------|-----------|
| `revou-logo.png` | RevoU yellow circular logo |
| `binus-logo.png` | BINUS University logo |
| `aws-logo.png` | AWS logo (Software Engineering section) |
| `hackerrank-logo.png` | HackerRank logo (Software Engineering section) |

## Hero
| File | What it is |
|------|-----------|
| `hero-students.png` | Two students in maroon blazers, transparent PNG (desktop hero) |
| `hero-student-mobile.png` | Single male student, transparent PNG (mobile hero crop) |
| `BINUS Campus.jpg` | **In use** — faded backdrop behind the whole hero section (`.hero` background, `cover` + bottom anchored, under a cream veil). Sky is baked in so it needs no alpha: 280 KB vs 1.4 MB for the PNG. Preloaded in `<head>`, since a CSS background is discovered late and this one is above the fold. |
| `BINUS Campus.png` | Source cutout of the campus building, transparent sky. Kept as the master — re-bake the `.jpg` from this if the hero background changes. Baked stops: `#fbf9ef 0% → #ebf2f9 38% → #c6deee 100%` vertical, then JPEG q72. The stops no longer have to match anything in the CSS (they did when the photo sat in its own panel); they now just tint the cropped sky, and cream at the top is what keeps it blending into the page. |

## Social proof / stats
| File | What it is |
|------|-----------|
| `stats-banner-desktop.png` | "2.695.700+ Pembelajar / 12.900+ Alumni" + Course Report 2024 badge (desktop) |
| `stats-banner-mobile.png` | Same stats, portrait layout (mobile) |

## Video / feature cards
| File | What it is |
|------|-----------|
| `video-thumbnail.jpeg` | "RevoU Sneak Peek" Zoom-grid video thumbnail with play button |
| `card1.png` | Feature card 1 — Kuasai Skill Digital |
| `card2.png` | Feature card 2 — Proyek Nyata |
| `card3.png` | Feature card 3 — Persiapan Karier |

## Program timeline (milestones)
| File | What it is |
|------|-----------|
| `timeline-desktop-4mo.png` | "4 bulan pertama" timeline — Digital Marketing / Data Analytics (desktop) |
| `timeline-mobile-4mo.png` | Same, vertical/mobile layout |
| `timeline-desktop-6mo.png` | "6 bulan pertama" timeline — Software Engineering (desktop) |
| `timeline-mobile-6mo.png` | Same, vertical/mobile layout |

## Software Engineering tech stack
| File | What it is |
|------|-----------|
| `tech-logos-desktop.png` | Tool logos row (GitHub, Kiro, Lucidchart, Next.js, Python, Vercel, Claude, Flask…) — desktop |
| `tech-logos-mobile.png` | Same logos, mobile grid layout |

## Alumni testimonials
| File | What it is |
|------|-----------|
| `testimonial-alvin.webp` | Alvin Budiarjo photo |
| `testimonial-mega.jpg` | Mega Dewi Larasati photo |
| `testimonial-nathasya.jpeg` | Nathasya Magdalena photo |

> Note: these are RevoU/BINUS brand and stock/licensed assets. Use only within
> the intended RevoU × BINUS partnership context.
