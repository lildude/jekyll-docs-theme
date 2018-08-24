# Jekyll Docs Theme

> This is a [Jekyll theme](https://github.com/allejo/jekyll-docs-theme) based on [mistic100's modification](https://github.com/mistic100/jekyll-bootstrap-doc) of the official Bootstrap documentation from a few years back.

Jekyll Docs Theme is provided as a theme for writing documentation for your projects instead of having a single large README file or several markdown files stored in a not so user-friendly manner.

This theme is still in development but is kept fairly stable; just note, there are a lot things yet to come.

![Theme Screenshot](https://raw.githubusercontent.com/allejo/jekyll-docs-theme/master/screenshot.png)

## @lildude's Modifications

I've started to tweak and enhance this theme for my own purposes and am still deciding how I'll upstream some of all of these changes. For the moment, these are the changes I've made in this fork:

- Detailed how you can use this theme with GitHub Pages' new [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/) functionality.
- Default to using [GitHub repository metadata](https://help.github.com/articles/repository-metadata-on-github-pages/) where it makes sense to. These can be overwritten by the original configuration options which are commented out in this fork.
- Added the ability to
    - configure a "brand color" - this is the primary color of the brand and used for the sidebar and navbar links.
    - configure a favicon
    - hide the top navigation bar
- Added a new syntax theme to override the default.

## Installation

To use on GitHub Pages sites, add this to your `_config.yml`:

```yaml
remote_theme: lildude/jekyll-docs-theme
```

-or-

Fork this project

-or-

Add this line to your Jekyll site's Gemfile:

```ruby
gem "jekyll-docs-theme"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-docs-theme
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-docs-theme

## Development

To set up your environment to develop this theme, run `bundle install`.

To develop on this theme, run `bundle exec jekyll serve --config _config.yml,_config-dev.yml` and open your browser at `http://localhost:4000`.

The `_config-dev.yml` file loads the [jekyll-github-metadata](https://github.com/jekyll/github-metadata) plugin so you can develop using the `site.github` parameters available on GitHub Pages.

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
