# Intro to GraphQL [![Build Status](https://travis-ci.org/hakimel/reveal.js.svg?branch=master)](https://travis-ci.org/hakimel/reveal.js) <a href="https://slides.com?ref=github"><img src="https://s3.amazonaws.com/static.slid.es/images/slides-github-banner-320x40.png?1" alt="Slides" width="160" height="20"></a>

Here it is, Intro to GraphQL. Presentation I presented at devjs #1 Łódź and GDevs #14 Lublin. Make good use of it.

### TODOs 

- add n+1 queries slides
- refactor `index.html` formatting and styles

### Setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/) (4.0.0 or later)

2. Install dependencies
   ```sh
   $ npm install
   ```

3. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

4. Open <http://localhost:8000> to view your presentation

   You can change the port by using `npm start -- --port=8001`.
