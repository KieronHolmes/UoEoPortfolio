<div align="center">
  <br>
  <h1>University of Essex Online - EPortfolio</h1>
  <strong>A personal E-Portfolio demonstrating my progress through the course.</strong>
</div>
<br>
<p align="center">
  <img src="https://badgen.net/dependabot/KieronHolmes/UoEoPortfolio/334473511?icon=dependabot" alt="Dependabot Badge">
</p>

Welcome to the repository for my personal E-Portfolio, demonstrating progress through the course. This repository should be updated upon completion of each Unit/Module, with details of:
- Data Sourcing
- Artefacts
- Learning Objectives
- Good/Bad Things

## Dependencies
- [Ruby](https://rubyinstaller.org/)
- [Jekyll](https://jekyllrb.com/)
- [TailwindCSS](https://tailwindcss.com/) - Project currently uses the hosted version due to issues with the jekyll-postcss plugin.

## Installation
Please complete the installation steps for Ruby and Jekyll before working on this project. Once complete, please open a command window in the cloned repository folder.

Install dependencies from Gemfile:
``
bundle install
``

## Development
Once the Installation steps have been completed, you can use the following commands to monitor file changes and serve a copy on localhost.

Run Jekyll (Local): 
``
bundle exec jekyll serve
``

Full Test Build:
``
bundle exec jekyll build
``

## Github Pages
This project is hosted on Github Pages, using their standard Jekyll integration for serving static sites. Following each deployment to the ``main`` branch, the main site should be refreshed within a few minutes.

The site is currently configured to listen on ``eportfolio.kieronholmes.me``, with the HTTPS enforced option selected as standard. The SSL certificate is supplied and served directly by Github Pages.