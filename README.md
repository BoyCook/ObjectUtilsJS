## Description

Object utility functions in JavaScript for node.js

## Usage

	var Object = require('objectutils');
	Object.isDefined({});
	Object.isUndefined({});
	Object.isNotEmpty([]);
	Object.isEmpty([]);

## Including in node.js app

You can include the module from GitHub directly by adding the following to your `package.json` and then doing `npm install`

    "dependencies": {
        "object-utils": "https://github.com/BoyCook/ObjectUtilsJS/tarball/master"
    }

## Tests

Displaying results in the terminal (common usage):

    make test

Running all the tests (calls test-ci and test-cov - best used by CI server):

    make test-all

Produce xUnit style XML report file:

    make test-ci

Running the tests with coverage and producing HTML Mocha coverage report file:

    make test-cov
