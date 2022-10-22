### Chocolate splash page

This is a simple site hosting content about chocolate network. 

## Development flow:

1. Branch off of `gh-pages` for feature
2. PR Merge into gh-pages.

### Using Gitpod

Open in Gitpod: [![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/chocolatenetwork/choco-pages/tree/gh-pages)

### On Local


```sh
# 1. Install ruby (Tested on: ruby 3.1.2p20 (2022-04-12 revision 4491bb740a) [x86_64-linux], gem v3.3.7)
https://jekyllrb.com/docs/installation/

# 2. Install bundler
 gem install bundler 


# 3. Install other deps

bundle install

# 4. Run the dev server

bundle exec jekyll serve --livereload

# App should be served with livereload on http://localhost:4000
```

### Problems

#### Jekyll install fails with `require': cannot load such file -- webrick (LoadError)`

1. See this solution: https://github.com/jekyll/jekyll/issues/8523

### File structure

Nb: This is a WIP, the current way css is structured is too specialised, in the process of refactoring it (this is tracked in issue [#11](https://github.com/chocolatenetwork/choco-pages/issues/11)) and this is the progress:


The _scss directory has all the styles for the website, with a few directories:


- pages:  This has stylesheets for each page.
- components: This has stylesheets for the common components in the application 
- design: This houses stylesheets for the design system; With typography, colors defined separately. Variables are also located here.
- util: Utility styles?

