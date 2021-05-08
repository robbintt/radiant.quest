# Radiant

Dead simple hugo theme for templating static info pages from simple `data bundles`.


## Data

Not really sure how I want to do this. There is front matter but I would rather use handlebars and a selector.

### Ticker Example

Wouldn't we rather just use handlebars to compose the template from the user selection?

If we did this with the static site we would have to regenerate the site to add a new value.

Also, it's not like we're doing

We do want to pro

1. user goes to a ticker data page
1. user selects a ticker or adds a new ticker
1. data from ticker is populated in a defined template
  - Why are we generating this template on the backend instead of the frontend?
1. ticker is saved in an index of tickers?
  - do we care about this... or would it be better to post a log of submitted requests...


### Dutch Word Example

This is more complicated, but the basic idea is once a word is submitted, it is captured.



### Photo Album Example

I would like to post small albums with an annotation per-photo.

1. Select a few photos, write a title for the album
2. write a title for each photo, maybe a description, add some tags for each photo
3. compile the site
  - resize all the photos appropriate for each page
    - album page should be smaller
    - photo page should be web, with a link to full size if i want to share that
    - full size may or may not be present in the website
  - build an album page
    - clicking into a photo could either take to a single URL (linkable) or a modal...
  - maybe: build a page per photo with links between the album and prev/next photo
  - would like to have a URL per photo
    - radiant.quest/album-name/photo-name
1. upload directory to s3
  - smart delele and ovewrite... how? need to decide on rules.



### Some Data

These are examples of strings, would be cool to use a json template for typed data.

- A stock ticker
- A dutch word
- a photo album




## Modules

> Hugo Modules are the core building blocks in Hugo. A module can be your main project or a smaller module providing one or more of the 7 component types defined in Hugo: static, content, layouts, data, assets, i18n, and archetypes.


## References

- [Hugo Theme Components](https://gohugo.io/hugo-modules/theme-components/)
- [Hugo Modules](https://gohugo.io/hugo-modules/)
- [Hugo Base Template](https://gohugo.io/templates/base/_)
