# ember-toastr

A wrapper for [toastr.js] by injecting it into routes, components, and controllers.

## Usage

```sh
ember install ember-toastr
```

The toastr object is injected as `notify`, so it can be used as

```js
this.notify.info('Hello there!');
```

See the toastr.js [demo] for other possible uses.

## Installation

* `git clone` this repository
* `npm install`
* `bower install`

## Running

* `ember server`
* Visit your app at http://localhost:4200.

## Running Tests

* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [http://www.ember-cli.com/](http://www.ember-cli.com/).

[toastr.js]: https://github.com/CodeSeven/toastr
[demo]: http://codeseven.github.io/toastr/demo.html