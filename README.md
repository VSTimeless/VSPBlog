# Volodymyr's Personal Website

This repository contains the source code for my personal website built with [Hugo](https://gohugo.io/), a fast and modern static site generator.

## Overview

This website showcases my skills, projects, and interests as an Electrical Engineering student. It features a clean, responsive design and is hosted on GitHub Pages.

## Features

- Responsive design that works on mobile, tablet, and desktop
- Project portfolio with detailed case studies
- Blog for sharing technical insights and experiences
- Sections for personal interests (books, podcasts, home labbing, gym, photography)
- Contact form for easy communication

## Technology Stack

- **Static Site Generator**: [Hugo](https://gohugo.io/)
- **Hosting**: [GitHub Pages](https://pages.github.com/)
- **CSS**: Custom CSS with responsive design
- **JavaScript**: Minimal vanilla JS for interactive elements
- **Form Handling**: [Formspree](https://formspree.io/) for the contact form

## Local Development

To run this website locally:

1. **Install Hugo**:
   ```bash
   # macOS with Homebrew
   brew install hugo
   
   # Windows with Chocolatey
   choco install hugo -confirm
   
   # Linux
   sudo apt-get install hugo
   ```

2. **Clone the repository**:
   ```bash
   git clone https://github.com/volodymyr/volodymyr.github.io.git
   cd volodymyr.github.io
   ```

3. **Run the development server**:
   ```bash
   hugo server -D
   ```

4. **View the site**:
   Open your browser to http://localhost:1313

## Deployment

The website is automatically deployed to GitHub Pages when changes are pushed to the main branch, using a GitHub Actions workflow defined in `.github/workflows/hugo.yml`.

## Content Management

All content is written in Markdown and stored in the `content/` directory:

- `content/about/` - About me information
- `content/projects/` - Project case studies
- `content/blog/` - Blog posts
- `content/interests/` - Personal interests pages
- `content/contact/` - Contact page

Images are stored in the `static/images/` directory.

## Customization

To customize this site:

- Edit the configuration in `hugo.toml`
- Modify the HTML templates in `themes/volodymyr-theme/layouts/`
- Update styles in `static/css/main.css`

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- [Hugo](https://gohugo.io/) for the static site generator
- [Formspree](https://formspree.io/) for form processing
- [GitHub Pages](https://pages.github.com/) for hosting
- Design inspiration from [Cursor.com](https://www.cursor.com/blog) 