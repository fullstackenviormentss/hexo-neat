# status
[![npm version](https://badge.fury.io/js/hexo-neat.svg)](https://badge.fury.io/js/hexo-neat)

# Hexo-neat

I want a profect page to show for my blog, so I made this.

## Show
[青枫浦](http://post.zz173.com)

## Installation
``` bash
$ npm install hexo-neat --save
```


## Options
To Enable Auto neat , you must config like this:
``` yaml
neat_enable: true
```

``` yaml
neat_html:
  enable: true
  exclude:
```
- **enable** - Enable the plugin. Defaults to `true`.
- **exclude**: Exclude files
**Note:** there are so many params please see '[HTMLMinifier](https://github.com/kangax/html-minifier)'
----------

``` yaml
neat_css:
  enable: true
  exclude:
    - '*.min.css'
```
- **enable** - Enable the plugin. Defaults to `true`.
- **exclude**: Exclude files

----------

``` yaml
neat_js:
  enable: true
  mangle: true
  output:
  compress:
  exclude:
    - '*.min.js'
```
- **enable** - Enable the plugin. Defaults to `true`.
- **mangle**: Mangle file names
- **output**: Output options
- **compress**: Compress options
- **exclude**: Exclude files


## Thanks
Say Very Thanks for this gays:
- neat html by [HTMLMinifier](https://github.com/kangax/html-minifier)
- neat css  by [clean-css](https://github.com/jakubpawlowicz/clean-css)
- neat js   by  [UglifyJS](http://lisperator.net/uglifyjs/)
