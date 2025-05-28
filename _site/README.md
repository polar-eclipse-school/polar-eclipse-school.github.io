# Polar ECLIPSE Summer School

This repository is the website of the Polar ECLIPSE School: Early-Career Learning and Integration in Polar Science Engagement.

## Template

This website is based on [alexhernandezgarcia.github.io](https://alexhernandezgarcia.github.io/), with inspiration and elements taken from [criticialscience.github.io](https://criticalscience.github.io/) and [ml4cryo.github.io](https://ml4cryo.github.io/). The code relies on jekyll and bulma.

## Installation

The following packages/software are needed to build the website:
- bundle
- sass stuff
- ruby
- gem

## Commands for building

Ideally run the following commands in separate terminal tabs. 

The following is a SASS (Syntactically Awesome Stylesheets) command used for converting a .scss file into a .css file while continuously watching for changes. When the source scss file changes it automatically recompiles the target css file.

```
sass --watch _sass/mystyles.scss:assets/css/mystyles.css
```

Build it (needs to be done evertime you change configs, yamls, etc.)
Builds to ML4cryo/ml4cryo.github.io/_site

```
bundle exec jekyll build --watch
```

Run website (in separate terminal) e.g. http://127.0.0.1:4000

```
bundle exec jekyll serve --incremental
```

## CSS structure

assets/css/mystyles.css

Overwrite css properties here:

_sass/main.scss

[see sass website](https://sass-lang.com/)

## Structure


## Colors
insert `style="color: #224760;"'

