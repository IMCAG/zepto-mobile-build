# zepto-mobile-build
Custom [Zepto](https://github.com/madrobby/zepto) build replacing jQuery in some IMC mobile apps.

Included modules: 
- zepto
- event
- ie
- data
- selector
- touch
- gesture
- stack

## Install
Adding SSH deploy key to the ssh-agent
```console
$ ssh-agent ssh-add path/to/id_rsa
```

Install using Bower OR npm
```console
$ bower install --save IMCAG/zepto-mobile-build
$ npm install --save IMCAG/zepto-mobile-build
```

## Comparison
Lib | Uncompressed | Compressed
:-- | -----------: | ---------:
jQuery 3 | 271 KB | 85 KB
jQuery 2 | 242 KB | 83 KB
Zepto | 56 KB | 26 KB
