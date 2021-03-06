---
layout: page
title: Theme test
---

# {{ page.title }}

**programming pages** is a [GitHub Pages][gh-pages] theme for publishing code documentation.
{:.larger.text}

<span>{% include icon.liquid id='info-circle' %} <b>Info</b></span><br> For more details, please refer to the [theme documentation][theme-docs].
{:.ui.info.message}

This site is a simple example of the fast-start [remote-theme][remote-theme] method:

1. create and clone a [new GitHub][new-repo] repo
2. add three magic beans (click to see contents):
  - [`_config.yml`][file-config]
  - [`Gemfile`][file-gemfile]
  - [`index.md`][file-index]
3. test locally
  - `bundle install`
  - `bundle exec jekyll serve`
  - `open http://localhost:4000/`
4. push to Github and [declare a publishing source][pub-source]
5. visit `https://<username>.github.io/<repository>`
  - e.g. <https://ellemenno.github.io/programming-pages-test>



[file-config]: https://raw.githubusercontent.com/ellemenno/programming-pages-test/master/_config.yml "Jekyll configuration for a remote theme site"
[file-gemfile]: https://raw.githubusercontent.com/ellemenno/programming-pages-test/master/Gemfile "Gemfile to use with Bundler to install and run locally"
[file-index]: https://raw.githubusercontent.com/ellemenno/programming-pages-test/master/index.md "site homepage source (markdown)"
[gh-pages]: https://pages.github.com/ "websites for you and your projects"
[new-repo]: https://github.com/new "create a new repository on GitHub"
[pub-source]: https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/#enabling-github-pages-to-publish-your-site-from-master-or-gh-pages "enable GitHub Pages to publish your site from the master branch"
[remote-theme]: https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/ "remote themes for GitHub pages"
[theme-docs]: https://pixeldroid.com/programming-pages/ "programming pages theme documentation"
