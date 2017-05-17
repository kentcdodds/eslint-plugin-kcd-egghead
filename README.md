# eslint-plugin-kcd-egghead

Just a demo of an eslint plugin. Don't use this.

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-kcd-egghead`:

```
$ npm install eslint-plugin-kcd-egghead --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-kcd-egghead` globally.

## Usage

Add `kcd-egghead` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "kcd-egghead"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "kcd-egghead/rule-name": 2
    }
}
```

## Supported Rules

* no-console: disable the use of `console`
