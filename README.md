# My Favorite Quotes

A static site using Hugo deployed to Netlify with Decap CMS which I maintain to keep a record of all my favorite quotes from different books, shows, movies, etc.

## How to
- Deployment Guide: [Hugo + Netlify](https://gohugo.io/hosting-and-deployment/hosting-on-netlify/)
- Admin Panel Guide: [Decap CMS](https://decapcms.org/docs/add-to-your-site/)

Theme used: https://themes.gohugo.io/themes/hugo-paper/

## Gotchas
- Make sure the Hugo config file is called "config.toml/yaml" and not "hugo.toml/yaml"
- Make sure the theme is added as a submodule
- Make sure the `baseURL` in the Hugo config is set correctly otherwise for some reason the theme doesn't load.
