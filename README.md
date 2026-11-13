# Paper Wings 🦋

**A scrapbooking field guide where a paper butterfly guides you through the page.**

Paper Wings is a single-page website about scrapbooking as a hobby. As you scroll, a vintage paper butterfly cutout flies a winding route down the page. It lands on a cutout in each section and draws a dashed thread trail behind it.

It's the first "hobby" in what will become a multi-hobby site with a hobby-finder quiz.

## Features

- **Scroll-driven flight.** The butterfly follows a curved path through one landing spot (a "perch") per section. How far you've scrolled decides how far along the path it is.
- **3D wing flap.** The butterfly image is split into left and right wings that rotate in 3D (`rotateY`) to flap. It beats fast while flying and folds slowly while resting.
- **Thread trail.** An SVG path, revealed with a mask as the butterfly travels.
- **Interactions.** Move your cursor near the resting butterfly and it flutters up. Click it and it does a loop.
- **Scrapbook styling.** Washi tape, ransom-note title letters, lined paper cards and torn-paper collages.
- **Responsive.** Works on phones.
- **Accessible.** Respects `prefers-reduced-motion`.

## Sections

1. Hero
2. What is scrapbooking?
3. A little history
4. What you need
5. Styles & techniques
6. Getting started
7. More hobbies coming soon

## Built with

- Plain HTML, CSS and JavaScript (no frameworks)
- Google Fonts: Cormorant Garamond, EB Garamond, Special Elite, Caveat, Abril Fatface
- Built with [Claude](https://claude.ai)

## Run it locally

Download the folder and open `index.html` in a browser.

## Project structure

```
paper-wings/
├── index.html   ← the whole page: HTML, CSS and JavaScript
├── img/         ← cutout images (WebP with transparent backgrounds)
└── README.md
```

## Image credits

The cutout images are placeholders collected from Pinterest. They belong to their original artists and are used here for a non-commercial student project. If one of them is yours and you'd like it credited or removed, please open an issue.

## Roadmap

- [ ] Home page linking all hobbies
- [ ] Hobby-finder quiz
- [ ] More hobby pages (photography, knitting, pottery, journaling…)

## Author

Karen, a computer science student at Miva Open University
