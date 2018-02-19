# todo

[![Greenkeeper badge](https://badges.greenkeeper.io/marcusasplund/hyperapp-todo-simple.svg)](https://greenkeeper.io/)
[![GitHub issues](https://img.shields.io/github/issues/marcusasplund/hyperapp-todo-simple.svg)](https://github.com/marcusasplund/hyperapp-todo-simple/issues)
[![Build status](https://travis-ci.org/marcusasplund/hyperapp-todo-simple.svg?branch=master)](https://travis-ci.org/marcusasplund/hyperapp-todo-simple)
[![dependencies](https://david-dm.org/marcusasplund/hyperapp-todo-simple.svg)](https://david-dm.org/marcusasplund/hyperapp-todo-simple)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/1fb89f04b2a948f6bba5071519f4df0b)](https://www.codacy.com/app/marcusasplund/hyperapp-todo-simple?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=marcusasplund/hyperapp-todo-simple&amp;utm_campaign=Badge_Grade)
[![Stack Share](http://img.shields.io/badge/tech-stack-0690fa.svg?style=flat)](http://stackshare.io/marcusasplund/hyperapp-todo-simple)


[![Standard - JavaScript Style Guide](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

[Hyperapp](https://github.com/hyperapp/hyperapp) crud todo

## [demo](https://pap.as/hyperapp/todo/)

Add some todos, click buttons to delete or toggle state, tap or click text in todo to edit.

Offline support with service worker

Also checkout [hyperapp-todo-parcel](https://github.com/marcusasplund/hyperapp-todo-parcel)

## installation

````bash
    $ git clone https://github.com/marcusasplund/hyperapp-todo-simple.git

    $ cd hyperapp-todo-simple

    $ yarn

    $ yarn start
````

Open up application at http://localhost:4000/ in browser

## build a release

````bash
    $ yarn run build

````
This will generate a release directory with your minified/rev'd assets.


## serve static

````bash
    $ yarn run serve

````

This will use serve to statically serve your app from the release directory.

## Credits

The rollup and taskr config is based on https://github.com/tzellman/hyperapp-boilerplate
