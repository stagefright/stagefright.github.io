stagefright.github.io
=====================

Website: http://stagefright.github.io

The idea behind this site is to collate all the good resources about public speaking so that anyone looking for advice can easily find it.

Contribute
----------
If you come across any great resources then please add them.

You can:
- raise an issue
- submit a pull request.

All resources are listed by type in the resources files under _data.

Alternatively check out the issues list to see any outstanding tasks.

Getting Started
---------------
Stagefright is powered by GitHub Pages using Jekyll.

Dependencies:
- Ruby
- Bundler

To get started:
- clone the repository
- install the bundled gems - `bundle install`
- run jekyll locally - `bundle exec jekyll serve`
- update `url` in _config.yml to be 'http://localhost:4000' to ensure assets etc are using your local version
- visit http://localhost:4000 to view the site

Be aware that GitHub handles the removal of `./html` from the urls, so `/resources` will not work locally.
Just add `./html` to the end to view the page locally

### Jekyll

To get jekyll to watch for changes in your files and automatically update:
```
jekyll build --watch
```

### Sass

Sass is used to generate the css files, so don't amend anything in the assets/css folder.
Make your updates in assets/scss and compile the changes. 
Sass can watch for changes made and compile automatically. Simply run:
```
sass --watch assets/scss:assets/css --style compressed
```

Useful links
------------

For more information on GitHub Pages, Jekyll and Sass, checkout these links:
- [GitHub Pages](http://pages.github.com/)
- [Jekyll](http://jekyllrb.com/)
- [Using Jekyll with GitHub Pages](https://help.github.com/articles/using-jekyll-with-pages)
- [Sass: Syntactically Awesome Style Sheets](http://sass-lang.com/)
