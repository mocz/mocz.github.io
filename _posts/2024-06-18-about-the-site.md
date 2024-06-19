---
layout: post
title: "About the Site"
permalink: /about-the-site/
gh-badge: [star, fork, follow]
tags: [about-site,github,cicd]
comments: true
mathjax: true
author: Carlo Goleta
---

# Portfolio Site: Tech Stack & CI/CD with Jekyll and GitHub Pages

<section id="projects" class="py-5 text-center">
  <!-- <h2>My Work</h2>
  <p>Here are some examples of projects I've worked on:</p> -->
  <div class="container d-flex justify-content-between flex-wrap">
    <!-- Include other project cards here -->
    <div class="card mb-4" style="width: calc(100% - 1rem);">
      <img src="/assets/img/gh-cicd.png" alt="Vortex.ph" width="100%">
      <!-- Include project details here -->
    </div>
  </div>
</section>


In this blog post, we will discuss the technology stack used to build my personal portfolio site using Jekyll and how I set up Continuous Integration (CI) and Continuous Delivery (CD) using GitHub Actions.

## Technology Stack

My portfolio site is built using a combination of technologies that allow me to create an engaging, responsive, and visually appealing web experience:

1. **Jekyll**: [A static website generator written in Ruby](https://jekyllrb.com/), which converts markdown files into HTML pages. It also supports various plugins for additional functionality like RSS feeds or custom themes.
2. **Markdown**: For writing the content of my site using a simple and easy-to-learn syntax.
3. **GitHub Pages**: [For hosting the static files generated by Jekyll](https://pages.github.com/), making it easily accessible to the public.
4. **Visual Studio Code (VSCode)**: My preferred code editor for writing, debugging, and editing the source markdown files and configuration settings.
5. **Ruby & Bundler**: To manage dependencies and run scripts during the build process using Jekyll's `bundle install` command.
6. **GitHub Repository**: For version control of my portfolio site's content, themes, plugins, and other configurations.
7. **Font Awesome Icons**: [A popular icon library](https://fontawesome.com/) used for adding icons to enhance the visual appeal of my website.
8. **Google Analytics**: To track user behavior and gain insights into visitor demographics, interests, and interactions with my site.

## CI/CD with GitHub Pages & GitHub Actions

GitHub Pages is a free static web hosting service provided by GitHub for open-source projects or personal websites. In combination with GitHub Actions, I can automate the process of building and deploying my Jekyll site whenever changes are pushed to the repository:

1. **Git Push**: Whenever I push changes to my main branch, GitHub Actions automatically triggers a workflow.
2. **Checkout Repository**: The first step in the workflow checks out the latest version of your repository.
3. **Install Dependencies**: Using `bundle install`, it ensures that all required dependencies are installed for Jekyll to build and run correctly.
4. **Build & Generate Static Files**: Running `jekyll build` generates static HTML files from markdown content, themes, plugins, and other configurations.
5. **Deploy to GitHub Pages**: The final step in the workflow deploys the newly generated static files to your personal GitHub Pages site by updating the `gh-pages` branch with the latest changes. This ensures that my portfolio website is always up-to-date and accessible at all times.

By using CI/CD with Jekyll, GitHub Pages, and GitHub Actions, I can ensure that my portfolio site remains stable, secure, and functional while also allowing me to easily deploy new features or updates whenever desired.