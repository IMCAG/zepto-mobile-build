# zepto-mobile-build
Custom [Zepto](https://github.com/madrobby/zepto) build replacing jQuery in some IMC mobile apps.

## Included modules
- zepto
- event
- ajax
- ie
- data
- detect
- selector
- touch
- gesture
- stack

Compiled using:
```console
$ SET MODULES=zepto event ajax ie data detect selector touch gesture stack
$ npm run-script dist
```

## Install
[Add SSH deploy key to your ssh-agent](https://jira.im-c.de/confluence/display/NM/Github+Deploy+Keys)
```console
$ ssh-agent ssh-add path/to/github_deploy_key_rsa
```

Install using Bower
```console
$ bower install --save ssh://github.com/IMCAG/zepto-mobile-build.git#*
```

## Comparison
Lib | Uncompressed | Compressed
:-- | -----------: | ---------:
jQuery 3 | 271 KB | 85 KB
jQuery 2 | 242 KB | 83 KB
Zepto | 62 KB | 28 KB
