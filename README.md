# ockham

> Entia non sunt multiplicanda praeter necessitatem.
>
> -- William of Ockham

Ockham is a content-first minimalist Jekyll blog theme.

![screenshot](screenshot.png)

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "ockham"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: ockham
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install ockham

If your website is hosted on GitHub Pages, you can install this theme via [`jekyll-remote-theme`](https://github.com/benbalter/jekyll-remote-theme).

Add the following to your `Gemfile`:

```ruby
gem "jekyll-remote-theme"
```

And add this line to your Jekyll site's `_config.yml`:

```yml
plugins:
  - jekyll-remote-theme
```

Add the following to your site's `_config.yml`:

```yml
remote_theme: zivong/ockham
```

## Usage

For more information about the usage of Ockham, please read the [tutorial](https://zivong.blog/ockham/tutorial/2021/09/12/tutorial.html).

## Contributing

Bug reports and pull requests are welcome on GitHub at [https://github.com/zivong/ockham](https://github.com/zivong/ockham). This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `ockham.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
