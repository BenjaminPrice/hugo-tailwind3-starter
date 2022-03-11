# hugo-tailwind3-starter

A very simple starter set up with [TailwindCSS](https://tailwindcss.com/) and its [typography plugin](https://tailwindcss.com/docs/typography-plugin) and a build setup using [PostCSS](https://postcss.org/) and PurgeCSS (when running the production build).

In the preview deployment on Netlify it currently has a 100 score on both mobile and desktop on [Google PageSpeed](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Flucid-nightingale-60a4e2.netlify.app%2F&tab=mobile).


This setup can be used both as a starter project and a theme.

## Inspiration & Attribution
Heavily inspired by [bep/hugo-starter-tailwind-basic](https://github.com/bep/hugo-starter-tailwind-basic) Tailwind 2 template.
Sample content from:
- [mxstbr/markdown-test-file](https://github.com/mxstbr/markdown-test-file)

## As a Project

```bash
npm install
npm start
```

## As a Theme

Import `github.com/BenjaminPrice/hugo-tailwind3-starter` into your project, and then run:

```bash
hugo mod npm pack
npm install
```