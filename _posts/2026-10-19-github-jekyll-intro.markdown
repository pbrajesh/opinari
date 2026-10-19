---
layout: post
title: Getting Started with GitHub Pages and Jekyll
date: 2026-10-19
tags: [jekyll, github-pages, tutorial]
---

This post summarizes the steps required to set up a static site using Jekyll and deploy it with GitHub Pages.

## Prerequisites

Before you begin, you need to install Jekyll and Git, and it's highly recommended to use Bundler to manage dependencies and avoid build errors.

1.  **Install Ruby:** Install the Ruby programming language. (See [Installing Ruby](https://www.ruby-lang.org/en/documentation/installation/) for details).
2.  **Install Bundler:** Install Bundler using its official instructions. Bundler helps manage the Ruby gem dependencies for Jekyll.
3.  **Install Jekyll:** Install Jekyll using Bundler, which ensures you have the correct version and dependency structure.

## Creating a Repository for Your Site

You must have a repository on GitHub to host your site.

1.  **Create a Repository:** On GitHub, create a new repository. For a user site, the repository must be named `<username>.github.io`.
2.  **Visibility:** If you are on GitHub Free or GitHub Free for organizations, the repository must be public.
3.  **Configure Source:** Decide whether you will use a dedicated branch/folder for your site's source files, or use a custom GitHub Actions workflow for deployment.

## Creating Your Site

1.  **Local Setup:** Navigate to the directory where you want to store your site's source files on your local machine.
2.  **Initialize Git:** Initialize a local Git repository in that folder.
3.  **Jekyll Configuration:** Create a `_config.yml` file to define your site settings (title, description, theme, plugins, etc.).
4.  **Add Content:** Create your blog posts inside the `_posts/` directory, following the required filename format: `YEAR-MONTH-DAY-title.markdown`.

Remember: GitHub Pages sites are publicly available. Be mindful of any sensitive data in your repository.

For full, detailed instructions, please refer to the official GitHub Pages documentation.
