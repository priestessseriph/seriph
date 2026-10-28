# Visual fidelity

Overall match: **29/100** — fonts, type sizes, spacing and each section measured in a browser on both sites (75%), and how alike the pages look as pictures (25%). How it's scored: docs/qa/import-fidelity.md.

Scored two ways, side by side: **29/100 corrected**, 29/100 by the strict v3 scorer. The corrected score reads three things the strict one gets wrong (navigation in a header themed "brand", off-screen slides counted as columns, a picture-only band on a phone); the pages below list where it did.

Auto-tuning raised it from 28/100:

- section padding on phones 57px

## / at 1440px — 48/100

Checks 47/100 · looks alike 51/100 (screenshots compared).

Original: https://tantra369.com/  
Imported: / (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading font | Cinzel | Cinzel | same |
| Heading 1 size | 71px | 71px | same |
| Body font | Source Sans Pro | Source Sans Pro | same |
| Body text size | 18px | 18px | same |
| Buttons: present | Source Sans Pro 16px | not found | **differs** |
| Label font | Source Sans Pro | Source Sans Pro | same |
| Navigation size | 16px | 16px | same |
| Navigation letter spacing and case | 0.071em, uppercase | 0.071em, uppercase | same |
| Content width | 1344px | 1344px | same |
| Section padding | 56px | 56px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Sacred Sensuality | 17 | Heading: Great Vibes 60px → Cinzel 71px; Text: Source Sans Pro 25px → Source Sans Pro 18px; Text color: #000000 → #202020; Columns: 3 → 1; Image placement: left, 45% wide → center, 93% wide; Image crop: 1.27:1 → 1.5:1; Height: 825px → 1314px |
| 2 | Welcome More Pleasure | 0 | Present: Welcome More Pleasure → no matching section |
| 3 | Touring: | 0 | Present: Touring: → no matching section |
| 4 | (no heading) | 0 | Present: PREMIUM CHAT LINK EMAIL ME → no matching section |

What would close the gap:

- Lay the text out in columns (a stack layout with more columns, or the text block's Columns style).
- Adjust the stack column spans (image column) or the image's side.
- Use the original's image proportions (the block's aspect ratio).
- Bring this section across (or check it was merged into another).

## / at 390px — 43/100

Checks 39/100 · looks alike 55/100 (screenshots compared).

Original: https://tantra369.com/  
Imported: / (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading font | Cinzel | Cinzel | same |
| Heading 1 size | 46px | 39.1px | **differs** |
| Body font | Source Sans Pro | Source Sans Pro | same |
| Body text size | 18px | 18px | same |
| Buttons: present | Source Sans Pro 16px | not found | **differs** |
| Section padding | 40px | 57px | **differs** |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Sacred Sensuality | 50 | Heading: Great Vibes 44px → Cinzel 39.1px; Text: Source Sans Pro 25px → Source Sans Pro 18px; Text color: #000000 → #202020; Height: 1040px → 621px |
| 2 | Welcome More Pleasure | 0 | Present: Welcome More Pleasure → no matching section |
| 3 | Touring: | 0 | Present: Touring: → no matching section |
| 4 | (no heading) | 0 | Present: PREMIUM CHAT LINK EMAIL ME → no matching section |

What would close the gap:

- choices.typography.scale.h1.sizeMobile = 46
- choices.layout.sectionPaddingMobile = 40
- Bring this section across (or check it was merged into another).

## /about at 1440px — 31/100

Checks 27/100 · looks alike 42/100 (screenshots compared).

Original: https://tantra369.com/about/  
Imported: /about (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 1: present | Cinzel 51px | not found | **differs** |
| Heading 2: present | Cinzel 51px | not found | **differs** |
| Body text: present | Source Sans Pro 18px | not found | **differs** |
| Buttons: present | Source Sans Pro 14px | not found | **differs** |
| Label font | Source Sans Pro | Source Sans Pro | same |
| Navigation size | 16px | 16px | same |
| Navigation letter spacing and case | 0.071em, uppercase | 0.071em, uppercase | same |
| Section padding | 57.5px | 56px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Sacred Sensuality | 0 | Present: Sacred Sensuality → no matching section |
| 2 | About Seriph | 0 | Present: About Seriph → no matching section |
| 3 | Why Tantra? | 0 | Present: Why Tantra? → no matching section |

What would close the gap:

- Bring this section across (or check it was merged into another).

## /about at 390px — 15/100

Checks 6/100 · looks alike 41/100 (screenshots compared).

Original: https://tantra369.com/about/  
Imported: /about (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 1: present | Cinzel 37px | not found | **differs** |
| Heading 2: present | Cinzel 37px | not found | **differs** |
| Body text: present | Source Sans Pro 18px | not found | **differs** |
| Buttons: present | Source Sans Pro 14px | not found | **differs** |
| Section padding | 52px | 51px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Sacred Sensuality | 0 | Present: Sacred Sensuality → no matching section |
| 2 | About Seriph | 0 | Present: About Seriph → no matching section |
| 3 | Why Tantra? | 0 | Present: Why Tantra? → no matching section |

What would close the gap:

- Bring this section across (or check it was merged into another).

## /blog at 1440px — 39/100

Checks 29/100 · looks alike 69/100 (screenshots compared).

Original: https://tantra369.com/blog/  
Imported: /blog (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 1: present | Cinzel 51px | not found | **differs** |
| Body text: present | Source Sans Pro 18px | not found | **differs** |
| Buttons: present | Source Sans Pro 14px | not found | **differs** |
| Label font | Source Sans Pro | Source Sans Pro | same |
| Navigation size | 16px | 16px | same |
| Navigation letter spacing and case | 0.071em, uppercase | 0.071em, uppercase | same |
| Section padding | 40px | 56px | **differs** |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Sacred Sensuality | 0 | Present: Sacred Sensuality → no matching section |
| 2 | My Blog | 0 | Present: My Blog → no matching section |

What would close the gap:

- choices.layout.sectionPadding = 40
- Bring this section across (or check it was merged into another).

## /blog at 390px — 21/100

Checks 8/100 · looks alike 61/100 (screenshots compared).

Original: https://tantra369.com/blog/  
Imported: /blog (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 1: present | Cinzel 37px | not found | **differs** |
| Body text: present | Source Sans Pro 18px | not found | **differs** |
| Buttons: present | Source Sans Pro 14px | not found | **differs** |
| Section padding | 49.5px | 51px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Sacred Sensuality | 0 | Present: Sacred Sensuality → no matching section |
| 2 | My Blog | 0 | Present: My Blog → no matching section |

What would close the gap:

- Bring this section across (or check it was merged into another).

## /blog/f/what-is-it-to-be at 1440px — 42/100

Checks 35/100 · looks alike 62/100 (screenshots compared).

Original: https://tantra369.com/blog/f/what-is-it-to-be/  
Imported: /blog/f/what-is-it-to-be (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 1: present | Cinzel 51px | not found | **differs** |
| Body text: present | Source Sans Pro 18px | not found | **differs** |
| Buttons: present | Source Sans Pro 14px | not found | **differs** |
| Label font | Source Sans Pro | Source Sans Pro | same |
| Navigation size | 16px | 16px | same |
| Navigation letter spacing and case | 0.071em, uppercase | 0.071em, uppercase | same |
| Section padding | 57.5px | 56px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Sacred Sensuality | 0 | Present: Sacred Sensuality → no matching section |
| 2 | My Blog | 0 | Present: My Blog → no matching section |

What would close the gap:

- Bring this section across (or check it was merged into another).

## /blog/f/what-is-it-to-be at 390px — 22/100

Checks 8/100 · looks alike 64/100 (screenshots compared).

Original: https://tantra369.com/blog/f/what-is-it-to-be/  
Imported: /blog/f/what-is-it-to-be (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 1: present | Cinzel 37px | not found | **differs** |
| Body text: present | Source Sans Pro 18px | not found | **differs** |
| Buttons: present | Source Sans Pro 14px | not found | **differs** |
| Section padding | 49.5px | 51px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Sacred Sensuality | 0 | Present: Sacred Sensuality → no matching section |
| 2 | My Blog | 0 | Present: My Blog → no matching section |

What would close the gap:

- Bring this section across (or check it was merged into another).

## /blog/f/what-led-me-here at 1440px — 42/100

Checks 35/100 · looks alike 60/100 (screenshots compared).

Original: https://tantra369.com/blog/f/what-led-me-here/  
Imported: /blog/f/what-led-me-here (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 1: present | Cinzel 51px | not found | **differs** |
| Body text: present | Source Sans Pro 18px | not found | **differs** |
| Buttons: present | Source Sans Pro 14px | not found | **differs** |
| Label font | Source Sans Pro | Source Sans Pro | same |
| Navigation size | 16px | 16px | same |
| Navigation letter spacing and case | 0.071em, uppercase | 0.071em, uppercase | same |
| Section padding | 57.5px | 56px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Sacred Sensuality | 0 | Present: Sacred Sensuality → no matching section |
| 2 | My Blog | 0 | Present: My Blog → no matching section |

What would close the gap:

- Bring this section across (or check it was merged into another).

## /blog/f/what-led-me-here at 390px — 21/100

Checks 8/100 · looks alike 58/100 (screenshots compared).

Original: https://tantra369.com/blog/f/what-led-me-here/  
Imported: /blog/f/what-led-me-here (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 1: present | Cinzel 37px | not found | **differs** |
| Body text: present | Source Sans Pro 18px | not found | **differs** |
| Buttons: present | Source Sans Pro 14px | not found | **differs** |
| Section padding | 49.5px | 51px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Sacred Sensuality | 0 | Present: Sacred Sensuality → no matching section |
| 2 | My Blog | 0 | Present: My Blog → no matching section |

What would close the gap:

- Bring this section across (or check it was merged into another).

## /booking-request at 1440px — 24/100

Checks 24/100 · looks alike 25/100 (screenshots compared).

Original: https://tantra369.com/booking-request/  
Imported: /booking-request (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 1: present | Cinzel 51px | not found | **differs** |
| Body text: present | Source Sans Pro 18px | not found | **differs** |
| Buttons: present | Source Sans Pro 16px | not found | **differs** |
| Label font | Source Sans Pro | Source Sans Pro | same |
| Navigation size | 16px | 16px | same |
| Navigation letter spacing and case | 0.071em, uppercase | 0.071em, uppercase | same |
| Section padding | 89.5px | 56px | **differs** |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Sacred Sensuality | 0 | Present: Sacred Sensuality → no matching section |
| 2 | (no heading) | 0 | Present: Click here for the Google form for easie → no matching section |
| 3 | Booking Request online booking tantra tantra appointment | 0 | Present: Booking Request online booking tantra tantra appointment → no matching section |

What would close the gap:

- choices.layout.sectionPadding = 90
- Bring this section across (or check it was merged into another).

## /booking-request at 390px — 7/100

Checks 0/100 · looks alike 28/100 (screenshots compared).

Original: https://tantra369.com/booking-request/  
Imported: /booking-request (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 1: present | Cinzel 37px | not found | **differs** |
| Body text: present | Source Sans Pro 18px | not found | **differs** |
| Buttons: present | Source Sans Pro 16px | not found | **differs** |
| Section padding | 93.5px | 51px | **differs** |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Sacred Sensuality | 0 | Present: Sacred Sensuality → no matching section |
| 2 | (no heading) | 0 | Present: Click here for the Google form for easie → no matching section |
| 3 | Booking Request online booking tantra tantra appointment | 0 | Present: Booking Request online booking tantra tantra appointment → no matching section |

What would close the gap:

- choices.layout.sectionPaddingMobile = 94
- Bring this section across (or check it was merged into another).

