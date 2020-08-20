# Playlist Cleaner for Spotify

Want to remove unavailable songs? Or duplicates? Or maybe songs from a specific artist? Say no more... the Playlist Cleaner for Spotify is here to help

# Contributing

If you want to work on it then fork this project. 

Feel free to submit PRs!

## Spotify Token Swap
You need a hosted .php file for the token swap. I provide a example later.

## Generate CSS/JS files

You need sass to generate the css file and you need uglify-merge-js to generate the js file.

### Install

You can install the packages with npm like this:

`npm i -g uglify-merge-js sass`

###  Generate the files
JS

`uglify-merge -s './assets/javascripts' -o '../../dist/js/scripts.min.js'`

CSS

`sass --style compressed  assets/scss/style.scss:dist/css/style.min.css`

CSS & JS

`uglify-merge -s './assets/javascripts' -o '../../dist/js/scripts.min.js' && sass --style compressed assets/scss/style.scss:dist/css/style.min.css`

## Please keep following in mind...

- Try to avoid additional dependencies
- Respect the Spotify Guidelines
- Keep it simple

# Credits

- Marco Sadowski
- Signika Font by Anna Giedryś (licensed under the SIL Open Font License, Version 1.1)
- spotify-web-api-js by José M. Pérez (licensed under the MIT License)
