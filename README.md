# FancyLogger

Standard Ruby logger, except fancier.

## Installation

Add this line to your application's Gemfile:

    gem 'fancy_logger'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install fancy_logger

## Usage

It's the same logger you use every day:

    l = FancyLogger.new(STDOUT)
    l.level = 0
    l.debug 'debugging is easy'
    l.info 'informing as well'
    l.warn 'OH WAIT! Something suspicious'
    l.error 'ACHTUNG! ZIE BIG ERROR'

except it colores warning levels, and prints out th file, line, and function
from which it was called:

![screenshot](https://raw.github.com/alisnic/fancy_logger/master/screenshot.png "screnshot")

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
