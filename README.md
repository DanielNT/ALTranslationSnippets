# AL Translation Snippets

[![Visual Studio Marketplace Version](https://img.shields.io/vscode-marketplace/v/daniel-nt.al-translation-snippets.svg?style=flat-square&label=Download%20in%20VS%20Marketplace)](https://marketplace.visualstudio.com/items?itemName=daniel-nt.al-translation-snippets)

A collection of useful **configurable** snippets for multi-language localization of text strings in AL Language, using the `developer comments`.

![Example of developer comments](https://i.ibb.co/ZTbGhC2/example-Label.png)

![Example of use](https://github.com/DanielNT/AlTranslationSnippets/assets/12068767/268de838-9d28-4bf0-b5a8-f84b95fb36c8)

## Requirements
- Visual Studio Code v1.56.0 (April 2021) or higher.

| **Extension**| Link     | Mandatory |
|--------------|-----------|------------|
| **AL Language extension for Microsoft Dynamics 365 Business Central** | [![Visual Studio Marketplace Version](https://img.shields.io/vscode-marketplace/v/ms-dynamics-smb.al.svg?style=flat-square&label=Download)](https://marketplace.visualstudio.com/items?itemName=ms-dynamics-smb.al) |  **Yes**    | 
| **AL Translation Center** | [![Visual Studio Marketplace Version](https://img.shields.io/vscode-marketplace/v/daniel-nt.al-translation-center.svg?style=flat-square&label=Download)](https://marketplace.visualstudio.com/items?itemName=daniel-nt.al-translation-center) |  Recommended*    | 

*You MUST use a translation extension which use developer comments for generating translations. **AL Translation Snippets does not generate translations by itself.**

## Features
- More than one language can be inserted in the comment at the same time.
- The default languages that will be inserted with the snippet can be customized without the need of creation of user snippets. 
- The focus on language (usually useful in static snippets for allowing changing quickly the language from "ESP" to your language) could be disabled by setting.

## Snippets included
- `tcaptionWithTranslation`  
- `ttoolTipWithTranslation`  
- `tlabelWithTranslation`  
- `toptionCaptionWithTranslation`  
- `tprofileWithTranslation` (for Runtime +4.0)  
- `tprofileDescriptionWithTranslation`  
- `tactionWithTranslation`  
- `tcommentWithTranslation`  
- `taboutTitleWithTranslation`  
- `tadditionalSearchTermsWithTranslation`  
- `taboutTextWithTranslation`  

## Commands
* `Update Snippets With Current Settings`: updates the snippets without the need of restart VS Code.

## Extension Settings
This extension contributes the following settings:

* `Focus on language`: Determines if snippet will focus in language prefix, or only in the comment text. 
* `Comment Languages`: The list of prefix of languages to be generated. Use prefix with 3 characters.
* `English Text as First`: Determines if snippet will focus in english text as first, not in the comments.

Restart or execute 'Update Snippets With Current Settings' to apply changes.

## Issues
- You can report an issue at https://github.com/DanielNT/ALTranslationSnippets/issues.
