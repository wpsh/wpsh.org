---
title: Automatic Deployments for WordPress Plugins and Themes
---

# Deploy WordPress Plugins and Themes Automatically

[View on GitHub →](https://github.com/wpsh/wpsh)


## How to Improve Documentation

We use [Jekyll](https://jekyllrb.com) to build the website from the Markdown files stored in the `docs` directory.

1. Clone this repository:

		$ git clone git@github.com:wpsh/wpsh.org.git
		$ cd wpsh.org

2. Start a local webserver and build the website whenever the source files change:

		$ bundle install
		$ jekyll serve --source docs

Now view the website at [http://127.0.0.1:4000]().

The public website is built by [Travis CI](https://travis-ci.org/wpsh/wpsh.org) and hosted on [Netlify](https://www.netlify.com).
