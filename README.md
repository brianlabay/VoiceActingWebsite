# Brian Labay — Voice Over Website

Personal VO website for Brian Labay, built as a single-file static HTML site.

## Live Site

Deploy via GitHub Pages — see setup instructions below.

## Structure

```
index.html       # The entire site — all CSS, JS, and HTML in one file
README.md        # This file
```

## Setup

### 1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

### 2. Open locally
Just open `index.html` in any browser — no build step, no dependencies.

### 3. Deploy to GitHub Pages
1. Push to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → main → / (root)**
4. Your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`

## Contact Form

The enquiry form uses [Formspree](https://formspree.io) (form ID: `mkokbavr`).
Submissions are delivered to **brianlabayvo@gmail.com**.

To update the form endpoint, find this line in `index.html`:
```
action="https://formspree.io/f/mkokbavr"
```

## Adding Audio

Each reel and sample card has a placeholder play button. When recordings are ready:

1. Add audio files to an `/audio` folder in the repo
2. Replace each disabled `<button>` with an `<audio>` element, e.g.:
```html
<audio controls src="audio/commercial-reel.mp3"></audio>
```

## Contact

Brian Labay — [brianlabayvo@gmail.com](mailto:brianlabayvo@gmail.com)
