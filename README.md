# Jekyll Boilerplate

Jekyll Boilerplate is a lightweight and cleaned up version of the initial [Jekyll](https://jekyllrb.com/) setup. The motivation behind this project was for me to avoid doing the same things over and over every time I build yet another site with Jekyll.

## Features

### Additions

* An empty folder has been created at `assets/images`.
* An empty folder has been created at `assets/js`.
* An initial configuration for Kramdown has been added.
* The CSS is being minified via Sass.
* Some project-agnostic base styles have been added.
* Normalize.css has been added.
* `.DS_Store` and `node_modules` have been added to `.gitignore`.
* The `jekyll-feed` gem has been added to automate Atom feed generation.
* The `jekyll-sitemap` gem has been added to automate sitemap generation.

### Editions

* The `_sass` folder has been moved to `assets/sass`.
* The `css` folder has been moved to `assets/css`.
* The `default.html` layout has been cleaned up.
* The `index.html` has been cleaned up.

### Deletions

* The `about.md` file has been removed.
* The `page.html` and `post.html` layouts have been removed.
* The sample post and the `_posts` folder have been removed.
* All initial partials from the `_includes` folder but `head.html` have been removed.
* Options `email`, `twitter_username`, `github_username` have been removed.
* All the existing styles have been removed.

### Fixes

* A `lang` attribute has been added to the default layout.
* A `<main>` element has been added to the default layout.

## Credits

* [Jekyll](https://jekyllrb.com/)
* [Hugo Giraudel](https://twitter.com/HugoGiraudel)
