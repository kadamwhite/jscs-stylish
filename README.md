# A Stylish JSCS Reporter

This is a reporter for the [JSCS]() JavaScript Code  [jshint-stylish](https://github.com/sindresorhus/jshint-stylish)

![JSCS-Stylish reporter output](jscs-stylish-screenshot.png)

## Install

```bash
npm install --save-dev jshint-stylish
```

## Usage

Example usage within the configuration block for [grunt-jscs-checker](https://www.npmjs.org/package/grunt-jscs-checker):
```javascript
jscs: {
    options: {
        config: '.jscsrc',
        reporter: require( 'jscs-stylish' )
    },
    all: {
        src: [ js/**/*.js ]
    }
}
```

## License

&copy; K.Adam White 2014, released under the [MIT License](http://opensource.org/licenses/MIT)
