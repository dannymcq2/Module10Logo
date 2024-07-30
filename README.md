# Module10Logo

## Description

My motivation to create this was to give a simple solution for a simple logo that someone needs quickly. I built this to help anyone in need of a logo or may need a template for ideas. This problem solves if someone may not be able to create a logo themselves or know anyone who can. I learned more about being able to work on generators to use.

## Table of Contents 
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Features](#features)
- [Tests](#tests)
- [package.json](#packagejson)

## Installation

No need to install. Runs on command line, after the logo then will open up on browser. Using Node index.js to run on command line.

## Usage

For more details, refer to this [video](https://drive.google.com/file/d/13kJ-kPJ3kYPiRp4hmW9zyjsHLMGSsDRs/view?usp=sharing).

## Credits

## Features

Creates a simple logo quickly from the command line. You will type up to 3 letters, choose a color for the text, a shape from circle, square or triangle then you will choose a color for shape. It will then create a svg file where you can open on browser to view + save.

## Tests

Command line

## package.json

Here is the `package.json` configuration for this project:

```json
{
  "name": "logo-generator",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "description": "",
  "dependencies": {
    "inquirer": "^10.0.1"
  }
}
