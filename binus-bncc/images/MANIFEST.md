# Extracted images — BNCC × RevoU landing page (copied from binus-university-offer)

All images pulled from the original page at full/original resolution
(Wix transform suffixes stripped to fetch originals, not the blurred thumbnails).

## Logos
| File | What it is |
|------|-----------|
| `revou-logo.png` | RevoU yellow circular logo |
| `binus-logo.png` | BINUS University logo |
| `bncc-logo.png` | **In use** — BNCC (Bina Nusantara Computer Club) stacked lockup, top logo bar. Trimmed from `assets/BNCC_Bigger 1(1).png` (466² with transparent padding → 356×297) so the CSS height sizes the artwork, not the padding. |
| `aws-logo.png` | AWS logo (Software Engineering section) |
| `hackerrank-logo.png` | HackerRank logo (Software Engineering section) |
| `binus-greatnusa.png` | BINUS University + GreatNusa two-logo lockup (certificate issuers) |
| `claude-code-logo.png` | Claude Code wordmark, stacked two-line lockup, orange on transparent. Pulled from the programme's own page at `revou.co/images/claude-code-logo.png`, so the offer page shows the same asset the live page does. Used in the Applied AI hero card chip and its tool row. |
| `n8n-logo.png` | Official n8n horizontal logo (coral node mark + slate wordmark, transparent). From `n8n.io/n8n-logo.png` — the programme page references n8n only in a workflow screenshot, so the mark came from the vendor. Slate wordmark, so it needs a white chip, never the dark one. |
| `claude-logo.png` | Claude horizontal lockup — orange asterisk + black "Claude" wordmark, transparent. Wikimedia Commons `Claude AI logo.svg` (public domain), rendered to 480px wide. |
| `chatgpt-logo.png` | ChatGPT knot mark, black on transparent — the current branding, not the old sage-green app tile. Wikimedia Commons `ChatGPT-Logo.svg` (public domain), rendered to 320px square. Icon only: no ChatGPT wordmark lockup exists on Commons. |

## Hero
| File | What it is |
|------|-----------|
| `hero-students.png` | Two students in maroon blazers, transparent PNG (desktop hero) |
| `hero-student-mobile.png` | Single male student, transparent PNG (mobile hero crop) |
| `binus-campus.jpg` | **In use** — faded backdrop behind the whole hero section (`.hero` background, `cover` + bottom anchored, under a cream veil). Sky is baked in so it needs no alpha: 280 KB vs 1.4 MB for the PNG. Preloaded in `<head>`, since a CSS background is discovered late and this one is above the fold. |
| `binus-campus.png` | Source cutout of the campus building, transparent sky. Kept as the master — re-bake the `.jpg` from this if the hero background changes. Baked stops: `#fbf9ef 0% → #ebf2f9 38% → #c6deee 100%` vertical, then JPEG q72. The stops no longer have to match anything in the CSS (they did when the photo sat in its own panel); they now just tint the cropped sky, and cream at the top is what keeps it blending into the page. |

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

## Certificates
| File | What it is |
|------|-----------|
| `certificate-cybersecurity.png` | Certificate of Achievement sample — Applied Cybersecurity with AI (RevoU / BINUS / GreatNusa) |
| `certificate-applied-ai.webp` | Certificate of Achievement sample — Applied AI, Analytics & Automation. Pulled from the programme's own page (`revou.co/_astro/certificate-preview.*.webp`, the zoom-size render, 1024×799). Kept as WebP: 34 KB against 411 KB for the equivalent PNG. |

## Alumni testimonials
| File | What it is |
|------|-----------|
| `testimonial-alvin.webp` | Alvin Budiarjo photo |
| `testimonial-mega.jpg` | Mega Dewi Larasati photo |
| `testimonial-nathasya.jpeg` | Nathasya Magdalena photo |

> Note: these are RevoU/BINUS brand and stock/licensed assets. Use only within
> the intended RevoU × BINUS partnership context. `claude-code-logo.png`, `n8n-logo.png`,
> `claude-logo.png` and `chatgpt-logo.png` are third-party vendor marks, shown to identify the
> tools the curriculum teaches — the same nominative use as the AWS and HackerRank marks.
> They render bare in the Applied AI panel's tool row, sized by optical weight rather than a
> shared box height: three wordmark lockups plus one square icon.
