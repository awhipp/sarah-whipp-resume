# Sarah Whipp's Resume

[![Netlify Status](https://api.netlify.com/api/v1/badges/499b3cfd-eb91-488d-949c-5ce6274953c8/deploy-status)](https://app.netlify.com/sites/sarah-whipp/deploys)

[![Build Status](https://travis-ci.com/awhipp/sarah-whipp-resume.svg?branch=master)](https://travis-ci.com/awhipp/sarah-whipp-resume)

## Development

After installation, run `yarn install` and then run `yarn start` which will open up a preview of the template in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. You can view the `gulpfile.js` to see which tasks are included with the dev environment.

### Gulp Tasks

- `gulp` the default task that builds everything
- `gulp watch` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp css` compiles SCSS files into CSS and minifies the compiled CSS
- `gulp js` minifies the themes JS file
- `gulp vendor` copies dependencies from node_modules to the vendor directory

You must have npm, yarn, and Gulp installed globally on your machine in order to use these features.
