# Ruby on Rails presentation based on Reveal JS

## Installation

This library shows what can be done with the awesome [Reveal JS](https://github.com/hakimel/reveal.js) library.
Also, it contains a boiler plate presentation example for Ruby on Rails promotion purposes.

### Basic setup

The core of this showcase library is very easy to install. You'll simply need to download a copy of this repository and open the index.html file directly in your browser.

1. Download the latest version of reveal.js from <https://github.com/ruby-on-rails-presentation>

2. Unzip and replace the example contents in index.html with your own

3. Open index.html in a browser to view it


### Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/) (1.0.0 or later)

1. Clone the ruby-on-rails-presentation repository
   ```sh
   $ git clone https://github.com/ralfclaassens/ruby-on-rails-presentation.git
   ```

1. Navigate to the ruby-on-rails-presentation folder
   ```sh
   $ cd ruby-on-rails-presentation
   ```

1. Install dependencies
   ```sh
   $ npm install
   ```

1. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

1. Open <http://localhost:8000> to view your presentation

   You can change the port by using `npm start -- --port 8001`.


### Folder Structure
- **css/** Core styles without which the project does not function
- **js/** Like above but for JavaScript
- **plugin/** Components that have been developed as extensions to reveal.js
- **lib/** All other third party assets (JavaScript, CSS, fonts)


## License

MIT licensed

Copyright (C) 2016 Ralf Claassens
