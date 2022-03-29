haoxiqiang-template
===================
The template from [Pure](http://purecss.io/)

>Pure is ridiculously tiny. The entire set of modules clocks in at 4.4KB* minified and gzipped. Crafted with mobile devices in mind, it was important to us to keep our file sizes small, and every line of CSS was carefully considered. If you decide to only use a subset of these modules, you'll save even more bytes.

You can easily create your blog by the jekyll template.


#How to use

* From GP,it's easy to use.

	[Github Page](https://pages.github.com/)

	You can create your repository which call `yourname.github.io` from this site .


* Install jekyll  (if windows,you should install [Ruby](https://www.ruby-lang.org/en/installation/) first)
* you can update all deps.
	```
	gem	update
	gem	install jekyll
	gem	install github-pages
	```

>
We highly recommend installing Jekyll on your computer to preview your site and help diagnose troubled builds before publishing your site on GitHub Pages.
Luckily, installing Jekyll on your computer, and ensuring your computer most closely matches the GitHub Pages settings is easy, thanks to the GitHub Pages Gem and our dependency versions page. To install Jekyll, you'll need a few things:

	Ruby - Jekyll requires the Ruby language. If you have a Mac, you've most likely already got Ruby. If you open up the Terminal application, and run the command ruby --version you can confirm this. Your Ruby version should begin with 1.9.3 or 2.0.0. If you've got that, you're all set. Skip to step #2. Otherwise, follow these instructions to install Ruby.

	Bundler - Bundler is a package manager that makes versioning Ruby software like Jekyll a lot easier if you're going to be building GitHub Pages sites locally. If you don't already have Bundler installed, you can install it by running the command gem install bundler.

	Jekyll - The main event. You'll want to create a file in your site's repository called Gemfile and add the line gem 'github-pages'. After that, simply run the command, bundle install and you're good to go. If you decided to skip step #2, you can still install Jekyll with the command gem install github-pages, but you may run into trouble down the line. Here’s an example of a Gemfile you can use (placed in the root directory of your repository):

>source 'https://rubygems.org'<br />gem 'github-pages'

	
* Run

Use the command in `hxq-template`.

```
cd hxq-template
bundle install
bundle add webrick

bundle exec jekyll server
```

#License
>
  Apache License
  Version 2.0, January 2004
  http://www.apache.org/licenses/

