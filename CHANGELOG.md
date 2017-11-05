# Change Log
All notable changes to the "octobercms-template-language" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## 0.1.0
- Initial release

## 0.2.0
- Removed dependence on `;;` to begin the INI section
- Removed custom implementations of PHP and INI
- Fixed comment commands and bracket matching
- Fixed most auto-closing brackets and surrounding bracket pairs (for some reason, these bracket pairs apply to a whole file and do not work with embedded languages, so I can't tell VS Code to type an extra closing `#` in the Twig section without it also happening in the PHP and INI sections as well)
