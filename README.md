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

Look inside `example` folder for examples of what you need to define

* `_config.yml` for site data
* `_data/nabar_links.yml` is used to define links in main navigation bar at top
* `_data/footer_links.yml`

You can use components from `_includes` folder. Check their source how to use
it.

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

There is example site inside `/example` folder. To rtest it run

~~~
rake example
~~~

Only the files in `_layouts`, `_includes`, and `_sass` tracked with Git will be released.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
