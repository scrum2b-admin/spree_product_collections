SUMMARY
====================


**Spree Product Category** is an extension of SpreeCommerce (www.spreecommerce.com), support to create collections and categories of products.
The extension is developed by ScrumTobe Team.

***Contacts:***
- Email: *scrum2b@ithanoi.com*
- Demo: *spree2-package.herokuapp.com*
- Website: *www.scrumtobe.com*
- Facebook: *www.facebook.com/ScrumToBe*


Installation
------------

The extension support Spree Core 2.0 or later versions.
Add spree_product_category to your Gemfile:

```ruby
gem 'spree_product_category'
```

Bundle your dependencies and run the installation generator:

```shell
bundle
bundle exec rails g spree_product_category:install
```

Testing
-------

Be sure to bundle your dependencies and then create a dummy test app for the specs to run against.

```shell
bundle
bundle exec rake test_app
bundle exec rspec spec
```

When testing your applications integration with this extension you may use it's factories.
Simply add this require statement to your spec_helper:

```ruby
require 'spree_product_category/factories'
```

Copyright (c) 2013 [name of extension creator], released under the New BSD License
