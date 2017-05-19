# octobercms-template-language package for Visual Studio Code

Provides language support for [October CMS's](http://octobercms.com) template file syntax.
**NOTE:** Because of the limitations of the VS Code grammar system, ``;;`` **must** be at the beginning of your INI script, and ``{##}`` **must** be at the beginning of your Twig/HTML script.

## Features
* No dependencies
* Full support for all of the OctoberCMS template language
* `;;` at the beginning of a file tells VS Code that your `.htm` file is for OctoberCMS
* Compatibility with Emmet

## Issues
* Commenting does not work properly (I tried, but please help, VS Code is confusing)
* The custom bracket autocompletion for Twig that I put in the Atom package does not work for VS Code

![Screenshot](https://github.com/dqsully/language-octobercms/blob/master/screenshot.png?raw=true)
