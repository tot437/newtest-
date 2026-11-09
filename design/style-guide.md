# Brightpath Style Guide

Use these values. Small differences of a few pixels are fine; the images in this folder are the visual reference.

## Colors

| Name | Hex | Used for |
| --- | --- | --- |
| Primary | `#4F46E5` | Main buttons, links, active nav link, newsletter box, price |
| Primary dark | `#4338CA` | Primary button on hover |
| Primary light | `#EEF0FF` | Badge background, feature icon background, "Development" tag |
| Accent | `#F59E0B` | "Subscribe" button, stars, quote marks |
| Accent hover | `#FBBF24` | "Subscribe" button on hover |
| Dark | `#1E1B4B` | Footer background, text on the accent button |
| Heading | `#0F172A` | Headings and strong text |
| Text | `#475569` | Body text |
| Border | `#E2E8F0` | Card borders, header bottom border, dividers |
| Soft background | `#F8FAFF` | "Popular courses" section, top of the hero gradient |
| White | `#FFFFFF` | Page background, cards |
| Footer text | `#A5B4FC` | Footer paragraph and links |
| Newsletter text | `#E0E7FF` | Paragraph and note inside the newsletter box |

Course tags:

| Tag | Background | Text |
| --- | --- | --- |
| Development | `#EEF0FF` | `#4F46E5` |
| Design | `#FEF3C7` | `#B45309` |
| Data | `#CCFBF1` | `#0F766E` |

## Fonts (Google Fonts)

- **Poppins** (weights 600, 700): logo, all headings, statistics numbers, prices.
- **Inter** (weights 400, 500, 600): everything else.

| Element | Desktop | Mobile | Weight | Line height |
| --- | --- | --- | --- | --- |
| Hero heading (h1) | 56px | 36px | 700 | 1.2 |
| Section heading (h2) | 40px | 30px | 700 | 1.2 |
| Newsletter heading | 34px | 26px | 700 | 1.2 |
| Card heading (h3) | 20px | 20px | 700 | 1.2 |
| Logo text | 22px | 22px | 700 | - |
| Statistic number | 30px | 24px | 700 | 1.2 |
| Price | 22px | 22px | 700 | - |
| Hero paragraph | 18px | 16px | 400 | 1.6 |
| Body text | 16px | 16px | 400 | 1.6 |
| Eyebrow (small uppercase title) | 14px, letter-spacing 0.08em | same | 600 | - |
| Badge, tags, small text | 13px to 15px | same | 500 to 600 | - |

## Layout

- Content container: max width **1160px**, centred, **24px** padding on the left and right.
- Header height: **80px** desktop, **68px** mobile. Header has a 1px bottom border.
- Section vertical padding: **96px** desktop, **64px** mobile.
- Gap between cards: **28px** desktop, **20px** mobile.
- Hero: two columns on desktop (text left, illustration right); one column on mobile (illustration below text).
- Feature, course and testimonial cards: 3 columns on desktop, 1 column on mobile.
- Footer: 4 columns on desktop (the first one is twice as wide); 2 columns on mobile.

## Shapes and effects

| Element | Value |
| --- | --- |
| Buttons, badge, tags, email input | Fully rounded (`border-radius: 999px`) |
| Cards | `border-radius: 16px` |
| Feature icon box | 64 x 64px, `border-radius: 16px` |
| Newsletter box | `border-radius: 24px` (20px on mobile) |
| Social icon circles | 40 x 40px |
| Avatars | 52 x 52px, circle |
| Card shadow (course cards, feature card on hover) | `0 10px 30px rgba(30, 27, 75, 0.08)` |
| Hero background | Vertical gradient from `#F8FAFF` to `#FFFFFF` |
| Button padding | 14px 26px (header button: 10px 20px) |

## Breakpoints

| Name | Width |
| --- | --- |
| Mobile | up to 767px |
| Tablet (no design, your choice) | 768px to 1023px |
| Desktop | 1024px and wider |

## Assets

All in `assets/`. Use them as `<img>` files; you do not need to edit them.

| File | Where |
| --- | --- |
| `logo-mark.svg` | Header and footer logo (the word "Brightpath" next to it is HTML text) |
| `icons/icon-menu.svg` | Mobile menu button |
| `icons/icon-arrow-right.svg` | "Explore courses" button (white arrow) |
| `icons/icon-arrow-right-primary.svg` | "View all courses" link (indigo arrow) |
| `icons/icon-play.svg` | "Watch demo" button |
| `icons/icon-calendar.svg`, `icon-mentor.svg`, `icon-certificate.svg` | Feature cards |
| `icons/icon-lessons.svg`, `icon-clock.svg`, `icon-star.svg` | Course cards |
| `icons/icon-quote.svg` | Testimonial cards |
| `icons/social-*.svg` | Footer social links |
| `images/hero-illustration.svg` | Hero |
| `images/course-web.svg`, `course-design.svg`, `course-data.svg` | Course card images |
| `images/avatar-1.svg`, `avatar-2.svg`, `avatar-3.svg` | Testimonial avatars |
