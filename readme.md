# My personal website

## Tech stack
The source code is written with
* [Jekyll extension](https://jekyllrb.com/docs/liquid/) of [Liquid](https://shopify.github.io/liquid/) template language
* [HTML](https://html.spec.whatwg.org/multipage/) and [kramdown](https://kramdown.gettalong.org/syntax.html) markup language
that is based on [Markdown](https://daringfireball.net/projects/markdown/syntax) and is converted into HTML
* [Sass](https://sass-lang.com/) ([SCSS syntax](https://sass-lang.com/documentation/syntax#scss)) stylesheet language that is converted into [CSS](https://www.w3.org/Style/CSS/)
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/JavaScript_technologies_overview)

and then transformed by [Jekyll](https://jekyllrb.com/) site generator into files ready to be served by a web server.
This transformation is done automatically by GitHub when a new commit is pushed to the repository and the result is hosted by
[GitHub Pages](https://help.github.com/en/github/working-with-github-pages).

This Jekyll theme is designed by [Valentin Kovalenko](https://www.kovalenko.link/).

## Instructions 
1. Install all [prerequisites](https://jekyllrb.com/docs/installation/).
2. Install specific version of `bundler` gem:

```
$ gem install bundler -v '~> 2.3.22'
```

3. From the root of the directory run:

```
$ bundle install
```

to install the relevant gems.

4. Build the site and make it available on a local server.

```
$ bundle exec jekyll serve
```

## Misc
The original GitHub URI <https://yo1k.github.io> is redirected to
the canonical URI <https://www.kovalenko.place>.

---

All content is licensed under [MIT Licence](https://opensource.org/licenses/MIT), except where another license is explicitly specified.
