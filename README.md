Folder Structure Conventions

### Top-level directory layout

    .
    ├── build                   # Compiled files (alternatively `dist`)
    ├── docs                    # Documentation files (alternatively `doc`)
    ├── src                     # Source files (alternatively `lib` for library or `app` for app that doesn't need compiling)
    ├── test                    # Automated tests (alternatively `spec` or `tests`)
    ├── tools                   # Tools and utilities
    ├── LICENSE
    └── README.md

> **Samples**: [jQuery](https://github.com/jquery/jquery) `src`, [Node.js](https://github.com/nodejs/node) `lib` and `src`, [D3.js](https://github.com/mbostock/d3) `src`, [AngularJS](https://github.com/angular/angular.js) `src`, [Adobe Brackets](https://github.com/adobe/brackets) `src`, [three.js](https://github.com/mrdoob/three.js) `src`, [Express](https://github.com/visionmedia/express) `lib`, [Socket.IO](https://github.com/LearnBoost/socket.io) `lib`, [Less.js](https://github.com/less/less.js) `lib`, [Redis](https://github.com/antirez/redis) `src`, [Ace](https://github.com/ajaxorg/ace) `lib`, [Semantic UI](https://github.com/Semantic-Org/Semantic-UI) `src`, [Zepto.js](https://github.com/madrobby/zepto) `src`, [Emscripten](https://github.com/kripken/emscripten) `src`, [RethinkDB](https://github.com/rethinkdb/rethinkdb) `src`, [Bitcoin](https://github.com/bitcoin/bitcoin) `src`, [MongoDB](https://github.com/mongodb/mongo) `src`, [Facebook React](https://github.com/facebook/react) `src`, [Rust](https://github.com/mozilla/rust) `src`, [ASP.NET](https://aspnetwebstack.codeplex.com/SourceControl/latest) `src`, [SignalR](https://github.com/SignalR/SignalR) `src`, [libgit2](https://github.com/libgit2/libgit2) `src`

### Automated tests
    .
    ├── ...
    ├── test                    # Test files (alternatively `spec` or `tests`)
    │   ├── benchmarks          # Load and stress tests
    │   ├── integration         # End-to-end, integration tests (alternatively `e2e`)
    │   └── unit                # Unit tests
    └── ...

> **Examples**: [jQuery](https://github.com/jquery/jquery), [Node.js](https://github.com/joyent/node), [D3.js](https://github.com/mbostock/d3), [AngularJS](https://github.com/angular/angular.js), [Adobe Brackets](https://github.com/adobe/brackets), [three.js](https://github.com/mrdoob/three.js), [Express](https://github.com/visionmedia/express), [Socket.IO](https://github.com/LearnBoost/socket.io), [Less.js](https://github.com/less/less.js), [Bower](https://github.com/bower/bower), [Mozilla PDF.js](https://github.com/mozilla/pdf.js), [Grunt](https://github.com/gruntjs/grunt), [Gulp](https://github.com/gulpjs/gulp), [Semantic UI](https://github.com/Semantic-Org/Semantic-UI), [Zepto.js](https://github.com/madrobby/zepto), [Jade](https://github.com/visionmedia/jade), [RethinkDB](https://github.com/rethinkdb/rethinkdb), [Vagrant](https://github.com/mitchellh/vagrant), [Sails.js](https://github.com/balderdashy/sails), [GitHub Hubot](https://github.com/github/hubot), [Facebook React](https://github.com/facebook/react), [Ansible](https://github.com/ansible/ansible), [ASP.NET](https://aspnetwebstack.codeplex.com/SourceControl/latest), [browserify](https://github.com/substack/node-browserify), [Paper.js](https://github.com/paperjs/paper.js), [Julia](https://github.com/JuliaLang/julia), [Karma](https://github.com/karma-runner/karma)

### Documentation files

    .
    ├── ...
    ├── docs                    # Documentation files (alternatively `doc`)
    │   ├── TOC.md              # Table of contents
    │   ├── faq.md              # Frequently asked questions
    │   ├── misc.md             # Miscellaneous information
    │   ├── usage.md            # Getting started guide
    │   └── ...                 # etc.
    └── ...

> **Examples**: [HTML5 Boilerplate](https://github.com/h5bp/html5-boilerplate) `doc`, [Backbone](https://github.com/jashkenas/backbone) `docs`, [three.js](https://github.com/mrdoob/three.js) `docs`, [GitLab](https://github.com/gitlabhq/gitlabhq) `doc`, [Underscore.js](https://github.com/jashkenas/underscore) `docs`, [Discourse](https://github.com/emberjs/ember.js) `docs`, [Grunt](https://github.com/gruntjs/grunt) `docs`, [Emscripten](https://github.com/kripken/emscripten) `docs`, [RethinkDB](https://github.com/rethinkdb/rethinkdb) `docs`, [RequireJS](https://github.com/jrburke/requirejs) `docs`, [GitHub Hubot](https://github.com/github/hubot) `docs`, [Twitter Flight](https://github.com/flightjs/flight) `doc`, [Video.js](https://github.com/videojs/video.js) `docs`, [Bitcoin](https://github.com/bitcoin/bitcoin) `doc`, [MongoDB](https://github.com/mongodb/mongo) `docs`, [Facebook React](https://github.com/facebook/react) `docs`, [libgit2](https://github.com/libgit2/libgit2) `docs`, [Stylus](https://github.com/LearnBoost/stylus) `docs`, [Gulp](https://github.com/gulpjs/gulp) `docs`, [Brunch](https://github.com/brunch/brunch) `docs`
