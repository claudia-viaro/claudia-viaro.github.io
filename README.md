# Bay

[![Version](https://img.shields.io/gem/v/bay_jekyll_theme)](https://rubygems.org/gems/bay_jekyll_theme)
[![Downloads](https://img.shields.io/gem/dt/bay_jekyll_theme)](https://rubygems.org/gems/bay_jekyll_theme)

Bay is a simple theme for Jekyll. [[view live]](https://eliottvincent.github.io/bay)

Inspired by [dangrover.com](http://dangrover.com/). Current theme used at [eliottvincent.com](http://eliottvincent.com/).

### Installation


The easiest solution is to [fork this repo](https://github.com/eliottvincent/bay/fork).
If you want to start from a clean website, follow the steps bellow:

Create a new Jekyll website:
```
jekyll new mysite
```

Open `Gemfile` and replace the line:
```
gem "minima"
```
with:
```
gem "bay_jekyll_theme"
```

Open `_config.yml` and replace the line:
```
theme: minima
```
with:
```
theme: bay_jekyll_theme
```
or, for GitHub Pages:
```
remote_theme: eliottvincent/bay
```

Finally, install the dependencies:
```
bundle install
```

and build the website!
```
jekyll serve
```

### Development

#### Run development instance (with hot-reload)
```sh
bundle exec jekyll serve
```

#### Build and publish the gem
```sh
gem build bay_jekyll_theme.gemspec
```

```sh
gem push bay_jekyll_theme-1.x.x.gem
```
