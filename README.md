# Personal Portfolio Website

## Overview

This repository contains my personal portfolio website, which showcases my skills and projects in software engineering and DevOps. The website is built using HTML, CSS, and JavaScript, and utilizes GitHub Actions for continuous deployment to GitHub Pages.

## Setting Up GitHub Actions

### Creating Workflow File
Created a GitHub Actions workflow file `.github/workflows/deploy.yml` to automate the deployment process.

### Configuring GitHub Actions
- Used the `peaceiris/actions-gh-pages` action to publish changes to the `gh-pages` branch.
- Specified the `GITHUB_TOKEN` for authentication.

### Workflow Triggers
Configured the workflow to trigger on pushes to the `main` branch.

## Deploying to GitHub Pages

### Enabling GitHub Pages
In the repository settings, I enabled GitHub Pages to serve from the `gh-pages` branch.

### Automated Deployment
Each time I push changes to the `main` branch, GitHub Actions automatically deploys the latest version of my portfolio to GitHub Pages.

## Final Review

### Live Site
Verified the live site at `https://SuranSandeepa.github.io/suran-sandeepa/` to ensure that everything is displayed correctly and is functional.



