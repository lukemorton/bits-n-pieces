# Bits n Pieces

[![Gem Version](https://badge.fury.io/rb/bits-n-pieces.svg)](http://badge.fury.io/rb/bits-n-pieces)

This library was built to play with [pieces][pieces], a front end toolkit for
ruby.

This library is opinionated so you might prefer to roll your own.

## Installation

Just add the following lines to your Gemfile:

``` ruby
gem 'pieces'
gem 'bits-n-pieces'
gem 'sprockets', github: 'rails/sprockets' # using master until v4 released
```

## Batteries Included

 - [Sass][sass]
 - [Bourbon][bourbon]
 - [Neat][neat]
 - [Babel][babel]
 - [Uglifier][uglifier]
 - [Normalize][normalize]
 - and other bits I find useful

## Useful things

Here is a quick summary of other bits included.

``` scss
@import 'bits/media_queries';

html {
  font-size: 16px;

  @include from(tablet) {
    font-size: 20px;
  }
}
```

``` scss
@import 'bits/normalize';

// includes latest normalize.css
```

``` scss
@import 'bits/reset';

// applies zero margin, zero padding and box-sizing: border-box
// to all elements
```

``` scss
@import 'bits/columns';

// shortcut for including bourbon and neat for columns
```

[pieces]: https://github.com/drpheltright/pieces
[sass]: http://sass-lang.com/
[bourbon]: http://bourbon.io/
[neat]: http://neat.bourbon.io/
[babel]: https://github.com/babel/ruby-babel-transpiler
[uglifier]: https://github.com/lautis/uglifier
[normalize]: https://necolas.github.io/normalize.css/
