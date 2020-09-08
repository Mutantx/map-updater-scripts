# wc3-ts-template
 An easy to use template to get you started coding in TypeScript for Warcraft III maps.

Setup guide and information on the [wiki](https://github.com/triggerhappy187/wc3-ts-template/wiki).

## Features
* TypeScript API and wrappers for most handles (see [w3ts](https://github.com/cipherxof/w3ts))
* Work on your map in the World Editor while also coding in TypeScript.
* Evaluate node scripts at compile time and support for npm dependencies (see [war3-transformer](https://github.com/cipherxof/war3-transformer))
* Build w3x archives from your project's map folder.
* Automatically generate definitions for global variables generated by the editor such as regions, cameras, or preplaced units.
* Works on Windows and Mac OS out of the box and with a couple modifications it works on Linux as well.

## W3C Commands
* Run ./updateMaps.sh to mass update all maps within the ./maps/w3c_maps directory to support new changes