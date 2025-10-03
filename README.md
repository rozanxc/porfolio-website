# Roshaan's Portfolio Website 😊

My first personal portfolio website which includes 4 pages:
- Home (`index.html`)
- About Me (`about.html`)
- Projects (`projects.html`)
- Contact Me (`contact.html`)

My CSS is split by viewport so each device size gets the simplest, most readable layout:
- `style-laptop.css` — default styles (loaded for all screens)
- `style-tablet.css` — loaded when the screen is 991px wide or smaller
- `style-mobile.css` — loaded when the screen is 600px wide or smaller

## Viewports (dimensions) and why

I used three breakpoints to keep the layout readable and easy to navigate on any device:

- Mobile: up to 600px
  - Why: phones need a single-column layout, larger tap targets, and tighter spacing.

- Tablet: 601px to 991px
  - Why: tablets get more width than phones but still really similar to phones.

- Laptop/Desktop: 992px and up
  - Why: larger screens can show wider content with more white space.

## Gradients used (linear + angled)

I used a linear gradient with an angle on the page background so the whole site gets a subtle depth effect.

- Body background (applies across all pages)
  ```css
  body {
    background: linear-gradient(135deg, #000000 50%, #150A0E 100%);
  }
  ```
- What and why:
  - Linear gradient: smoothly blends two colors because is appealing to look at.
  - Angled (135°): adds a diagonal flow

## Color scheme

My color scheme took me while but I ended up going with a dark / high contrast mix

- Primary background: `#000000` (black)
- Secondary background (card/content): `#100D12` (very dark maroon). I feel like it goes really well with black
- Gradient end: `#150A0E` (deep burgundy).
- Text: `#FFFFFF` (white) for MAX contrast on dark backgrounds so its easily visible. 
- Accent (hover): `#92A8D1` (for the buttons)

Why I chose this scheme:
- Dark backgrounds reduce glare which is easy on human eyes. Most people prefer darker colors. I also made the text white so everyone can easily see
- The deep maroon and burgundy tones match well with black

## File structure

- `index.html` — Home
- `about.html` — About Me
- `projects.html` — Projects
- `contact.html` — Contact Me
- `style-laptop.css` — base styles + background gradient
- `style-tablet.css` — tablet overrides (≤ 991px)
- `style-mobile.css` — phone overrides (≤ 600px)
- Images/videos used by About page

## How to view

- Local: open `index.html` in a browser.
- GitHub Pages : https://rozanxc.github.io/portfolio-website/
