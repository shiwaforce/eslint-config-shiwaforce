# eslint-config-shiwaforce


## Installation
```
npm i eslint-config-shiwaforce --save
```

## Usage
If you've installed eslint-config-shiwaforce locally within your project, just set your eslint config(```.eslintrc``) to:
```json
{
  "extends": "eslint-config-shiwaforce"
}
```

## Extending/Overriding the config
Just add ```"rules""``` key to your config, then add your additional/override rules.
For example if you would like to change ```"indent"``` rule from default to your own:
```json
{
  "extends": "eslint-config-shiwaforce",
  "rules": {
    "indent": [2, "space"],
  }
}
```
## Additional information about rules
[Eslint](http://eslint.org)