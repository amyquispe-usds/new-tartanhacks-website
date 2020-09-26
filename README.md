This is the 2020-2021 Tartanhacks website (under development). We're
using Jekyll on GitHub Pages.


## Installation

For information about setting up the project locally, check out <a href="https://docs.google.com/document/d/1N3wfRB0y__8qYLljmlGhZXq8ICHm75l-QYAJ-32aM0c/edit?usp=sharing">this</a> document!


## I want to...

This is a typical Jekyll project. The [Jekyll documentation][jekyll] online is
really well put together; you should give it a skim. In the mean time, here's a
list of points where you might want to look:

### ... change the style of the site.

Since this is a Jekyll site, the repetitive content is pulled out into
_templates_. These files are located in `_includes/` and `_layouts/`. Altering
these files will alter all files based off of them. You can tell if a file is
based off another file if it includes the line `layout: <something>` or `{%
include <something> %}` somewhere inside it.

To change the stylesheets, you should look in `assets/css/`. Here' you'll see
that we're using Sass, which is a CSS preprocessor. This just means we're using
a language that compiles to CSS, instead of writing CSS directly. Look it up
online for more information. The `main.scss` file `@import`s the files which are
located in the folder `_sass/`. To change the styles, you'll want to change
the files located in there.

### ... add content to the site.

Any file or folder that doesn't start with an underscore will end up being a
web page visible to users. To add content, simply create a file that doesn't
have a leading underscore.

Jekyll allows you to write content using Markdown, a language that compiles to
HTML. You should probably use Markdown, not HTML, to create content. For an
example of how this is done, see the `frontend/` folder, which contains numerous
examples of using Markdown files to generate content. Feel free to use these
files as starting points for generating your own content.


## License

MIT License. See LICENSE. (c) 2015 ScottyLabs



[jekyll]: http://jekyllrb.com/
