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

```shell
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
