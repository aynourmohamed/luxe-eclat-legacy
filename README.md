# Luxe Éclat — Legacy Version (v1)

The original Luxe Éclat candle e-commerce website, built with HTML, CSS, JavaScript, and Bootstrap. This repo is kept as an archived "v1" so the project's progression is visible.

**Looking for the modern version?** See [luxe-eclat-modern](https://github.com/aynourmohamed/luxe-eclat-modern), rebuilt with Next.js, TypeScript, and Tailwind CSS ((https://luxe-eclat-modern.vercel.app/)).

## Tech Stack

| Area | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom `main.css`) + Bootstrap 5 |
| Interactivity | Vanilla JavaScript + Bootstrap JS components |
| Icons | Font Awesome |
| Fonts | Poppins |

## Pages

| Page | File | Highlights |
|---|---|---|
| Home | `index.html` | Hero carousel, picks for the season, "why choose us" icons, testimonials carousel, newsletter signup |
| Products | `products.html` | Product cards with prices and pagination layout |
| Contact Us | `contactus.html` | Customer service info and contact form |
| Help | `help.html` | FAQ accordion, live chat section |
| Account | `account.html` | Login form and sign-up modal |

## Features

- Bootstrap carousels for the hero and testimonials
- Dropdown menus for language and currency in the top bar
- Search bar and cart icon in the navbar
- Collapsible FAQ accordion
- Sign-up modal on the account page
- Brand styling: mauve/lilac palette (`#c2b5be`), Poppins body font
- Responsiveness fixes: removed `100vw` overflow, fixed navbar wrapping, added a mobile media query for logo, hero text, and product cards

## Running Locally

No build step needed. Open `index.html` in a browser, or serve the folder with any static server.

## Known Limitations

These are the gaps that motivated the rebuild:

| Limitation | Details |
|---|---|
| Static data | Products are hardcoded in HTML, with no shared data source |
| No cart logic | The cart icon is visual only |
| Forms | Contact, login, sign-up, and newsletter forms don't submit anywhere |
| Repeated markup | Top bar, navbar, and footer are copied into every page |
| Responsiveness | Relies on Bootstrap's grid plus some fixed pixel widths |

## What I Learned

- Structuring a multi-page site and a consistent brand style with plain HTML/CSS
- Using Bootstrap's grid and components (carousel, accordion, modal, dropdown)
- Where a no-framework approach gets repetitive, which led to the Next.js rebuild