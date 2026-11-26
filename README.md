# abdulrahman-zaghloul.github.io

Source for my portfolio site: **https://abdulrahman-zaghloul.github.io**

Plain HTML and CSS in [`site/`](site), no build step. Every pull request and push runs
[html-validate](https://html-validate.org/); pushes to `main` then deploy to GitHub Pages
through [`.github/workflows/pages.yml`](.github/workflows/pages.yml).

Run it locally:

```bash
python3 -m http.server --directory site 8000   # then open http://localhost:8000
npx html-validate "site/**/*.html"
```
