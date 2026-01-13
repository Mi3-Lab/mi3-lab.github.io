# Mi3 Lab Website

Official website for the Mi³ Lab (Machine Intelligence, Interaction & Imagination) at UC Merced.

**Live site:** https://mi3-lab.github.io

## Setup

This site uses [Jekyll](https://jekyllrb.com/) and is hosted on GitHub Pages.

### Local Development

1. Install Ruby and Jekyll
2. Clone this repository
3. Run `bundle install` (if using a Gemfile)
4. Run `jekyll serve`
5. Visit `http://localhost:4000`

### Deployment

Push to the `main` branch and GitHub Pages will automatically build and deploy the site.

## Structure

```
├── _config.yml          # Site configuration
├── _layouts/
│   └── default.html     # Main layout template
├── assets/
│   ├── css/
│   │   └── style.css    # Main stylesheet
│   └── images/          # Image assets
├── index.html           # Homepage
├── people.html          # Team members
├── publications.html    # Research publications
├── news.html            # News and events
├── prospective.html     # Info for prospective members
└── gallery.html         # Photo gallery
```

## Customization

- Edit `_config.yml` to update site metadata and navigation
- Add team photos to `assets/images/` and update `people.html`
- Add publications to `publications.html`
- Add news items to `news.html`
- Add gallery photos to `assets/images/gallery/`

## Contact

For questions about this website, contact rossgreer@ucmerced.edu
