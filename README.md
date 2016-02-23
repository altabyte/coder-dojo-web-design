# Coder Dojo - Web Design

HTML CSS web design tutorial for [Coder Dojo Belfast](http://www.coderdojobelfast.com/)

## Setup

Clone this repository into a dir called `rob_graham_web_site`

    $ git clone https://github.com/altabyte/coder-dojo-web-design.git

Switch to the `gh-pages` branch

    $ git checkout gh-pages

Install the gems listed in the [Gemfile](https://github.com/altabyte/coder-dojo-web-design/blob/gh-pages/Gemfile).

    $ bundle install --path=.bundle

Launch the localhost server

    $ bundle exec jekyll serve --baseurl '' --port 4040

The site should then be available locally on port **4040** [http://localhost:4040/](http://localhost:4040/)

Note 1, without `--baseurl ''` the localhost URL will be
[http://localhost:4000/coder-dojo-web-design/](http://localhost:4000/coder-dojo-web-design/)

Note 2, the default port for Jekyll is 4000, however [NX Server](https://www.nomachine.com/) 
also uses this port so I have decided to use port 4040 locally.
