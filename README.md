# aligner-stylus

[Aligner](https://github.com/adrianlee44/atom-aligner) add-on to support Stylus.

## Supported operators
` ` (whitespace)
```stylus
body
  display   block
  position  absolute
  font-size 12px
```
`:` assignment
```stylus
.some-div
  color:            blue
  background-color: red
```
`=` variable assignment
```stylus
body
  $varFoo   = blue
  $varOther = red
  $varLast  = $externalVar
```
`//` comments (if `Align Comments` options is enabled in the [Aligner](https://github.com/adrianlee44/atom-aligner) package)
```stylus
.foo
  $var = 'hello';   // line 1
  $foo = 'wo';      // line 2
  $bar = 'rld';     // line 3
```

## Installation
Aligner must be installed along with this package. For more information, please check out [Aligner](https://github.com/adrianlee44/atom-aligner)

## Changelog
- 2017-10-11   v1.3.0   Add support for comments; README;
- 2017-10-11   v1.2.0   Add support for `=`, markup in `.styl`, `.vue` files
- 2017-05-15   v1.1.0   Add support for `:`
- 2017-05-13   v1.0.1   Update documentation
- 2016-04-16   v1.0.0   Initial release
