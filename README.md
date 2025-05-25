# Personal Website Content

This repository contains all content for Sribhuvan Reddy Yellu's personal website including:

- Personal information and bio
- Work experience and research
- Projects portfolio
- Blog posts (AI-generated and manual)
- Images and media assets

## Structure

```
├── personal/
│   ├── bio.json          # Personal information and contact
│   ├── experience.json   # Work experience
│   ├── research.json     # Research experience
│   └── skills.json       # Technologies and skills
├── projects/
│   ├── index.json        # Projects listing
│   └── images/           # Project images
├── blog/
│   ├── index.json        # Blog posts index
│   ├── posts/            # Individual blog posts
│   └── images/           # Blog images
└── images/               # General images (logos, etc.)
```

## Usage

This content is consumed by the main website via the GitHub API. The website includes:
- Caching for performance
- Fallback mechanisms for reliability
- Error handling for network issues

## AI Blog Pipeline

The AI blog generation system automatically commits new posts to this repository following the established JSON structure.

## Image Management

All images are stored in appropriate subdirectories:
- `personal/` - Profile and personal images
- `projects/` - Project screenshots and demos
- `blog/images/` - Blog post hero images
- `images/` - Company logos and general assets

## Content Updates

Content can be updated by:
1. Direct editing via GitHub web interface
2. Pull requests for collaborative editing
3. Automated commits from the AI blog pipeline
4. Manual commits for immediate updates
