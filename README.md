# Aprender Docs

The website for [Aprender](https://github.com/KristianMansfield/Aprender), a flashcard app that teaches the most common Spanish and French words first. It's hosted on GitHub Pages and has three pages:

| Page | File | URL |
| --- | --- | --- |
| Marketing | [index.html](index.html) | https://kristianmansfield.github.io/Aprender-Docs/ |
| Support | [support/index.html](support/index.html) | https://kristianmansfield.github.io/Aprender-Docs/support/ |
| Privacy policy | [privacy/index.html](privacy/index.html) | https://kristianmansfield.github.io/Aprender-Docs/privacy/ |

The App Store listing links to these URLs, so keep the folder names as they are.

## Editing

The pages are plain HTML with one shared stylesheet, [style.css](style.css), which uses the app's colours and supports dark mode. There's no build step. Edit a file, push to `main`, and GitHub Pages republishes it within a minute or two. The `.nojekyll` file tells GitHub to serve the files as they are.

Images are in [assets/](assets/): the app icon, the favicon, and four screenshots from the app.

If the app starts handling data differently, for example by adding ads or analytics, update the privacy policy and its "Last updated" date before releasing that version.

## Publishing

On GitHub, open Settings → Pages. Under **Source**, choose **Deploy from a branch**, then branch `main` and folder `/ (root)`.
