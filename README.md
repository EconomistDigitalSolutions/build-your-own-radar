[![Build Status](https://travis-ci.org/thoughtworks/build-your-own-radar.svg?branch=master)](https://travis-ci.org/thoughtworks/build-your-own-radar)
[![Stars](https://badgen.net/github/stars/thoughtworks/build-your-own-radar)](https://github.com/thoughtworks/build-your-own-radar)
[![dependencies Status](https://david-dm.org/thoughtworks/build-your-own-radar/status.svg)](https://david-dm.org/thoughtworks/build-your-own-radar)
[![devDependencies Status](https://david-dm.org/thoughtworks/build-your-own-radar/dev-status.svg)](https://david-dm.org/thoughtworks/build-your-own-radar?type=dev)
[![peerDependencies Status](https://david-dm.org/thoughtworks/build-your-own-radar/peer-status.svg)](https://david-dm.org/thoughtworks/build-your-own-radar?type=peer)
[![Docker Hub Pulls](https://img.shields.io/docker/pulls/wwwthoughtworks/build-your-own-radar.svg)](https://hub.docker.com/r/wwwthoughtworks/build-your-own-radar)
[![GitHub contributors](https://badgen.net/github/contributors/thoughtworks/build-your-own-radar?color=cyan)](https://github.com/thoughtworks/build-your-own-radar/graphs/contributors)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)
[![AGPL License](https://badgen.net/github/license/thoughtworks/build-your-own-radar)](https://github.com/thoughtworks/build-your-own-radar)

# Golden Path | The Economist
A library that generates an interactive radar, inspired by [thoughtworks.com/radar](http://thoughtworks.com/radar).

## How To Use

*With npm*
1. Clone the project and go to the main folder 
2. Run `npm install` to install required dependencies
3. Run `npm run dev` 
4. Open `localhost:8080` in your browser to access the application.

## Setting up your data

You can add/edit data in `/src/data.js`.  
Your addition must be entered as an object. See example below.


`{name: "sweet potatoes", ring: "adopt", quadrant: "tools", isNew: "FALSE", description: "Sweet potato chips >>>>> Potato chips."},`

>**IMPORTANT: All your object values must be strings.**

Except for `name` and `description`, all other key values must show one of the options listed below for the sake of consistency.   

| name          | ring    | quadrant               | isNew   | description                                             |
|---------------|---------|------------------------|---------|---------------------------------------------------------|
| _Foo bar_       | adopt   | tools                  | "TRUE"  | _Lorem ipsum dolor amet scenester ethical meditation..._          |
| _Bar foo_       | trial   | techniques             | "FALSE" | _Vinyl quinoa waistcoat yr art party humblebrag post-ironic sartorial disrupt..._       |
| _Oar fob_       | assess  | platforms              | "TRUE"  | _Chicharrones pitchfork polaroid four loko man braid aesthetic butcher ..._   |
| _Boar of_       | hold    | languages & frameworks | "FALSE" | _Franzen small batch austin try-hard..._ |



