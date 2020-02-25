# Dev Portfolio
## Modified from Ryan Fitzgerald's portfolio template

This repo contains an easy-to-customize personal dev portfolio template that was created with Sass and JavaScript. It is lightweight and fully responsive, as well as comes with the Bootstrap grid system and loaded with Font Awesome. The site is static and comes production ready if you just want to add your information and go. Alternatively, you can edit styles, colours, and scripts fairly easily. The site was built as modular as possible to make it easy to shift around styles and content.

### Making Edits / Customizing the Template

To setup, simply fork the repo and run `npm install` in order to get all the Gulp dev dependencies. Next, run `Gulp watch` to compile the Sass and minify the JavaScript. Alternatively, if you don't have Gulp installed globally, you can run the npm script `npm run watch`. Any changes done to the JavaScript (js/scripts.js) or Sass (sass/styles.scss) will be autocompiled and ready to go.

All scripts are within `js/scripts.js` and get minified to `js/scripts.min.js`. All styles are in `sass/styles.scss` and get compiled to `css/styles.css`. Both the minified scripts file and compiled CSS file are what is loaded on the page by default.

At this point, the page is ready to go and you can begin to add your own information and make any needed changes. The sections below  contains a quick breakdown of each of the default sections and how they work.

## License

Completely free (MIT)! See [LICENSE.md](LICENSE.md) for more.
