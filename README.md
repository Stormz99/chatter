<div align="center">

# Chatter

A responsive landing page for a blogging platform built around text-based content.

<a href="https://stormz99.github.io/chatter/"><img src="https://img.shields.io/badge/Live_site-543EE0?style=for-the-badge&logo=githubpages&logoColor=white" alt="Live site"></a>
<a href="https://www.figma.com/design/TXzuoMAwGEIfWcAq0HbBNY/purposed?node-id=55-78&t=twTf4fFXEkJS9KDo-0"><img src="https://img.shields.io/badge/Figma_design-0F0F0F?style=for-the-badge&logo=figma&logoColor=white" alt="Figma design"></a>

<br><br>

<a href="https://stormz99.github.io/chatter/"><img src="assets/preview.png" alt="Chatter landing page on desktop and mobile" width="100%"></a>

</div>

## About

Chatter is a landing page converted from a Figma design into plain HTML and CSS, built one section at a time. It is fully responsive and uses no frameworks or JavaScript.

## Sections

1. Navigation bar
2. Hero
3. About Chatter
4. Why you should join Chatter
5. Testimonial
6. Call to action
7. Footer

## Built with

- HTML5
- CSS3, using custom properties, Flexbox and Grid
- DM Sans from Google Fonts

The mobile menu is a CSS-only toggle.

## Responsive behaviour

| Width            | Changes                                                                        |
| ---------------- | ------------------------------------------------------------------------------ |
| 1200px and below | Tighter spacing, smaller images and headings                                   |
| 900px and below  | Navigation collapses into a menu, sections stack, cards become a single column |
| 600px and below  | Smaller type, full-width buttons, footer links wrap into two columns           |

## Project structure

```
chatter/
├── index.html
├── style.css
├── README.md
└── assets/
    ├── logo.svg
    ├── hero.jpg
    ├── about.jpg
    ├── testimonial.jpg
    ├── avatar-1.jpg
    ├── avatar-2.jpg
    ├── avatar-3.jpg
    ├── icon-analytics.svg
    ├── icon-social.svg
    ├── icon-content.svg
    └── preview.png
```

## Running locally

```bash
git clone https://github.com/Stormz99/chatter.git
cd chatter
open index.html
```

On Windows or Linux, open `index.html` directly in a browser.

## Deployment

The site is hosted on GitHub Pages at [stormz99.github.io/chatter](https://stormz99.github.io/chatter/).
