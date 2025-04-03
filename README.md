---
title: GitHub Pages Deployment
tags: github_actions, ci_cd
---

[![Deploy to GitHub Pages](https://github.com/see7e/github-actions-deployment-workflow/actions/workflows/deploy.yml/badge.svg)](https://github.com/see7e/github-actions-deployment-workflow/actions/workflows/deploy.yml)
[![wakatime](https://wakatime.com/badge/user/64702d7f-73f9-4165-a34d-d5da36c01a1f/project/96c8ebf4-6481-4326-a886-50b69201f91f.svg)

# github-actions-deployment-workflow
> https://roadmap.sh/projects/github-actions-deployment-workflow
> Write a simple GitHub Actions workflow to deploy a static website to GitHub Pages.

The goal of this project is to help you learn the notion of continuous integration and continuous deployment. You will write a simple GitHub Actions workflow to deploy a static website to GitHub Pages.

## Requirements

You are required to write a GitHub action that deploys any changes made to the `index.html` file to GitHub Pages. It should only deploy the file when the `index.html` file is changed.

Here are the steps to get you started:

-   Create a GitHub repository for the project called `gh-deployment-workflow` for example.
-   Repository should contain a simple `index.html` file saying “Hello, GitHub Actions!”
-   It should also have a `README.md` file explaining the project.
-   There should also be a `deploy.yml` file in the `.github/workflows` directory which contains the GitHub Actions workflow to deploy the website to GitHub Pages.
-   Every push to the `main` branch that changes the `index.html` file should trigger the workflow to run and deploy the website to [GitHub Pages](https://docs.github.com/en/pages).
-   Website and any changes you make should be accessible at the GitHub pages URL for the repository e.g. `https://<username>.github.io/gh-deployment-workflow/`.

Stretch goal: You can also make this project more practical e.g. use some sort of a static site generator such as [Hugo](https://gohugo.io/), [Jekyll](https://jekyllrb.com/), [Astro](https://astro.build/) or similar generator to create a more complex website e.g. your own personal portfolio.

___

After finishing this project, you will have a good understanding of the following concepts:

-   GitHub Actions
-   GitHub Pages
-   Continuous Integration and Continuous Deployment
-   Writing GitHub Actions workflows
