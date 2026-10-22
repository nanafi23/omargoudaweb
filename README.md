# Web Technologies Learning Website

A Turkish-language educational website introducing web development topics and linking to learning resources. Built by Omar Gouda as a university web technologies project.

## Features

- Introductions to frontend, backend, databases, security, hosting and related web topics.
- Learning-resource cards and external course links.
- Bootstrap navigation and separate contact/registration interface pages.

## Technology

HTML, CSS, JavaScript and Bootstrap 5. Some fonts, icons and framework assets are loaded from external CDNs.

## Run locally

From the repository root:

```bash
python -m http.server 8000
```

Open **http://localhost:8000/index.html/index.html**. The outer `index.html` is currently a directory containing the website; it is not the entry-point file itself.

## Structure

- `index.html/index.html`: main learning page
- `index.html/in.html`: contact interface
- `index.html/in2.html`: registration interface
- `index.html/css/`: stylesheets
- `index.html/js/`: JavaScript
- `index.html/assets/`: images and favicon

## Scope

This is a frontend learning project. The contact and registration screens do not establish a working backend, message delivery or secure account system. External course content belongs to its publishers. UI content is primarily Turkish; this README provides an English project overview.

## Repository organization

This is the selected maintenance copy of the older web technologies repositories under this account. Other `omargouda...` repositories are historical iterations, not separate portfolio projects.

For AI/ML work, see [Turkish sentiment analysis](https://github.com/nanafi23/turkish-sentiment-analysis).
