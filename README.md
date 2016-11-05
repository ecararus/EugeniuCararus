# ecararus.github.io

Simple static generated site
tools used:
 - Ruby
 - [how to](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)
 - [jekyll](http://jekyllrb.com)
 - [jekyll-import](https://github.com/jekyll/jekyll-import)
 - [jekyll-sitemap](https://github.com/jekyll/jekyll-sitemap)
 - [so-simple-theme](https://mmistakes.github.io/so-simple-theme/)
 - [all pages imported from blogger](https://cararuseugeniu.blogspot.co.uk/)
 
```
$ ruby -rubygems -e 'require "jekyll-import";
    JekyllImport::Importers::MyImporter.run({
      # options for this importer
    })'
```

```
$ bundle exec jekyll serve
```

