Solidus Comments
==============

Is completely based on Spree Comments and made to work with Solidus.

Spree Comments is an extension for Spree to allow commenting on different models via the
admin ui and currently supports Orders & Shipments.

Spree Comments also supports optional comment Types which can be defined per comment-able
object (i.e. Order, Shipment, etc) via the admin Configuration tab.

This is based on a fork / rename of jderrett/spree-order-comments and is now an officially
supported extension.

Notes:

* Comments are create-only.  You cannot edit or remove them from the Admin UI.

Installation
------------

After adding gem to Gemfile.

Run:

```shell
bundle install
bundle exec rails g spree_comments:install
```

Run the migrations if you did not during the installation generator:

    bundle exec rake db:migrate

Start your server: 

    rails s
