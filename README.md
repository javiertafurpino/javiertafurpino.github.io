# Javier Tafur's Personal Blog

This repository contains the source code for my personal blog and portfolio website, built with Jekyll and hosted on GitHub Pages.

## Local Development

1. Install Ruby and Jekyll:
   ```bash
   gem install bundler jekyll
   ```

2. Clone the repository:
   ```bash
   git clone https://github.com/javiertafurpino/javiertafurpino.github.io.git
   cd javiertafurpino.github.io
   ```

3. Install dependencies:
   ```bash
   bundle install
   ```

4. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```

5. Visit `http://localhost:4000` in your browser

## Adding Content

### Blog Posts
- Create new posts in the `_posts` directory
- Use the format: `YYYY-MM-DD-title.md`
- Include front matter at the top of each post:
  ```yaml
  ---
  layout: post
  title: "Your Title"
  date: YYYY-MM-DD
  categories: category-name
  ---
  ```

### Projects
- Add new projects in the `_projects` directory
- Include front matter:
  ```yaml
  ---
  layout: project
  title: "Project Title"
  excerpt: "Brief description"
  ---
  ```

## Customization

- Edit `_config.yml` for site-wide settings
- Modify layout files in `_layouts` directory
- Update styles in `assets/css`

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch.
