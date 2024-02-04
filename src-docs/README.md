# Generating Webpage

## Prerequisites

First, we need some basic tools. Install, Ruby and Bundle, then run (under this directory):

``` bash
bundle config set --local path 'vendor'
bundle install
```

## Generation

All we need to do now is:

``` bash
bundle exec jekyll build -d ../docs
```

That will generate the webpage.

## Adding a new post

See one of the examples inside `_posts` and follow their template. If lost, google
"jekyll post example template for minima".

## Checking whether post or change looks good before commiting

Continuosly build and run http server with:

```bash
bundle exec jekyll serve --baseurl ''
```

Now go to: <http://localhost:4000>

**Do NOT forget to `build` the website before commiting! ("generation" section above).**
