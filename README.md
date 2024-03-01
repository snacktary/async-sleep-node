# Async Sleep for Node.js

An uncomplicated async sleep function for node.js.

**BREAKING CHANGE for v1.0.3+** v1.0.3+ is an es6 module. You must use it
with `import` syntax. If your project uses the CommonJS `require` syntax, you
should use v1.0.2.

## Overview

Features:

* uncomplicated
* no dependencies or bloat - it's literally one line of code
* familiar interface
* ESM

## Install

    # For ESM, use v0.0.1 or later
    npm install async-sleep-node --save

    # For CommonJS, use v0.0.1
    npm install async-sleep-node@0.0.1 --save

## Usage

    import asyncSleep from 'async-sleep-node'
    await asyncSleep(1000) // sleep for 1s

## License

MIT
