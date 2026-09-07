# LJT-Homepage

Junteng Liu's personal academic homepage, forked from [Academic Pages](https://github.com/academicpages/academicpages.github.io).

## Content

The existing About page contains the personal profile, education, research experience, all six publications, research areas and interests, scholarship, and contact information supplied in memory. The existing Publications page renders the same publication list.

- `_pages/about.md`: main page and its sections.
- `_data/publications.yml`: publication details, shared by both pages.
- `_includes/publication-list.html`: inline publication rendering; no individual publication pages are generated.
- `_config.yml`: profile and project-site configuration.
- `_data/navigation.yml`: links to the two existing pages and About sections.

Stored dates and contact details are preserved. No portrait, programming languages, tool proficiencies, publication URLs, or code repository URLs have been inferred. The GitHub contact remains `Vicent0205`; `teckatich` is the account hosting this fork.

Inherited sample pages, posts, collections, CV files, and talk-map content are excluded from the published site. The source template and its license are retained.

## GitHub Pages

The site is configured for `https://teckatich.github.io/LJT-Homepage/` using `url: https://teckatich.github.io` and `baseurl: /LJT-Homepage`.

To publish with GitHub's standard Jekyll build, enable Pages in this repository's **Settings → Pages**, select **Deploy from a branch**, and use **master / (root)**. Configuration alone does not mean the site has been deployed.
