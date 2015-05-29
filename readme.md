# SASS Boilerplate

SASS Boilerplate is a no-bullshit UI framework that is built for performance and compatibility.

It's meant for  designers and developers who care about the [bloat modern front-end frameworks like Bootstrap and Foundation are  introducing](http://yycjs.com/not-bootstrap/), and aims to solve these issues with a simplistic,
modular approach.

Similar to [organic SCSS](https://github.com/krasimir/organic-css), this project uses placeholders wherever possible, so as to reduce duplicate code.  As a
result, your css parses **slightly** faster, and you have to maintain less code.


## Quick start

Choose one of the following options:

1. Use the [yeoman generator](https://github.com/srsgores/generator-sass-boilerplate)
2. (**New!**) Install using [bower](http://bower.io") - `bower install sassboilerplate`
3. Clone the git repo — `git clone
   https://github.com/srsgores/sass-boilerplate.git` - and checkout the [tagged
   release](https://github.com/srsgores/SASS-boilerplate/releases) you'd like to
   use.


## Features

* SASS-ready. Use the new elements with confidence.
* Cross-browser compatible: support IE8 and potentially IE7.  Hacks are ready to go, and can be disabled easily.
* Designed with progressive enhancement in mind.
* NO MORE [Normalize.css](http://necolas.github.com/normalize.css/)!  You don't have to worry about normalization
because the defaults are already in the base style via ``@extends``
* The latest [jQuery](http://jquery.com/) and [Modernizr](http://modernizr.com/) build for feature detection via
[bower](http://bower.io).
* Modularized component-based approach, with minimal coupling only to helpers, mixins,
and compass.  Mix and match them as you wish
* WAI-ARIA compliant, with roles.  [Start caring about accessibility today](http://seangoresht.com/index.php/blog/item/design-for-the-blind-wai-aria-explained).
* [Icomoon](https://icomoon.io) icons included, with better, faster approach to loading icons
* CSS3-animation-ready with [companimation](https://github.com/mikefowler/companimation)
* Placeholder fixes, placeholder styling
* Media query-ready, with grid system placeholders already implemented.  Just extend a ``%col``, and you're good to go.
* Flexible grid placeholder naming scheme.  Call your columns and rows whatever you want,
and don't worry about bloat being output because you have placeholders!  Once you extend,
they fold to a single-column grid!
* Useful placeholders like ``%small-margin-top``, ``%large-padding-top``, and so forth.
* Fluid, extensible grid system with working media queries via susy grid system
* Apache server caching, compression, and other configuration defaults for
  Grade-A performance.
* Cross-domain Ajax and Flash.
* "Delete-key friendly." Easy to strip out parts you don't need.
* Extensive inline and accompanying documentation.


## Documentation

Take a look at the [documentation table of contents (in progress)](doc/TOC.md). This
documentation is bundled with the project, which makes it readily available for
offline reading and provides a useful starting point for any documentation you
want to write about your project.


## Contributing

Anyone and everyone is welcome to [contribute](CONTRIBUTING.md). Hundreds of
developers have helped make the SASS Boilerplate what it is today.
