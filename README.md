# Production Resources

The `gh-pages` branch of this repo is home for the files used to generate http://oreillymedia.github.io/production-resources/.

The web page content is generated from markdown source (well, actually it's kramdown) using Jekyll.

## Local Preview

You can preview the files locally using `jekyll`. Clone down the repo and make sure you have the proper version of Ruby installed on your system by checking the _.ruby-version_ file. You can use [`rbenv`](https://github.com/rbenv/rbenv) to manage Ruby on your system.

Then install the Gem dependencies:

```
bundle install
```

Then change the base URL in the _\_config.yml_ file to:

```
baseurl: /oreillymedia.github.io/production-resources/
```

Finally, start your local server:

```
bundle exec jekyll serve
```

This should show output including the server address which will be something like: `http://127.0.0.1:4000/oreillymedia.github.io/production-resources/`. Open that URL in a browser to see how the docs will look.
