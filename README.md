# npmdoc-speaker

#### api documentation for  [speaker (v0.3.0)](https://github.com/TooTallNate/node-speaker)  [![npm package](https://img.shields.io/npm/v/npmdoc-speaker.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-speaker) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-speaker.svg)](https://travis-ci.org/npmdoc/node-npmdoc-speaker)

#### Output PCM audio data to the speakers

[![NPM](https://nodei.co/npm/speaker.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/speaker)

- [https://npmdoc.github.io/node-npmdoc-speaker/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-speaker/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-speaker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-speaker/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-speaker/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-speaker/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "speaker",
    "description": "Output PCM audio data to the speakers",
    "keywords": [
        "pcm",
        "audio",
        "sound",
        "music",
        "output",
        "speaker",
        "headphone",
        "alsa",
        "coreaudio",
        "openal",
        "sdl",
        "portaudio",
        "jack",
        "oss",
        "pulse",
        "mpg123"
    ],
    "license": "MIT",
    "version": "0.3.0",
    "author": "Nathan Rajlich <nathan@tootallnate.net> (http://tootallnate.net)",
    "repository": {
        "type": "git",
        "url": "git://github.com/TooTallNate/node-speaker.git"
    },
    "bugs": {
        "url": "https://github.com/TooTallNate/node-speaker/issues"
    },
    "homepage": "https://github.com/TooTallNate/node-speaker",
    "main": "./index.js",
    "scripts": {
        "test": "node-gyp rebuild --mpg123-backend=dummy && mocha --reporter spec"
    },
    "dependencies": {
        "bindings": "^1.2.1",
        "debug": "^2.2.0",
        "nan": "^2.2.0",
        "readable-stream": "^2.0.5"
    },
    "devDependencies": {
        "mocha": "^2.1.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
