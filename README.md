<h1 align="center">
  <a href="https://jekyll-vite.netlify.app/">
    <img src="https://raw.githubusercontent.com/ElMassimo/vite_ruby/main/docs/public/logo.svg" width="120px"/>
  </a>

  <br>

  <a href="https://jekyll-vite.netlify.app/">
    Jekyll Minima ➕ Vite.js
  </a>
</h1>

[vite ruby]: https://github.com/ElMassimo/vite_ruby
[jekyll-vite]: https://github.com/ElMassimo/jekyll-vite
[documentation website]: https://jekyll-vite.netlify.app/
[jekyll]: https://jekyllrb.com/
[minima]: https://github.com/jekyll/minima
[this blog post]: https://tetrapyloctomy.org/articles/2021/08/04/jekyll-vite.html
[@posiczko]: https://github.com/posiczko

This repo demonstrates how to setup [Vite Ruby] in a [Jekyll] site using the [minima] default theme.

You may also use it as a starter for your site or blog.

## Step by Step 🥾

Check the commit history for a step-by-step recap:

1. [`jekyll new`](https://github.com/ElMassimo/jekyll-vite-minima/commit/bb1a5d2)
2. [add webrick to the Gemfile](https://github.com/ElMassimo/jekyll-vite-minima/commit/4fe33f7)
3. [upgrade `minima` to the latest version, which supports `custom_head.html`](https://github.com/ElMassimo/jekyll-vite-minima/commit/2aa5437)
4. [add `jekyll-vite` to the Gemfile](https://github.com/ElMassimo/jekyll-vite-minima/commit/facf1a6)
5. [run `bundle exec vite install`](https://github.com/ElMassimo/jekyll-vite-minima/commit/fdb3d76)
6. [uncomment `exclude:` in `_config.yml`](https://github.com/ElMassimo/jekyll-vite-minima/commit/b333fab)
7. [add ViteRuby tags to `custom-head.html`](https://github.com/ElMassimo/jekyll-vite-minima/commit/b333fab)

## Additional Resources 📖

Visit the [`jekyll-vite`][jekyll-vite] [documentation website] for more information.

If you would like to process the [minima] stylesheets with Vite, see [this blog post] by
[@posiczko].

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

