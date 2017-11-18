# cSpell CI Example

## **WORK IN PROGRESS**

The purpose of this repository is to have an example on how to setup cSpell in
a CI node environment.

This repository is setup to support both Travis-CI and Appveyor.

The following steps were used to get CI working to check both English and German text.

1. Install cSpell: `npm install -SD cspell`
1. Install German: `npm install -SD cspell-dict-de-de`
1. Edit `cspell.json` to reference the German dictionary.
