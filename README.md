# DBC-Boots.github.io

DBC Boots Web Page, hosted on [dbc-boots.github.io](http://dbc-boots.github.io/).

A hosted site where the Wiki lives.

Powered by [Jekyll](http://jekyllrb.com/)

### Contributing

Want to contribute? Sign up to [join our repository here](https://docs.google.com/forms/d/1OC3WSuPx23SIwM_hEEoRf4SW8HVvoLyvwHYtmy8rYb0/viewform).

* Or open an issue
* Or send us a pull request
* Or contribute to the [wiki](https://github.com/DBC-Boots/Resources/wiki)

## Local Set-up

You must clone the repo recursively or else the the `rake wiki` command won't work. The other way to do it if you didn't clone recursively is to pull in the wiki submodule.


```shell
$ git clone git@github.com:DBC-Boots/DBC-Boots.github.io.git --recursive
$ jekyll serve
# => Now browse to http://localhost:4000
```

Utilizing [WikiToJekyll](https://github.com/djacquel/WikiToJekyll) as a way to update website via Github wiki

## Sync Wiki

Run the following command:

```
rake wiki
```

This will do the following:
- sync your wiki pages
- transform them to markdown pages with yaml front matter
- launch a Jekyll build
- convert wiki links to Jekyll links
- optionally commit and push you code to you Jekyll repository

### Known Issues with Sync

- Won't be able to use Github's flavored markdown of relative files shorthand, e.g. `[[Home]]`
- Won't be able to use named linked if you want to focus on section. That's a link with a hashtag to that section. Affects some of the guide pages.
