# dms-snippets README

This is the README for the extension "dms-snippets". Commonly used snippets for use when creating experiences.

## Features

![snippet gif](https://media.giphy.com/media/LPIZ8rCf1S2CC2W1l6/giphy.gif)

### List of Available Commands

#### Triggers
- !dms-triggers - Template for triggers.js with utils package
- !dms-slick-require - Require function for Slick Carousel

#### Variation
- !dms-variation - Template for variation.js with utils package

#### Fields
- !dms-fields - Template for fields.json
- !dms-fields-group
- !dms-field-string
- !dms-field-number
- !dms-field-string-array
- !dms-field-boolean
- !dms-field-url
- !dms-field-image

#### CSS
- !dms-css - Template for variation.less
- !dms-slick-css - Formatted CSS file for Slick Carousel

## How to Install

Copy the dms-snippets folder and paste into the following directory

```
users/<name>/.vscode/extensions/
```

## How to Extend

### How to Add Snippets

- Copy the code snippet you wish to add and paste into the snippet generator [here](https://snippet-generator.app/?description=&tabtrigger=&snippet=&mode=vscode)
- Find the relevant json file and paste the snippet
- '$' in jQuery and template literal expressions have to be escaped with `\\` as VSCode snippet literals also use '$' e.g. $banner.text(\`${\_ticket}-banner\`) becomes $banner.text(\`${\_ticket}-banner\`)

### How to Add Files

- To add additional files create a json file within the `snippets` folder. Add the following to the package.json and specify the language and path to the json file.
```
{
  "language": "javascript",
  "path": "./snippets/triggers.json"
}
```


## Known Issues

- Todos listed below

## Release Notes

### 0.0.2

Initial release of dms-snippets

-----------------------------------------------------------------------------------------------------------

## Todos

- Add all template snippets when utils versions are updated
