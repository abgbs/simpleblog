# Simpleblog

Simpleblog is a Jekyll theme created mainly for learning purposing. The theme is very simple and minimal, you can find the guts of this project under the `_sass` directory.

## Installation

First, build the theme as a gem file run `gem build simpleblog.gemspec`.

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "simpleblog"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: simpleblog
```

And then execute:

    $ bundle

OR
To install it to your Github pages copy all the contents to your page.

## Usage

There are there layouts:
- default - this is the main layout that other layouts depends on.
- post - defines how a post looks like.
- page - any other page.

In the includes directory there is two files:
- head.html - where the stylesheets, page title, social media info, and Google Analytics are.
- sidenav.html - this is the side navigation bar.

The main theme located under `_sass`.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/aymanbagabas/simpleblog.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `simpleblog.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

