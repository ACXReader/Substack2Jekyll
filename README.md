# Substack2Jekyll

A fork of Substack2Markdown for github pages. Allows github actions to update the site on an interval.

How to use:
- Fork this repo
- Enable github pages (select "Github Actions" in `Settings>Pages>Build and deployment>Source`)
- In `site-updater.yml`, replace `YOUR_SITE_HERE` with the url of the substack site you want to clone
- Drag `site-updater.yml` to `.github/workflows`
- Done!
