# Coder Dojo - Web Design Course

HTML CSS [web design tutorial](http://altabyte.github.io/coder-dojo-web-design/) for [Coder Dojo Belfast](http://www.coderdojobelfast.com/) by [Rob Graham](http://robgraham.me/).

#### [http://altabyte.github.io/coder-dojo-web-design/](http://altabyte.github.io/coder-dojo-web-design/)

## Change branch
This site is hosted on [GitHub Pages](https://pages.github.com/) so you will need to jump the `gh-pages`
[branch](https://github.com/altabyte/coder-dojo-web-design/tree/gh-pages) to see the [Jekyll](http://jekyllrb.com/) source code.

## Setup

Clone this repository into a dir called `coder_dojo_web_design_site`

    $ git clone https://github.com/altabyte/coder-dojo-web-design.git coder_dojo_web_design_site

Switch to the `gh-pages` branch

    $ git checkout gh-pages

Install the gems listed in the [Gemfile](https://github.com/altabyte/coder-dojo-web-design/blob/gh-pages/Gemfile).

    $ bundle install --path=.bundle

Launch the localhost server

    $ bundle exec jekyll serve --baseurl '' --port 4040

The site should then be available locally on port **4040** [http://localhost:4040/](http://localhost:4040/)

#### Note 1
Without `--baseurl ''` the localhost URL will be
[http://localhost:4040/coder-dojo-web-design/](http://localhost:4040/coder-dojo-web-design/)

#### Note 2
The default port for [Jekyll](http://jekyllrb.com/) is 4000, however [NX Server](https://www.nomachine.com/) also uses this port so I use port 4040 locally.
