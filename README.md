# maxrintoul.github.io

Personal website of Max Rintoul, a marine biogeochemist. Built with Jekyll (GitHub Pages) on the
[Freelancer](https://github.com/jeromelachaud/freelancer-theme) Bootstrap theme.

## Editing content

| What | Where |
| --- | --- |
| Name, tagline, email, socials, footer address, contact form ID | `_config.yml` |
| About text | `_includes/about.html` |
| Research themes (grid + popups) | `_posts/*.markdown`, images in `img/portfolio/` (900x650) |
| Publications | `_data/publications.yml` |
| DEI statement | `_includes/dei.html` |
| Profile picture | `img/profile.png` |

### Contact form
Create a form at [formspree.io](https://formspree.io) and set `formspree_id` in `_config.yml`.
Until then the contact section shows a plain `mailto:` button.

## Running locally
```sh
bundle install
bundle exec jekyll serve
```
