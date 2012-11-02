**This gem has been moved to the [mince](https://github.com/coffeencoke/mince) core gem, and this repo is deprecated**

# Version 2.0 Release Notice

Version 2.0 is currently in preview, available on <http://rubygems.org> and at [@coffeencoke's github repo](https://github.com/coffeencoke)

This repo will be moved to @coffeencoke once version 2.0 is officially released.

# MinceModel

Common model behavior for objects backed by Mince


## Installation

Add this line to your application's Gemfile:

    gem 'mince_model'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install mince_model


## Usage

1. Write your models as plain old Ruby objects.
2. In your model, `include MinceModel`.
3. In your model, define the data model with `data_model DataModelClass`.
4. In your model, define fields with `field :field_name, assignable: true`.


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
