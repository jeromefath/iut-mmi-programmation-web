# Programmation web (S4)
Slides à destination de l'IUT MMI de l'Université Savoie Mont Blanc. Cette présentation a été réalisée à l'aide du framework reveal.js.
Pour consulter les slides en ligne, rendez-vous à l'adresse : [http://jeromefath.github.io/iut-mmi-programmation-web/](http://jeromefath.github.io/iut-mmi-programmation-web/)

Reaveal.js is a framework for easily creating beautiful presentations using HTML. [Check out the live demo](http://lab.hakim.se/reveal-js/).

## Installation

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/) (4.0.0 or later)

1. Clone the repository
   ```sh
   $ git clone https://github.com/jeromefath/iut-mmi-programmation-web.git
   ```

1. Navigate to the reveal.js folder
   ```sh
   $ cd iut-mmi-programmation-web
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

   You can change the port by using `npm start -- --port=8001`.