# Hello Front End Devs

SMACSS powered HTML5 Boilerplate (SpH5B) is a boilerplate for front end developers. It’s based on [HTML5 Boilperplate](https://html5boilerplate.com) and refactored to work in [Jade](http://jade-lang.com) and [Sass](http://sass-lang.com) with some [SMACSS](http://smacss.com).

## Why now this?

I use the HTML5 Boilerplate for nearly every front end project as a quick and simple starting point. Adding the SMACSS (BEM will follow in v1.1) methodology to my own front end mojo and to this personalised boilerplate, I started a while ago, truly boosted my development. Timewise and codewise. If this boilerplate is as helpful to you as it is to me … [Hooray](http://media.giphy.com/media/ns8FcEX37Ha5G/giphy.gif) :-)

## How to …

Basically just download or fork this repo and start writing down your code! Edit all your html files and stylings in the `_source` folder and compile them. Jade and Sass will need some ‘magic’ help to compile their files, everything else works nicely out of the box.

### Install & watch via the command line

Install Jade via npm

    npm install jade

and Sass via Ruby Gems

    gem install sass

Watch the files you are working with in the `_source` folder and compile them into `_site`. More on the folders in a second.

### Install & watch via there’s an app for that

If you and your command line are not the best friends (yet) and your are asking yourself: Is there an app for that? The answer is YES, more than one ;-) There are quite a few good apps on the web that help you with all the compiling mumbo-jumbo. My favourite one is [CodeKit](http://incident57.com/codekit/) as it does a lot more than compiling files and I use it on most front end projects. Give it a try, it comes with a 15 days trial.

### Intention & usage of the folder structure

There are basically two folders. The `_source` folder is the home to the Jade and Sass files. HTML5 Boilerplate’s html and CSS files are inside as a starting point.

    /_source/
    |-- _jade                 # The Jade template files to edit
    |   |-- 404.html          # HTML5 Boilerplate’s 404 page, Jade styled
    |   `-- index.html        # HTML5 Boilerplate’s index file, Jade styled
    |-- _sass                 # The mighty SMACSS adapted directory
    |   |-- 1-tools           # External resources like Normalize.css and Bourbon
    |   |-- 2-base            # Fundamental defauls for your site
    |   |-- 3-layouts         # Sections of your pages like header and footer
    |   |-- 4-modules         # Reusable modules like call to actions
    |   |-- 5-states          # Actives and other states
    |   |-- 6-pages           # Page style, the classy theming way
    |   |-- 7-utilities       # Utilities needed
    |   |-- 8-development     # Temporary development hacks
    |   `-- style.sass        # One to import them all, one to compile
    `-- icons.sketch          # Template for your system icons

The `_site` folder is the output I use for the compiled files. This folder is the root that gets deployed later. `_site` already contains some basic and compiled files, mainly from HTML5 Boilerplate:

    /_site/                   # Home to your compiled web project
    |-- assets                # All your assets in one place
    |   |-- css               # Compile your Sass files here
    |       `-- style.css     # Your compiled stylesheet
    |   |-- img               # Your images folder
    |   `-- js                # Home to your Javascript files
    |       `-- vendor        # External Javascript files go here
    |-- index.html            # The compiled index file
    `-- ...                   # Most of HTML5 Boilerplate’s files

## What’s inside

SpH5B is based on and includes the resources listed below. Version numbers indicate the current version used for SpH5B. Thanks to all the fine people who made these great resources!

### Code

- [Bourbon v4.2.2](http://bourbon.io): a lightweight mixin library for your Sass
- [HTML5 Boilperplate v5.2.0](https://html5boilerplate.com): the core as you might have guessed
- [jQuery v1.11.3](https://jquery.org/): everybody knows jQuery, right?
- [Modernizr v2.8.3](http://modernizr.com): detect HTML5 and CSS3 features and style them
- [Normalize.css v3.0.2](http://necolas.github.io/normalize.css/): HTML5-ready CSS reset

### Languages / Syntaxes

- [Jade](http://jade-lang.com): a high performance node template engine
- [Sass](http://sass-lang.com): one of the most known and mature CSS preprocessors

### Methodologies

- [SMACSS](http://smacss.com) is a style guide based CSS library that helps you to structure your CSS files and folders in a logic, scalable and brilliant manner supporting your development, workflow and maintance. If you’re a front end coder you really have to get [Jonathan Snook’s](https://twitter.com/snookca) book. You will love it!

## Version history

**Version 1.0** (28/06/15)

- Finally cleaned up this repo and published it

## Feedback

If you find any errors or missing parts please [create a new issue](https://github.com/kayspiegel/smacss-powered-html5-boilerplate/issues/new). That makes tracking and adding those easy.

And if you feel like getting in touch, have a cup of coffee or code something together [twitter](http://twitter.com/kay_spiegel) or [email](mailto:hello@kayspiegel.com) might be the best ways.

## License

SpH5B is licensed under the [MIT license](http://opensource.org/licenses/MIT).
