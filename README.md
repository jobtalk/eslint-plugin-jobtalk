# eslint-plugin-jobtalk

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-jobtalk`:

```
$ npm install eslint-plugin-jobtalk --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-jobtalk` globally.

## Usage

Add `eslint-plugin-jobtalk` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "jobtalk"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "eslint-plugin-jobtalk/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





