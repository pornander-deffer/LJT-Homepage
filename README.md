# Junteng Liu - Academic Homepage

Personal academic website based on [Academic Pages](https://github.com/academicpages/academicpages.github.io). Upstream layouts, assets, and the MIT license are retained.

## Editing

Only existing template pages are used. Research and contact navigation links point to sections on the homepage, not separate pages.

- `_config.yml`: identity, social profiles, Jekyll settings, and hosting URL.
- `_pages/about.md`: homepage, including all publications, research interests, background, and contact links.
- `_pages/cv.md`: curriculum vitae.
- `_pages/publications.html`: publications page.
- `_data/publications.yml`: six publications and complete author lists, reused on the homepage, publications page, and CV.
- `_includes/ljt-background.html`: education, internships, and award, reused on the homepage and CV.
- `_data/cv.json`: machine-readable background and contact details.
- `_data/navigation.yml`: navigation.

Template sample pages, collections, and downloadable files are excluded in `_config.yml`; theme source is retained.

## Source and Review Notes

Personal content was populated from saved memory, not independently verified as current. The potentially stale description 'first-year' is omitted. Memory lists the MINIMAX internship as February 2025 - Present; confirm its current status. No programming languages, frameworks, language proficiencies, office address, or phone number were recorded, so none are claimed. Skills are limited to recorded research expertise.

Publication titles, author lists, years, and venues follow memory. Exact publication dates, paper URLs, and repository URLs were not recorded and have not been guessed. A Google Scholar link provides access to the publication profile. The profile image uses the saved GitHub account's public avatar endpoint, not a fabricated portrait.

The public GitHub profile remains Vicent0205. Hosting is under pornander-deffer/LJT-Homepage.

## GitHub Pages

Configured URL: https://pornander-deffer.github.io/LJT-Homepage/

To publish, open Settings > Pages, choose Deploy from a branch, and select master / (root). The URL is not evidence that deployment has completed.

## Local Preview

With Ruby, Bundler, and the template dependencies installed:

```sh
bundle install
bundle exec jekyll serve --host 127.0.0.1
```

Visit http://127.0.0.1:4000/LJT-Homepage/ after the server starts.

A local Jekyll build and browser rendering have not been verified in the editing environment.
