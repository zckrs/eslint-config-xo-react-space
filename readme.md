# eslint-config-xo-react-space [![Build Status](https://travis-ci.org/zckrs/eslint-config-xo-react-space.svg?branch=master)](https://travis-ci.org/zckrs/eslint-config-xo-react-space)

> ESLint [shareable config](http://eslint.org/docs/developer-guide/shareable-configs.html) for React to be used with [eslint-config-xo-space](https://github.com/sindresorhus/eslint-config-xo-space)

This is for advanced users. You probably want to use [XO](https://github.com/sindresorhus/xo) directly.


## Install

```
$ npm install --save-dev eslint-config-xo-space eslint-config-xo-react-space eslint-plugin-react
```


## Usage

Add some ESLint config to your `package.json`:

```json
{
	"name": "my-awesome-project",
	"eslintConfig": {
		"extends": ["xo", "xo-react-space"]
	}
}
```

Or to `.eslintrc`:

```json
{
	"extends": ["xo", "xo-react-space"]
}
```

You can also mix it with a sub-config:

```json
{
	"extends": ["xo/esnext", "xo-react-space"]
}
```


## Tip

### Use with XO

```
$ npm install --save-dev eslint-config-xo-react-space eslint-plugin-react
```

```json
{
	"name": "my-awesome-project",
	"xo": {
		"extends": "xo-react-space"
	}
}
```


## Related

- [eslint-config-xo](https://github.com/sindresorhus/eslint-config-xo) - ESLint shareable config for XO
- [eslint-config-xo-space](https://github.com/sindresorhus/eslint-config-xo-space) - ESLint shareable config for XO with 2-space indent
- [eslint-config-xo-react](https://github.com/sindresorhus/eslint-config-xo-react) - ESLint shareable config for React to be used with eslint-config-xo


## License

MIT © [Mehdy Dara](http://eleven-labs.com)
