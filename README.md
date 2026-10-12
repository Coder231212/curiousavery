# Avery H. Liu

Source for Avery's personal research and project site at [curiousavery.github.io](https://curiousavery.github.io/).

The site is built with HugoBlox and deployed to GitHub Pages from the `main` branch.

## Local development

Requirements:

- Hugo Extended 0.162.0
- Node.js 22
- pnpm 10

Install the front-end dependencies, then start Hugo:

```shell
pnpm install
pnpm dev
```

Create a production build with:

```shell
pnpm build
```

## Content

- Homepage sections: `content/_index.md`
- Profile data: `data/authors/me.yaml`
- Downloadable resume: `static/uploads/resume.pdf`
- Profile artwork: `assets/media/authors/me-avatar.svg`

Research and patient-safety claims on the homepage link to their supporting sources.
