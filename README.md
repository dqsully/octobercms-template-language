# octobercms-template-language package for Visual Studio Code

Provides language support for [October CMS's](http://octobercms.com) template file syntax.
**NOTE:** Because of the limitations of the VS Code grammar system, `{##}` **must** be at the beginning of your Twig/HTML script.

## Recent Changes
* Removed dependence on `;;` to begin the INI section
* Removed custom implementations of PHP and INI
* Fixed comment commands and bracket matching
* Fixed most auto-closing brackets and surrounding bracket pairs (for some reason, these bracket pairs apply to a whole file and do not work with embedded languages, so I can't tell VS Code to type an extra closing `#` in the Twig section without it also happening in the PHP and INI sections as well)

## Features
* No dependencies
* Full support for all of the OctoberCMS template language
* `;;` at the beginning of a file tells VS Code that your `.htm` file is for OctoberCMS

## Issues
* Commenting does not work properly (I tried, but please help)
* The custom bracket autocompletion for Twig that I put in the Atom package does not work for VS Code (it may with a lot of tweaking)

![Screenshot](https://github.com/dqsully/language-octobercms/blob/master/screenshot.png?raw=true)
