# jekyll-theme-booster

This is  Jekyll Theme based on <https://freehtml5.co/demos/booster/> Thanks freehtml2

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-booster"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-booster
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-theme-booster

# Usage

Look inside `example` folder for example site so you know what you need to
define in your project. At least you should update:

* `_config.yml` for site data
* pages (`index.md` and `contact.md`) and posts inside folders
  (`product_type_1`)
* `_data/nabar_links.yml` should define links in main navigation bar at top
* `_data/footer_links.yml` similar to navbar, but contains pages and posts (you
  can call it Products and News).
* index page can have carousel layout, for which you need to define text and
  client images

* you can use other components from `_includes` folder. Check their source how
  to use it.

Tips:

* when defining images always use leading `/`, for example
  `image: /assets/images/my image.png`. Spaces are allowed.
* when defining paths do not use leading `/` and use `.md` at the end. Spaces
  are not allowed.

~~~
carousel_paths:
  - product_type_1/index.md
~~~

## Contributing

Bug reports and pull requests are welcome on GitHub at <https://github.com/duleorlovic/jekyll-theme-booster>. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

There is example site inside `/example` folder. To test it run

~~~
rake example
# open browser
google-chrome http://127.0.0.1:4005
~~~

And

Only the files in `_layouts`, `_includes`, and `_sass` tracked with Git will be
released.

To build and install gem run

~~~
gem build jekyll-theme-booster.gemspec
gem install jekyll-theme-booster-0.1.0.gem
~~~

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
