# _registry
Theme registry for [GitHub Pages Generator](https://github.com/ronik-design/slush-gh-pages)

## How-To Add Your Theme

* Fork the [`/themes` repo](https://github.com/ghpagesthemes/themes) on GitHub
* Add a new entry in the [`themes.yml`](https://github.com/ghpagesthemes/themes/blob/master/themes.yml) file and fill out all fields.
  Example:

``` yaml
- 
  title:        Default
  description:  Basic theme.
  github:       ghpagesthemes/default
  branch:       master              # note: defaults to master
  demo_url:     https://ghpagesthemes.github.io/default/
  author:       Theme Master
  thumbnail:    default.png
  license:      The Unlicense
```

* Make a 250 x 200 thumbnail and drop it in the thumbnails folder.
  Note: Do NOT forget to list its filename in the `themes.yml` entry.
* Check that everything is ok, then open up a pull request.


## Meta

**Credit**

This `README.md` and the whole idea for the repo is borrowed from
[Dr. Jekyll Themes](https://github.com/drjekyllthemes/themes)

**License**

The themes directory is dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

**Questions? Comments?**

Post them to the [issues](https://github.com/ghpagesthemes/_registry/issues). Thanks!
