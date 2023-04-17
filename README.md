# eslint-plugin-smwd

A set of custom eslint rules created by Sterling May

## Installation

You'll first need to install [ESLint](https://eslint.org/):

```sh
npm i eslint --save-dev
```

Next, install `eslint-plugin-smwd`:

```sh
npm install eslint-plugin-smwd --save-dev
```

## Usage

Add `smwd` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "smwd"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "smwd/rule-name": 2
    }
}
```

## Rules

<!-- begin auto-generated rules list -->
TODO: Run eslint-doc-generator to generate the rules list.
<!-- end auto-generated rules list -->


