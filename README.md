# Personal Website

* Taken and adjusted Manuel's theme: https://github.com/mpeuster/mpeuster.github.io
* Based on this: https://github.com/sharu725/online-cv
* Original Theme: https://themes.3rdwavemedia.com/

## Dev

### Install

- Install Ruby and gem
- gem install bundler
- bundle install

### Serve

```sh
bundle exec jekyll serve --livereload
```

Open: [http://127.0.0.1:4000/](http://127.0.0.1:4000/)

* Use Safari if Chrome makes trouble

### Configure

* `_config.yml`
* Add data to `data/_data.yml`
* Also check `_includes` folder for some content and layout
* Change style in `_sass/_base.scss`
  * Background image: Under body/background image inside the scss file
* Skill icon list: Change indent manually in `_base.scss` und `skillset/level-title/margin-right`