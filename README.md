# pfolio
Fortified Folio

I borrowed much of this.

## Develop

- `$ npm install` to install node modules locally.
- `$ gulp dev`
	- Opens up a preview of the template in your default browser
	- Watches for changes to core template files and reloads the browser when changes are saved.


#### Gulp Tasks

- `gulp` the default task that builds everything
- `gulp dev` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp sass` compiles SCSS files into CSS
- `gulp minify-css` minifies the compiled CSS file
- `gulp minify-js` minifies the themes JS file
- `gulp copy` copies dependencies from node_modules to the vendor directory
