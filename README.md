# Front-End Intern Test: Brightpath Landing Page

Welcome, and thank you for applying. This is a practical test: build a one-page website from a design, using
**HTML and CSS only**.

## The task

Build the landing page for **Brightpath Academy**, a (fictional) online learning platform, so that it matches the
designs in the `design/` folder as closely as you can.

| File | What it shows |
| --- | --- |
| `design/design-desktop-1440.png` | The full page at a 1440px wide screen |
| `design/design-mobile-390.png` | The full page on a 390px wide phone (exported at 2x, so the image is 780px wide) |
| `design/style-guide.md` | Exact colors, fonts, sizes, spacing and breakpoints |
| `content.md` | All the text on the page, so you do not need to type it from the image |
| `assets/` | The logo, every icon and every illustration you need (SVG) |

## Time

- Time limit: **3 hours** of work. Submit within **48 hours** of receiving this test.
- If you run out of time, submit what you have and write what you would do next in your `NOTES.md`.
  A clean, unfinished page is better than a complete but messy one.

## Requirements (must have)

1. Build the page with **plain HTML and CSS**. One `index.html` and one `styles.css` is enough.
2. Build every section in the design, in this order:
   1. Header with logo, navigation links, "Log in" link and "Get started" button
   2. Hero: badge, heading, paragraph, two buttons, three statistics and the illustration
   3. "Why Brightpath": three feature cards
   4. "Popular courses": three course cards
   5. "What our students say": three testimonial cards
   6. Newsletter box with an email field and a "Subscribe" button
   7. Footer: logo, short text, social icons, three link columns and the copyright line
3. **Responsive**: the page must match the desktop design at 1440px and the mobile design at 390px, and must not
   break (no horizontal scroll, no overlapping content) at any width between 360px and 1920px.
4. On mobile, the navigation links and header buttons are hidden and a menu (hamburger) icon is shown.
   The menu does **not** need to open.
5. Use semantic HTML (`header`, `nav`, `main`, `section`, `footer`, headings in the right order, and so on).
6. Every `<img>` has an `alt` attribute. The email field has a label (it can be visually hidden).
7. Buttons and links have a **hover** state.
8. Load the fonts from Google Fonts (see `design/style-guide.md`).

## Bonus (nice to have, not required)

- Use CSS custom properties (variables) for colors and fonts.
- Use CSS Grid and/or Flexbox for the layouts.
- Visible focus styles for keyboard users.
- A working mobile menu built with CSS only (for example, a checkbox or `:target`).
- Small, tasteful transitions on hover.
- A sensible layout at tablet width (around 768px to 1023px). There is no design for it, so use your judgement.

## Not allowed

- CSS frameworks or UI kits (Bootstrap, Tailwind, Bulma, and so on).
- Page builders, templates, or code exported from a design tool.
- JavaScript is **not needed**. You may use a few lines only for the bonus mobile menu.
- Copying the page from another source. You can search for how to do something, of course, but you should be
  able to explain every line you submit.

## What to submit

A GitHub repository link (preferred) or a `.zip` file containing:

```
index.html
styles.css
assets/          (the folder you received, with the same paths)
NOTES.md         (short: what you finished, what you skipped, anything you want us to know)
```

If you use GitHub, enabling GitHub Pages so we can open the page online is a plus.

## How we will review it

- How close the page is to the design (layout, spacing, colors, typography)
- Responsive behaviour on desktop and mobile
- Clean, semantic HTML
- Organised, readable CSS
- Basic accessibility
- Attention to detail (hover states, alignment, consistent spacing)

After you submit, we may ask you to walk us through your code in a short call and make a small change live.

Good luck, and enjoy building it.
