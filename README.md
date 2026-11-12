# Chatter

A responsive landing page for Chatter, a blogging platform for text-based content. It is built with plain HTML and CSS, converted section by section from a Figma design.

## Design

The page follows the [Chatter landing page design on Figma](https://www.figma.com/design/TXzuoMAwGEIfWcAq0HbBNY/purposed?node-id=55-78&t=twTf4fFXEkJS9KDo-0).

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

There are no frameworks or JavaScript. The mobile menu is a CSS-only toggle.

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
    └── icon-content.svg
```

## Running locally

```bash
git clone https://github.com/Stormz99/chatter.git
cd chatter
open index.html
```

On Windows or Linux, open `index.html` directly in a browser.

## Responsive behaviour

The layout adjusts at three breakpoints:

| Width            | Changes                                                                                   |
| ---------------- | ----------------------------------------------------------------------------------------- |
| 1200px and below | Tighter spacing, smaller images and headings                                              |
| 900px and below  | Navigation collapses into a menu, sections stack vertically, cards become a single column |
| 600px and below  | Smaller type, full-width buttons, footer links wrap into two columns                      |
