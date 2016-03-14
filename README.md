Personal academic website for [Dan Roberts](http://www.danintheory.com).

This website is based on the [Compass](https://github.com/excentris/compass) Jekyll theme.

# Compass Documentation

Compass is a Jekyll theme designed with something very specific in mind: to be a simple and elegant personal landing page that can be easily deployed to [GitHub Pages](https://pages.github.com/).

## How to use Compass

1. Start by [installing Bundler](http://bundler.io) `gem install bundler`
2. [Fork the Compass repository](https://github.com/excentris/compass/fork)
3. Then run `bundle install` to get [Jekyll](http://jekyllrb.com) and all the dependencies.
4. Clone the repository you just forked: `git clone https://github.com/YOUR-USER/compass`
5. Edit `_config.yml` as needed.
6a. Run the Jekyll server with `bundle exec jekyll serve`
6b. If that generated a "command not found: jekyll" error, you might need to say `bundle show jekyll`, add `bin/jekyll` to the path, and use that entire path in place of `jekyll` in the command `bundle exec jekyll serve`.
7. Go to `http://localhost:4000`

## Deploy your site to GitHub Pages

If you want to use Compass as your personal landing page you can deploy your site to GitHub Pages as a [User Page](https://help.github.com/articles/user-organization-and-project-pages/#user--organization-pages). To do so, when you are done modifying your clone, you should rename your repository to `username.github.io` where username is your username. When GitHub builds the page it will be made available at `https://username.github.io`.

If you are planning on using a custom domain to direct to your site, modify the CNAME file as described [here](https://help.github.com/articles/adding-a-cname-file-to-your-repository/).

Check the [GitHub Pages Basics](https://help.github.com/categories/github-pages-basics/) for more information.
