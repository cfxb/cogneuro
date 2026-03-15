# cogneuro.net — Jekyll site

This is a clean, markdown-based static website built with [Jekyll](https://jekyllrb.com/).

---

## How to edit content

**Every page is a `.md` (markdown) file.** Open any file in a text editor and edit the text below the `---` front matter block. That's it.

### Markdown basics

```
# Heading 1
## Heading 2
### Heading 3

Normal paragraph text.

**bold text**   *italic text*

- Bullet item
- Another item

[Link text](https://example.com)

![Alt text](/assets/images/filename.jpg)
```

### File locations

| Page | File to edit |
|------|-------------|
| Home | `index.md` |
| Contact | `contact.md` |
| About | `general/about.md` |
| Clinical information | `patients/clinical-info.md` |
| Neuropsychological assessment | `patients/neuropsych.md` |
| Preparing for assessment | `patients/preparing.md` |
| Language fMRI | `patients/fmri.md` |
| Recommendations | `patients/recommendations.md` |
| Managing memory | `patients/memory.md` |
| Finding a psychologist | `patients/finding-psychologist.md` |
| fMRI: Resources | `clinicians/fmri-resources.md` |
| fMRI: Language tasks | `clinicians/language-tasks.md` |
| fMRI: OMfMRI battery | `clinicians/omfmri.md` |
| Epilepsy readings | `clinicians/epilepsy-readings.md` |
| ESM stimuli | `clinicians/esm-stimuli.md` |
| Research studies | `research/studies.md` |
| Imaging resources | `research/imaging-resources.md` |

### Changing the site title, author, URL

Edit `_config.yml`.

### Changing the navigation menu

Edit `_data/nav.yml`. This controls the top navigation bar structure.

### Changing colours or fonts

Edit `assets/css/style.css`. The colour palette is all at the top in `:root { ... }`.

### Adding images

Copy images into `assets/images/` then reference them in markdown as:
```
![Description](/assets/images/filename.jpg)
```

---

## How to preview locally

Ruby is already set up on your Mac with rbenv. To preview locally:

```bash
# cd into this folder first
cd /Users/christo/Documents/claude/my-site/cogneuro

# Build the site (creates the _site/ folder)
~/.rbenv/versions/3.3.6/bin/ruby ~/.rbenv/versions/3.3.6/bin/jekyll build

# Serve with live reload (auto-rebuilds when you save files)
~/.rbenv/versions/3.3.6/bin/ruby ~/.rbenv/versions/3.3.6/bin/jekyll serve

# Then open http://localhost:4000 in your browser
```

Every time you save a file and Jekyll is running with `serve`, it rebuilds automatically.

### Shortcut: add to your shell profile

Add this alias to `~/.zshrc` so you can just type `jekyll`:
```bash
alias jekyll="~/.rbenv/versions/3.3.6/bin/ruby ~/.rbenv/versions/3.3.6/bin/jekyll"
```

---

## How to deploy

Jekyll builds the site into a `_site/` folder. Upload the contents of `_site/` to your web server via FTP/SFTP, or use a service like:

- **GitHub Pages** (free, automatic) — push this repo to GitHub and enable Pages
- **Netlify** (free, automatic) — connect your GitHub repo for automatic deploys
- **Traditional hosting** — run `bundle exec jekyll build` and upload `_site/`

---

## Adding a new page

1. Create a new `.md` file in the appropriate folder (e.g., `patients/new-page.md`)
2. Add front matter at the top:
   ```
   ---
   layout: default
   title: My new page
   ---

   Content goes here.
   ```
3. Add the page to the navigation in `_data/nav.yml` (optional)
