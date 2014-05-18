# Guard::HamlCoffee

**(Technically not a pulished gem, just a forked copy. Original gem is receiving no support, planning to close this one as well.)**

Guard gem to generate Javascript code from [Haml Coffee](https://github.com/netzpirat/haml-coffee) templates. Inspired by [haml_coffee_assets](https://github.com/netzpirat/haml_coffee_assets).

## Installation

Add this line to your application's Gemfile:

    gem 'guard-hamlcoffee'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install guard-hamlcoffee

## Usage

As a prerequisite, you must have [Guard](https://github.com/guard/guard) installed and initialized already.

Add the hamlcoffee instructions to the `Guardfile`:
    
    $ bundle exec guard init hamlcoffee

Restart guard if it's running and that's it.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
