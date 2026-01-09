# adiii.me

Personal website built with Jekyll.

## Development

### Prerequisites

- Ruby 3.0 or higher
- Bundler

### Setup

1. Install dependencies:
```bash
bundle install
```

2. Build the site:
```bash
bundle exec jekyll build
```

3. Serve the site locally:
```bash
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`

### Adding Blog Posts

Create new posts in the `_posts` directory with the format: `YYYY-MM-DD-title.md`

Example:
```markdown
---
layout: post
title: "My New Post"
date: 2026-01-09 00:00:00 +0000
categories: blog
---

Your content here...
```

## Deployment

The site can be deployed to GitHub Pages or any static hosting service. The built site will be in the `_site` directory.