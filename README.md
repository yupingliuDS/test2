# devops-github-pages-template
A template repository intended to provide a starting point for GitHub Pages development at Takeda.

[![Build Status](https://github.com/oneTakeda/devops-github-pages-template/workflows/Deploy%20Jekyll%20with%20GitHub%20Pages%20dependencies%20preinstalled/badge.svg)](https://github.com/oneTakeda/devops-github-pages-template/actions)

## Install

Request a new GitHub Repository via [Issue Form](https://github.com/oneTakeda/devops-repo-automation/issues/new?assignees=&labels=pages&projects=&template=a2-repo-create-request-form.yml&title=%5BGitHub+Repository+Creation+Request%5D%3A+Create%20Repo%20from%20Pages%20Template) and select this template from the dropdown along with the rest of the information needed.

## Usage

### Publishing
1. From the Settings of your new repository, open the Pages configuration
1. Under "Source", select GitHub Actions to use with this template
1. Modify the "Custom Domain" if needed and click save.
1. Once the workflow has run, this page will also show your live URL and include a "Visit Site" button.
1. From the main page of your repository, edit your "Repository Details" by clicking the Gear icon next to About on the right side.
2. Under the "Website" section, check the box to "Use your GitHub Pages Website" and click the "Save changes" button.

### File configuration

1. Update `_config.yml` as needed with information such as the Title and Description of your website
1. Customize the *.markdown files
1. Customize the 404.html page
1. From the `_posts/` directory, update the markdown files and create new ones

## References
* https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll
