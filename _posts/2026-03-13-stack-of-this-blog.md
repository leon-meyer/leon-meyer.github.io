---
layout: post
title: "Stack of this Blog"
date: 2026-03-13
tags: [dev, web, github, ruby, jekyll]
---

This might be a bit meta, but my first blog post is about the tech stack this blog is based on.

I wanted it to be as simple as possible to maintain while having control over the styling and accessibility.

Since I am a web dev, GitHub Pages seems like a simple yet powerful solution.  
It is free for both reader and writer, ad-free, and linked to my GitHub profile.

As my framework I use Ruby and Jekyll.  
It is natively supported by GitHub Pages and only requires Ruby to be installed on your local machine and the following Gemfile in the repo.

```ruby
source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
```

With this I can serve the blog locally with bundle exec jekyll serve and see the changes I made before pushing them to GitHub.

## Project Structure

My initial folder structure for this blog is the following.
If you are interested in whether the structure has changed, follow the link[Repo of Blog](https://github.com/leon-meyer/leon-meyer.github.io).

```
leon-meyer.github.io
│   _config.yaml
│   .gitignore
│   .ruby-version
│   blog.md
│   favicon.ico
│   Gemfile
│   Gemfile.lock
│   index.md
│   README.md
│
└───_layouts
│   │   default.html
│   │   post.html
│
└───_posts
│   │   YYYY-MM-DD-post-1.md
│   │   YYYY-MM-DD-post-2.md
│   │   ...
│
│
└───assets
    │   style.css
```

This lets me quickly add posts by simply adding a new .md file.
My templates and styles are simple yet modern by design.

## Sources

- [Jekyll](https://jekyllrb.com/)
- [Ruby](https://www.ruby-lang.org/de/)
- [Github Pages](https://pages.github.com/)
