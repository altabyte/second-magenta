# Second Magenta web site

This GitHub project hosts the source code for the 
**[Second Magenta](http://secondmagenta.com/)** web site. 
The GitHub hosted version can be seen 
[here](http://altabyte.github.io/second-magenta/).

As this GitHub [project](https://github.com/altabyte/second-magenta/) is 
only a [Jekyll](http://jekyllrb.com/) web site, you must switch to the `gh-pages`
[branch](https://github.com/altabyte/second-magenta/tree/gh-pages) to see the source code.

## Setup

Clone this repository into a dir called second_magenta_web_site

    $ git clone https://github.com/altabyte/second-magenta.git second_magenta_web_site

Switch to the `gh-pages` branch

    $ git checkout gh-pages

Install the gems listed in [Gemfile](https://github.com/altabyte/second-magenta/blob/gh-pages/Gemfile).

    $ bundle install --path=.bundle

Launch the localhost server

    $ bundle exec jekyll serve --baseurl ''

The site should then be available on port **4000** [http://localhost:4000/](http://localhost:4000/)

Note that without `--baseurl ''` the localhost URL will be
[http://localhost:4000/second-magenta/](http://localhost:4000/second-magenta/)

