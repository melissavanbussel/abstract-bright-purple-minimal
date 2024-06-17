# Project Title

This is a sample Quarto project generated with the following theme:Abstract bright purple minimal## How to Use

1. In RStudio, use `New project > Existing directory` to create an R project for the generated outputs folder
2. If pushing to GitHub, run `renv::init()` when R project is opened in RStudio, and use `renv::status()` and `renv::snapshot()` as project is modified in order to keep package information updated
3. If pushing to GitHub, run `git init` inside the project directory and then commit and push
4. on GitHub, add a `gh-pages` branch and ensure that `gh-pages` is selected under `Settings > Pages > Deploy from a branch`.
5. Edit the `slides.qmd` file to add your content.
6. Customize the `custom.scss` file to change the theme.
7. When rendering locally, make a copy of all images in the `images` folder and put them into `slides_files/libs/revealjs/dist/theme`

## Generated Content

This project includes:
- A `slides.qmd` file with sample slides.
- A `custom.scss` file for theme customization.
- An `images` folder with AI-generated background images, based on your user prompt.
- A `publish.yml` file that will configure GitHub Actions to automatically publish your slides to GitHub Pages
- A `.gitignore` to avoid accidentally uploading unnecessary files to GitHub

