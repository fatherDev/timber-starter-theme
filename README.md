# The Timber Starter Theme

The "\_s" for Timber: a dead-simple theme that you can build from. The primary purpose of this theme is to provide a file structure rather than a framework for markup or styles. Configure your Sass, scripts, and task runners however you would like!

[![Build Status](https://travis-ci.org/timber/starter-theme.svg)](https://travis-ci.org/timber/starter-theme)

## What's here?

`templates/` contains all of your Twig templates. These pretty much correspond 1 to 1 with the PHP files that respond to the WordPress template hierarchy. At the end of each PHP template, you'll notice a `Timber::render()` function whose first parameter is the Twig file where that data (or `$context`) will be used. Just an FYI.

If you want to create new page or component look at front-page example.

`bin/` and `tests/` ... basically don't worry about (or remove) these unless you know what they are and want to.

`.env` file to set credentials to live reload.

`gulpfile.js` and `webpack.config.js` to deal with js and scss.

## Developement

After cloning this theme - in your root folder run `npm install` to install all nesecary node.js (`node version 14.16.1`) dependencies. Then run `composer install` to install all composer necesary dependencies (ex. Timber or Dumeper). Create your `.env` file.

Run `npm start` to watch all changes in browser.

Run `npm build` to build and minify all files.

Before running `npm build` update version in `style.css` file to prevent site to use old cached version.

## Other Resources

The [main Timber Wiki](https://github.com/jarednova/timber/wiki) is super great, so reference those often. Also, check out these articles and projects for more info:

- [This branch](https://github.com/laras126/timber-starter-theme/tree/tackle-box) of the starter theme has some more example code with ACF and a slightly different set up.
- [Twig for Timber Cheatsheet](http://notlaura.com/the-twig-for-timber-cheatsheet/)
- [Timber and Twig Reignited My Love for WordPress](https://css-tricks.com/timber-and-twig-reignited-my-love-for-wordpress/) on CSS-Tricks
- [A real live Timber theme](https://github.com/laras126/yuling-theme).
- [Timber Video Tutorials](http://timber.github.io/timber/#video-tutorials) and [an incomplete set of screencasts](https://www.youtube.com/playlist?list=PLuIlodXmVQ6pkqWyR6mtQ5gQZ6BrnuFx-) for building a Timber theme from scratch.
