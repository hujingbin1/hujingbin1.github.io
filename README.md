# Jingbin Hu · Academic Homepage

This is a Jekyll homepage using the same public AcademicPages / Minimal Mistakes template repository as [tiamojames.github.io](https://tiamojames.github.io/). It pins the template repository to commit [`81aeba4`](https://github.com/tiamojames/tiamojames.github.io/commit/81aeba46763778b3998c9204d90cb4f4e51db3ed); this repository contains Jingbin’s profile, projects, publications, and image.

## Publish on GitHub Pages

1. Create a repository named `hujingbin1.github.io` under GitHub account `hujingbin1`.
2. Upload the **contents of this folder** to the repository root.
3. Open **Settings → Pages** and set the publishing source to **GitHub Actions**.
4. Push to the `main` branch. The workflow in `.github/workflows/pages.yml` builds and deploys the site to `https://hujingbin1.github.io/`.

The Jekyll theme is fetched from `tiamojames/tiamojames.github.io` during the GitHub Actions build through `jekyll-remote-theme`. Internet access is needed during the build so Jekyll can retrieve the template. GitHub documents remote themes and GitHub Pages support [here](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll).

## Edit the profile

- Site name, profile details, social links, and theme reference: `_config.yml`
- Top navigation: `_data/navigation.yml`
- About, selected paper contributions, projects, internships, publications, education, and honors: `_pages/includes/`
- Selected-paper figures: `images/papers/`
- Profile picture: `images/jingbin-hu.png`
- Template CSS entry point and small local styles: `assets/css/main.scss`

The CV’s phone number is not included in this public homepage. Paper links point to arXiv or official proceedings pages. The `Qwen3.8-Omni` row is labeled as a Qwen Team contribution, per Jingbin’s clarification.

## Local preview

With Ruby and Bundler installed:

```bash
bundle install
bundle exec jekyll serve
```

Open <http://localhost:4000>.

## Template license

The referenced template repository is distributed under the MIT License. Its license notice is included in `LICENSE`.
