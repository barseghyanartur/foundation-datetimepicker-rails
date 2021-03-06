# foundation-datetimepicker-rails

This gem packages the foundation-datetimepicker (JavaScripts & stylesheets) for Rails 3.1+ asset pipeline. It adds ability to use [foundation-datetimepicker plugin](https://github.com/najlepsiwebdesigner/foundation-datepicker) within your Rails app without puting files inside `vendor` directory.

## Installation

Add this line to your application's Gemfile:

    gem 'foundation-datetimepicker-rails'

Add the following directive to your Javascript manifest file (`application.js`):

    //= require foundation-datetimepicker

Add the following line to your stylesheet file (`foundation_and_overrides.scss`):

```scss
@import 'foundation';
@import 'foundation-datetimepicker';
```
## Update

Support for Foundation5 and Foundation-Icons-3 has been added.

##Quick instructions

Call the datetimepicker via javascript:

    $('.datetimepicker').fdatetimepicker()


## Usage

See the excellent demo provided by plugin's author - [here](http://foundation-datepicker.peterbeno.com/example.html).

## Contributing to the original plugin

If you've encountered some plugin-related issues, please contribute directly to https://github.com/najlepsiwebdesigner/foundation-datepicker/issues.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
