# Foundersclub Freiburg

Das ist die Internetseite vom Foundersclub Freiburg auf Github. Aktuell befindet sich die Internetseite in Bearbeitung.

## Steps for Setup:

### Make sure you have Ruby

First, make sure you have [Ruby](https://www.ruby-lang.org/en/) installed. You can confirm this by running `ruby -v` on the command line:

```sh
$ ruby -v
ruby [version number] (date) [your platform]
```

If you get something like `"Error, command not found"` visit the link above and
install Ruby for your platform.


### Make sure you have Bundler

Next, make sure you have [Bundler](https://bundler.io) installed. Just like
above, run `bundle -v` on the command line:

```sh
$ bundle -v
bundle [version number]
```

If you get `"Error, command not found"` run `gem install bundler` to install it
using RubyGems.

### Run this repository

Clone the repository, and `cd` into it:
```sh
$ git clone https://github.com/ndrewtl/airspace-jekyll.git
$ cd airspace-jekyll
```

Install dependencies locally:
```sh
$ bundle install --path vendor/bundle
```

This should install a local copy of jekyll.

Now run the server:
```sh
$ ./vendor/bundle/ruby/#{YOUR_RUBY_VERSION}/bin/jekyll server
```
