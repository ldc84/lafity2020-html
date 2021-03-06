# LAFITY 2020 HTML 
This provides an example Gulp.js project which automates CSS tasks including:

* optimizing images
* compiling Sass .scss files
* handling and inlining assets
* automatically appending vendor prefixes
* removing unused CSS selectors
* minifying CSS
* reporting file sizes
* outputing sourcemaps for use in browser devtools
* live-reloading CSS in a browser when source files change.
* HTML include Template.


## Installation
To install on any Linux, Mac OS or Windows system, ensure [Node.js](https://nodejs.org/) is installed then clone the repository:

```bash
git clone https://github.com/ldc84/lafity2020-html.git
```

Navigate to the folder:

```bash
cd lafity2020-html
```

Install dependencies:

```bash
npm i gulp -g
npm i
```

Note that module versions have been fixed to guarantee compatibility. Run `npm outdated` and update `package.json` as necessary.


## Usage
Run in live-reloading development mode:

```bash
gulp
```

Navigate to `http://localhost:9090/` or the `External` URL if accessing from another device. Further instructions are shown on the index page.

[http://lafity.live](http://lafity.live/)