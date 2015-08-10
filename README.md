GridSide Theme
==============

The GridSide theme is a multi-page portfolio and blog utilizing the
[Materialize][materialize] frontend framework. Medium-style comments may be
added to blog entries using [SideComments.js][sidecomments.js].

The theme contains a main page with a single grid of images representing
different sections of the website. Sections can be marked as blog, project,
contact, or miscellaneous in order to provide slight changes in styling.

Current Materialize version is `0.97.0`.
Current SideComments.js version is `0.0.3`.

Contents
--------

- [Installation](#installation)
- [Getting Started](#getting-started)
    - [The Config File](#the-config-file) 
    - [Adding a Blog Section](#adding-a-blog-section)
        - [Optional - Adding Medium-style Comments with Hull.io](#optional---adding-medium-style-comments-with-hullio)
    - [Adding a Project Section](#adding-a-project-section)
    - [Adding a Contact Section](#adding-a-contact-section)
    - [Adding a Miscellaneous Section](#adding-a-miscellaneous-section)
    - [Nearly Finished](#nearly-finished)
- [Contributing](#contributing)
- [License](#license)

Installation
------------

Inside the folder of your Hugo site run:

    $ mkdir themes
    $ cd themes
    $ git clone https://github.com/rcsenkbeil/grid-side

For more information read the official [setup guide][setup_guide] of Hugo.

Getting Started
---------------

### The Config File ###

Take a look inside the [`exampleSite`][exampleSite] folder of this theme.
You'll find a file called [`config.toml`][config.toml]. To use it, copy the
[`config.toml`][config.toml] in the root folder of your Hugo site. Feel free
to customize this theme as you like.

### Adding a Blog Section ###

TODO

#### Optional - Adding Medium-style Comments with Hull.io ####

TODO

### Adding a Project Section ###

TODO

### Adding a Contact Section ###

TODO

### Adding a Miscellaneous Section ###

TODO

### Nearly Finished ###

In order to see your site in action, run Hugo's built-in local server. 

    $ hugo server -w

Now enter `localhost:1313` in the address bar of your browser.

Contributing
------------

Report any bugs using the [issue tracker][issue_tracker]. Submit your own bug
fixes or feature additions via a [pull request][pull_request].

License
-------

This theme is released under the MIT License. For more information read the
[license][license].

[materialize]: http://www.materializecss.com/
[sidecomments.js]: https://github.com/aroc/side-comments
[setup_guide]: http://gohugo.io/overview/installing/
[exampleSite]: https://github.com/rcsenkbeil/grid-side/tree/master/exampleSite
[config.toml]: https://github.com/rcsenkbeil/grid-side/blob/master/exampleSite/config.toml
[issue_tracker]: https://github.com/rcsenkbeil/grid-side/issues
[pull_request]: https://github.com/rcsenkbeil/grid-side/pulls
[license]: https://github.com/rcsenkbeil/grid-side/blob/master/LICENSE
