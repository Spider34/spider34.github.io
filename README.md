# Particle Jekyll Theme

This is a simple and minimalist template for Jekyll designed for developers that want to show of their portfolio.

The Theme features:

- Gulp
- SASS
- Sweet Scroll
- Particle.js
- BrowserSync
- Font Awesome and Devicon icons
- Google Analytics
- Info Customization

## Basic Setup

1. [Install Jekyll](http://jekyllrb.com)
2. Fork the [Particle Theme](https://github.com/nrandecker/particle/fork)
3. Clone the repo you just forked.
4. Edit `_config.yml` to personalize your site.

## Site and User Settings

You have to fill some informations on `_config.yml` to customize your site.

```
# Site settings
description: A blog about me
baseurl: "" # the subpath of your site, e.g. /blog/
url: "http://localhost:3000" # the base hostname & protocol for your site

# User settings
username: Spider
user_description: Student and Software Developer
user_title: Rakesh Kumar
email: rakekum34@gmail.com
linkedin : rakesh-kumar-2b05a4138
github_username:  spider34
```

**Don't forget to change your url before you deploy your site!**

## Color and Particle Customization
- Color Customization
  - Edit the sass variables
- Particle Customization
  - Edit the json data in particle function in app.js
  - Refer to [Particle.js](https://github.com/VincentGarreau/particles.js/) for help

## Running the blog in local

In order to compile the assets and run Jekyll on local you need to follow those steps:

- Install [NodeJS](https://nodejs.org/en/download/package-manager/)
- Install jekyll
- Run 'jekyll serve'
