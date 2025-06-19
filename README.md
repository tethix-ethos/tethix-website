# About tethix-website

This repository includes a Jekyll-based version of the [Tethix website](https://tethix.co).

## Tech stack 

The website uses Jekyll 4 and deploys to GitHub Pages. 

The project uses the following plugins:

- [jekyll-feed](https://github.com/jekyll/jekyll-feed): for generating RSS feeds for different collections,
- [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag): for adding SEO-friendly tags in the header,
- [jekyll-paginate-v2](https://github.com/sverrirs/jekyll-paginate-v2): for adding pagination to collections and generating autopages for categories and tags,
- [jekyll-target-blank](https://keith-mifsud.me/projects/jekyll-target-blank): to open all external links in a new window in a safe way,
- [jekyll-redirect-from](https://github.com/jekyll/jekyll-redirect-from): to redirect some old URLs and handle awkward URL paths. 

## Getting started with Jekyll on macOS

To get a local copy up and running follow these simple steps.

### Prerequisites

  Jeykyll requires Ruby 2.5 or above. Ruby 3 and above does not include webrick; this dependency will be included when you run bundle install (see below).

  ```sh
  brew install ruby
  ```  
  Install jekyll:

  ```sh
  gem install jekyll bundler
  ```

### Running the website locally

  Make sure all dependencies in your Gemfile are available to your application
  ```sh  
  bundle install
  ```
  Build the site and serve locally with or without live reload
  ```sh
  bundle exec jekyll serve
  bundle exec jekyll serve --livereload
  ```

If you run into any problems, Jekyll documentation has all the information you need to set up your machine, and build and run a Jekyll site: https://jekyllrb.com/docs/.

## Editing and adding content

### Content types and layouts

- **Pages** can be found in the `pages` folder. Most pages use the `page` layout, and include different section styles – see the `_includes` folder for include files starting with 'section'. For a basic content page, you can use the `page-content` layout.
- **Blog posts** can be added and edited in the `_posts` folder. Pagination and autopages based on categories and tags are enabled for blog posts. See the `blog` and `post` layouts if you want to edit how blog posts appear as a list or individual posts respectively. Autopages also use the `blog` layout. 
- **Newmoonsletters** have their own collection, which doesn't use categories, tags, or pagination, and lives inside the `_newmoonsletters` folder. The `newmoonsletter` layout is used to display individual issues.
- **Data files** inside the `_data` folder include:
    - lists of blog post `authors.yml`, 
    - descriptions of elemental `categories.yml` for the blog, 
    - navigation elements for header and footer `menus.yml`, 
    - `people.yml` that are part of the Tethix team and advisors, 
    - `social.json` links, 
    - and sets of paper `sparks.yml`.

### Images

- Images uploaded to the **previous WordPress site** can be found in the `wp-content/uploads/:year/:month` folders. These folders are only used for backwards compatibility reason and to preserve any old links.
- All **new images for posts and pages** should be added to the `images/uploads` folder. 
- The `images` folder also includes dedicated folders for general purpose `icons`, `social` icons, and `logo` files.

### Assets and stylesheets 

- The `assets` folders contains `css`, `js`, and `fonts` files.
- The `assets/css/style.scss` file imports additional bootstrap and theme components from the `_sass` folder. Not all Bootstrap components are used in this project.
- The [Serif Jekyll theme](https://jekyllthemes.io/theme/serif) was used as a starting point, but relies more heavily on Bootstrap components and utilities.

