# Personal Website

* Taken and adjusted Manuel's theme: https://github.com/mpeuster/mpeuster.github.io
* Based on this: https://github.com/sharu725/online-cv
* Original Theme: https://themes.3rdwavemedia.com/

## Dev

### Install

- Install Ruby (tested with Ruby 4.0, e.g. `brew install ruby`) and make sure its `bin` directory is on your `PATH`
- Install Bundler matching the version in `Gemfile.lock`:
  - `gem install bundler -v 2.7.2`
- Install gems: `bundle install`

### Serve

```sh
bundle exec jekyll serve --livereload --open-url
```

Opens: [http://127.0.0.1:4000/](http://127.0.0.1:4000/)

If `bundle` fails with a `LoadError` for a missing Bundler version, reinstall the version from `Gemfile.lock` (see the `BUNDLED WITH` entry) as shown above.

### Configure

* `_config.yml`
* Add data to `_data/data.yml`
* Also check `_includes` folder for some content and layout
* Change style in `_sass/_base.scss`
  * Background image: Under body/background image inside the scss file
* Skill icon list: Change indent manually in `_sass/_base.scss` under `skillset/level-title/margin-right`