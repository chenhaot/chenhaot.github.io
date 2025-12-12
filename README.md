# Chenhao Tan's Homepage

This is the source code for Chenhao Tan's personal website, built with [Hugo](https://gohugo.io/) static site generator.

## About

This website showcases research, publications, talks, and other academic work by Chenhao Tan, an associate professor at the University of Chicago specializing in human-centered AI, natural language processing, and computational social science.

## Building the Site

### Prerequisites

- [Hugo](https://gohugo.io/installation/) (extended version recommended)
- Git

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/chenhaot/chenhaot.github.io.git
   cd chenhaot.github.io
   ```

2. Initialize and update the theme submodule:
   ```bash
   git submodule update --init --recursive
   ```

3. Start the Hugo development server:
   ```bash
   hugo server
   ```

4. View the site at `http://localhost:1313`

### Building for Production

To build the static site:

```bash
hugo
```

The generated site will be in the `public/` directory.

## Deployment

This site is deployed to GitHub Pages. The deployment is automated via GitHub Actions (see `.github/workflows/` for configuration).

## Structure

- `content/` - Markdown content files for pages, papers, talks, etc.
- `static/` - Static assets (images, PDFs, etc.)
- `themes/` - Hugo theme (hugo-xmin)
- `hugo.yaml` - Hugo configuration file

## License

Content © Chenhao Tan. All rights reserved.

## Contact

For questions or issues, please contact via the information provided on the [website](https://chenhaot.github.io/contact).
