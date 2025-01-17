![Code of Conduct Icon](/icons/vscode-add-coc.png)

# VS Code Add Code of Conduct

## Code of Conduct
A Code of Conduct is a set of rules for a group of people to follow when they interact with each other on behalf of a project, community, or event. Adding a Code of Conduct to your repo is a great way to show inclusivity for all contributors and provide clear guidelines for how to behave and how the rules will be enforced.

This extension will add a Code of Conduct to your repo. You can choose from a [selection of templates](/src/codesOfConduct/) and replace the placeholders with your own text.

## How to Add a Code of Conduct to Your Repo
- Activate the Command Pallet
- Select the `Add Code of Conduct` Command
- Choose your Code of Conduct Template
- Replace Placeholders in the Template

![Add Code of Conduct](https://kjaymiller.azureedge.net/media/add_covenant-2022-8-2.gif)

## Settings

### Setting Default Placeholders
You can set default values for a given placeholder by adding the value into your vscode settings. You must edit the settings file directly.

```json
{
    "codeOfConduct.defaultPlaceholders": [
  {
    "placeholder": "{{INSERT_CONTACT_METHOD}}",
    "replacement": "kjaymiller@gmail.com"
  }
  ]
}
```

`codeOfConduct.defaultPlaceholders` is an array of objects with the properties `placeholder` and `replacement`. The `placeholder` property is the placeholder AS IT APPEARS IN THE TEMPLATE (BRACES INCLUDED).  `replacement` is the value that will be offered as a default in the template.

## Templates
A list of the templates can be found in [/src/codesofConduct](/src/codesOfConduct/) or you can view the list in [/src/manifest.ts](src/manifest.ts). The templates are as-written with the exception of organizational specifics being generalized and being replaced and Attributtion being given to the original source.Placeholders being wrapped with double braces to conform to the extension's formatting.


## Inspiration:
* [original project](https://github.com/cg-cnu/vscode-add-conduct) by [@cg_cnu](https://github.com/cg-cnu) 

