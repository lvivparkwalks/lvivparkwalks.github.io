# Прогулянки Стрийським парком

> Люди, події, роздуми на свіжому повітрі.

* **Facebook Page**: [facebook.com/lviv.park.walks](https://www.facebook.com/lviv.park.walks/)
* **Архів блогу**: [lvivparkwalks.github.io](https://lvivparkwalks.github.io/)


## Built with Jekyll

* [**Jekyll**](https://github.com/jekyll/jekyll) is a static site generator that's perfect for GitHub hosted blogs.
* [**Jekyll Now**](https://github.com/barryclark/jekyll-now) makes it easier to create your Jekyll blog, by eliminating a lot of the up front setup.

[Build A Blog With Jekyll And GitHub Pages](http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/).


## Setup local environment

### Install Ruby 3
```
brew install ruby
ruby -v
```

### Install Jekyll and plug-ins
```

gem install --user-install bundler jekyll jekyll-sitemap jekyll-feed jekyll-paginate github-pages
jekyll -v
```


## Development

### Pull project
* Git clone `git clone https://github.com/lvivparkwalks/lvivparkwalks.github.io.git`.

### Local development
* Serve the site and watch for markup/sass changes `jekyll serve --force_polling`.
* Website is served at [http://localhost:4000](http://localhost:4000).
