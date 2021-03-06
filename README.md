# remove-node-modules

Helps Windows developers remove node_modules folder.

If you're unable to remove the node modules folder on Windows 7 from explorer and receive an error similar to this:

> The source file name(s) are larger than is supported by the file system. > Try moving to a location which has a shorter path name, or try renaming > to shorter name(s) before attempting this operation

### Current Version: 1.7.6

## Getting Started With Yarn

`$ yarn global add remove-node-modules`

## Getting Started With NPM

`$ npm install -g remove-node-modules`

## Default Usage

1. Navigate to where your node_modules folder resides
2. `$ remove-node-modules`

## Alternative Usage

`$ remove-node-modules /path/to/node_modules`

## Contributing

Feel free to contribute!

## Changelog

- v1.7.7 (08/31/2019) - improves deletion of node modules folder
- v1.7.2 (08/31/2019) - patches security vulnerability
- v1.7.2 (11/5/2016) - updates documentation
- v1.7.1 (10/26/2016) - fixes bug in index.js
- v1.7.0 (10/13/2016) - updated friendly message
- v1.6.2 (10/12/2016) - fixes alternative usage bug
- v1.6.1 (10/11/2016) - available on yarn
- v1.0.0 (10/7/2016) - published to npmjs
- v0.1.3 (12/26/2015) - added return in front of cleanup callback
- v0.1.2 (12/17/2015) - added .gitignore
