# Academic Pages sample (Vishesh Yadav)

Throwaway comparison site built from [Academic Pages](https://github.com/academicpages/academicpages.github.io).

**This is not the live portfolio.** Production site remains the custom scroll-less page at:

* Site: https://vishesh9131.github.io
* Repo: https://github.com/vishesh9131/vishesh9131.github.io

This fork exists only to try the Jekyll academic layout (sidebar bio, publications list, portfolio, CV) with Vishesh's identity and project highlights filled in.

## Preview locally

Needs Ruby + Bundler (same as upstream Academic Pages).

```bash
git clone https://github.com/vishesh9131/academicpages.github.io.git
cd academicpages.github.io
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000/academicpages.github.io/

Docker (upstream compose file):

```bash
docker compose up
```

## Enable GitHub Pages

1. Repo **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `master` (or `main` if you rename), folder `/ (root)`
4. After the build finishes, the preview URL should be:

   `https://vishesh9131.github.io/academicpages.github.io/`

`_config.yml` already sets `url` / `baseurl` for that project-Pages path. If you rename this repo (e.g. to `academicpages-demo`), update `baseurl` and `repository` to match.

## What was customized

* `_config.yml` — name, IISc / AIREX bio, Bangalore, GitHub + LinkedIn
* `_pages/about.md` — home copy + highlights (AxLearn, CoreRec, NVIDIA TEGRA, BHASA, oioi, SLYRIC)
* `_pages/cv.md` — short CV skeleton
* `_publications/` — project-style entries instead of template papers
* `_portfolio/` — CoreRec, oioi, BHASA, SLYRIC
* `_data/navigation.yml` — Publications / Portfolio / CV only

Stock Talks / Teaching / Blog samples were removed so the demo stays focused.

## Related repo name

`vishesh9131/academicpages-demo` is a thin pointer repo (same account) in case you want the clearer name; the full theme checkout lives here because forking Academic Pages keeps all assets intact.
