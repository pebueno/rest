# generator-rest [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url] [![Coverage percentage][coveralls-image]][coveralls-url]
> RESTful API generator using NodeJS, Express and Mongoose

## Features

 - **Highly customizable** - You can choose what to install
 - **Really RESTful** - It follows the best practices
 - **ES6!** - Using [babel](https://babeljs.io/)
 - **User registration API** - Using [passport](http://passportjs.org/) (optional)
 - **Social login API** - Currently only Facebook (optional)
 - **Password reset API** - Sending emails with [SendGrid API](https://sendgrid.com/docs/API_Reference/index.html) (optional)
 - **Listing query strings** - `q`, `page`, `limit`, `fields` etc. already provided by [querymen](https://github.com/diegohaz/ququerymen)
 - **Query string validator** - Using [querymen](https://github.com/diegohaz/ququerymen)
 - **Request body validator** - Using [bodymen](https://github.com/diegohaz/qubodymen)
 - **Standard error responses** - Using [querymen](https://github.com/diegohaz/ququerymen) and [bodymen](https://github.com/diegohaz/qubodymen) error handlers
 - **Unit and integration tests** - Using [AVA](https://github.com/avajs/ava)
 - **Continuous integration support** - Using [Travis CI](https://travis-ci.org/)
 - **API docs generator** - Using [apidoc](http://apidocjs.com/)
 - **Love ♥** - Using [me](https://github.com/diegohaz)

## Installation

First, install [Yeoman](http://yeoman.io) and generator-rest using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
npm install -g yo
npm install -g generator-rest
```

Then generate your new project:

```bash
yo rest
```

## Directory structure

You can customize the `src` and `api` directories.

```
- src/
| - api/
| | - some-endpoint/
| | | - index.js
| | | - index.test.js
| | | - some-endpoint.controller.js
| | | - some-endpoint.model.js
| | | - some-endpoint.model.test.js
| | - another-endpoint/
| - config/
| | - index.js
| | - express.js
| | - mongoose.js
| - services/
| | - facebook/
| | - passport/
| | - sendgrid/
| | - your-service/
| - app.js
| - index.js
| - routes.js
```
## License

MIT © [Diego Haz](https://github.com/diegohaz)


[npm-image]: https://badge.fury.io/js/generator-rest.svg
[npm-url]: https://npmjs.org/package/generator-rest
[travis-image]: https://travis-ci.org/diegohaz/generator-rest.svg?branch=master
[travis-url]: https://travis-ci.org/diegohaz/generator-rest
[daviddm-image]: https://david-dm.org/diegohaz/generator-rest.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/diegohaz/generator-rest
[coveralls-image]: https://coveralls.io/repos/diegohaz/generator-rest/badge.svg
[coveralls-url]: https://coveralls.io/r/diegohaz/generator-rest