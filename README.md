# Wireless Hobo

Personal tech blog built with [Jekyll](https://jekyllrb.com) and hosted via GitHub Pages.

## Writing a new post

Create a file in `_posts/` named `YYYY-MM-DD-your-title.md` with this front matter:

```markdown
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD
categories: [HomeLab, PowerShell]
tags: [tag1, tag2]
---

Your content here.
```

Images go in `assets/images/` and are referenced as:

```markdown
![Alt text](/assets/images/your-image.png)
```

## Running locally

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000
