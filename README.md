# Forked from reveal.js [![Build Status](https://travis-ci.org/hakimel/reveal.js.svg?branch=master)](https://travis-ci.org/hakimel/reveal.js) <a href="https://slides.com?ref=github"><img src="https://s3.amazonaws.com/static.slid.es/images/slides-github-banner-320x40.png?1" alt="Slides" width="160" height="20"></a>

A framework for easily creating beautiful presentations using HTML. [Check out the live demo](http://lab.hakim.se/reveal-js/).

## Table of contents
- [Installation](#installation)
  - [Basic setup](#basic-setup)
  - [Full setup](#full-setup)
  - [Folder Structure](#folder-structure)

## Installation

The **basic setup** is for viewing presentations only. The **full setup** gives you access to all reveal.js features and plugins such as speaker notes as well as the development tasks needed to make changes to the source.

### Basic setup

The core of reveal.js is very easy to install. You'll simply need to download a copy of this repository and open the index.html file directly in your browser.

1. Download the latest Deck from <https://github.com/andrewdc/pds-overview-deck/archive/master.zip>

2. Open index.html in a browser to view it


### Full setup


1. Install [Node.js](http://nodejs.org/) (1.0.0 or later)

2. Clone this repository
   ```sh
   $ git clone git@github.com:andrewdc/pds-overview-deck.git
   ```

3. Navigate to the reveal.js folder
   ```sh
   $ cd pds-overview-deck.js
   ```

4. Install dependencies
   ```sh
   $ npm install
   ```

5. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

6. Open <http://localhost:8000> to view your presentation

   You can change the port by using `npm start -- --port 8001`.
