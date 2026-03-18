# harshdarji.com — Personal Website

Dark terminal/scientific aesthetic built with Jekyll + GitHub Pages.

## Quick Setup

```bash
# 1. Clone your repo
git clone https://github.com/HarshD16112/HarshD16112.github.io
cd HarshD16112.github.io

# 2. Copy all site files into the repo root

# 3. Install dependencies (requires Ruby ≥ 3.0)
gem install bundler
bundle install

# 4. Preview locally
bundle exec jekyll serve
# → open http://localhost:4000
```

## Deploying to GitHub Pages

```bash
git add .
git commit -m "initial site"
git push origin main
```

## Custom Domain (harshdarji.com)

See SETUP_GUIDE.md for full DNS instructions.

## Updating Content

- **Research**: `_pages/research.md`
- **Publications**: `_pages/publications.md`
- **Awards/Skills**: `_pages/awards-skills.md`
- **CV**: `_pages/cv.md` + replace `/assets/Harsh_Darji_CV.pdf`
- **Homepage stats/bio**: `index.md`
- **Photo**: replace `hero-avatar-placeholder` div in `index.md` with `<img src="/assets/images/headshot.jpg">`
