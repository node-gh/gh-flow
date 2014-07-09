# GH Flow [![Build Status](https://secure.travis-ci.org/node-gh/gh-flow.svg?branch=master)](https://travis-ci.org/node-gh/gh-flow) [![NPM version](https://badge.fury.io/js/gh-flow.svg)](http://badge.fury.io/js/gh-flow) [![Dependency Status](https://david-dm.org/node-gh/gh-flow.svg?theme=badge.io)](https://david-dm.org/node-gh/gh-flow)

![Dodgetocat](https://cloud.githubusercontent.com/assets/398893/3528234/42725954-078d-11e4-8835-6156da9bc4a1.png)

NodeGH plugin for integrating [GitFlow](https://github.com/nvie/gitflow), a successful Git branching model.

> Maintained by [Elad Elrom](https://github.com/eladelrom).

## Install

```
[sudo] npm install -g gh-boilerplate
```

## Usage

```
gh boilerplate
```

> **Alias:** `gh bo`

Option             | Usage        | Type
---                | ---          | ---
`-f`, `--foo`      | **Required** | `String`

#### Examples

* **Shortcut** for showing hello world message.

	```
gh bo
	```

* Show hello world message.

	```
gh bo --foo
	```

## Testing

Check [Travis](https://travis-ci.org/node-gh/gh-boilerplate) for continous integration results.

* Run [JSHint](http://www.jshint.com/), a tool to detect errors and potential problems.

    ```
npm run-script lint
    ```

* Run [Mocha](http://visionmedia.github.io/mocha/), a unit test framework.

    ```
npm run-script test
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 September 12, 2013
	* Start plugin using [gh-boilerplate](https://github.com/node-gh/gh-boilerplate)

## License

[BSD License](https://github.com/node-gh/gh/blob/master/LICENSE.md)
