# Node.js Clients for SmartDataCenter UFDS

Repository: <git@github.com:joyent/node-ufds>
Browsing: <https://github.com/joyent/node-ufds>
Who: Mark Cavage and others

Tickets/bugs: <https://github.com/joyent/node-ufds/issues>


# Overview

Node.js client library for SDC UFDS service.

# Repository

    lib/                 Source files.
    test/                Test suite (using node-tap)
    tools/               Dev support tools
    Makefile
    package.json         npm module info (holds the project version)
    npm-shrinkwrap.json  Frozen npm module versions to setup.
    README.md            This.
    CHANGES.md           Changelog

# Development

Before commiting/pushing run `make prepush` and, if possible, get a code
review. Refer to the test section below for reference on setup and how to run
the test suites.

# Testing

Short version:

    make test
