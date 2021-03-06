# Blub
Blub is a feature rich Chromium based web browser made using Electron JS and based on min.


# Repository Information 
"Nightly" is the main branch of this repository. All active development happens in Nightly, and new beta releases happen often. 
Because of this, nightly builds will be incomplete and have bugs. 

Please make sure all contributions are somewhat "working" when you create a pull request, and will not break other parts of the code when merged. 

As development continues, changes are pushed into beta and release branches. If a bug is found after release (in the release branch), bug fix changes will be made directly there. 

# Building
To build Blub from source code, run `npm install` and then run one of the following commands.

- `npm run buildWindows`
- `npm run buildMacIntel`
- `npm run buildMacArm`
- `npm run buildDebian`
- `npm run buildRaspi` (for Raspberry Pi, Raspberry Pi OS)
- `npm run buildLinuxArm64`
- `npm run buildRedhat`

Run `npm install` and `npm start` to test without building.

# Credits
Some parts of the source code in this project come from min (https://github.com/minbrowser/min), and credit goes to its developers and contributers.
This project uses Electron JS as a framework, which uses Chromium as a base. 
Changes are made to this project by contributers and developers.

Thanks to everyone who helps make this project!


# License [MIT]
Copyright (c) 2021 Blub Browser

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Blub-browser does not allow use of its trademarks in redistribution of this software. 
