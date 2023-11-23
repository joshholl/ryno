# Ryno

Ryno is a fresh and clean them for the [Hugo](https://gohugo.io/) static site generator that was created to suit my needs for a photo blog. It is meant to be exceptionally minimal yet full featured for photo blogs

## Features
* Sass styling with Dart Sass and config based variables
* A clean and fresh soft box-esque like theme (by default)
* Support of tag taxonomies
* Automatic building of gallery cover photos
* Predominately static with minimal javascript
* A mobile first responsive layout
* Short code emoji support [See Hugo docs for full list](https://gohugo.io/quick-reference/emojis/#smileys--emotion)

## Installation
1. Install [Hugo](https://gohugo.io/installation/)
1. Install [Dart Sass](https://sass-lang.com/dart-sass/)
1. Create your site with Hugo ```sh hugo new site your-site-name```
1. Go to your sites directory ```sh cd your-site-name```
1. Remove the default configuration ```sh rm hugo.toml```
1. Initialize your site as a git repo ```sh git init```
1. Install the theme as a git submodule ```sh git submodule add --depth=1 https://github.com/joshholl/ryno.git themes/ryno```
1. Copy the example site as a base ```sh cp -r ./themes/ryno/example-site/* .```
    1. Alternatively just copy the example config ```sh cp ./themes/ryno/config.example.yaml config.yaml```
1. Start Hugo ```sh hugo serve --port 1313```
1. Open a browser to http://localhost:1313

## Configuration
See the [[docs]], more to come soon!

## Users of Ryno

If you use ryno, please add an issue with an "I use this!" label to be added here

