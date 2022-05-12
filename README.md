# Snooey - A Remote Jekyll Theme

*Snooey* - A simple but extensive Jekyll theme that features:

**IMPORTANT** - This theme is always under active development, to ensure that I don't break something on your website please always fork this site, and use your own fork as the remote_theme.

View a live example @ [snooey.com](https://snooey.com) with multiple brands all running from same site!

## Want more information

This repository just contains the remote theme files only, refer to [github](https://github.com/snooey-template) for all documentation and example usage

### Current Status

![status](https://img.shields.io/static/v1?label=Development%20Status&color=yellow&message=beta)
![status](https://img.shields.io/netlify/4a073a6e-02dd-40a8-94e0-1bcb2179fa64?label=Build%20Status)
![status](https://img.shields.io/github/last-commit/shanehoey/snooey?label=Lastest%20Commit%20Remote%20Theme)
![status](https://img.shields.io/github/last-commit/shanehoey/snooey-template?label=Lastest%20Commit%20Example%20Site)
[![scheduled deploy](https://github.com/shanehoey/snooey-template/actions/workflows/deploy.yml/badge.svg)](https://github.com/shanehoey/snooey-template/actions/workflows/deploy.yml)

## History

v1.2.135 May 2022 - Fixing Theme formating

v1.2.130 May 2022 - Improved Flex and flex card includes files with changes to YAML Schema and Data.

v1.2.127 May 2022 - standardised branding to match collections. Allows for easier customisaztion.

v1.2.125 May 2022 - improved flex & flexcard

v1.2.121 May 2022  - Includes Breaking Changes

- removed page.debug and use JEKYLL_ENV instead
- Breaking Changes to the Schema
- Remove excerpt from the frontmatter, and migrated to description instead, excerpt only generated on posts automatically
- Breaking Changes to include files, using flex where possible, and removed obsolete files.

v1.2.117 April 2022 - Includes Breaking Changes

- Added _include/error.html to show modal dialog
- Standardised yaml/frontmatter across collections & yaml files
- Standardised liquid across all includes
- Updated _includes, including simplified logic and it now accepts DATASOURCE as an object rather than DATASET(text string) to allow collections and datafiles.
- Reintroduced Brandx.yml for branding of navbar/footer/layout/carousel on default layout.  navbar and footer can be overridden by respective yaml files
- nolonger requires page.dataset

v1.2.110 April 2022 - Includes Breaking Changes

- Simplified Theme (_sass & assets/css)
- Schema files standardised (_data/schema)
- Dataset files standardised (_data/dataset)
- page.theme or include.theme specifies the theme.css (default: theme[1-5])
- page.schema or include.schema specifies the schema used (default: dark,light,image)
- include.dataset specifies the content (default: dataset[1-5])
- All schema changes now via the schema yaml files
- All content files and include files have same data syntax ie feature.yml should matches all featureXX.html include files

v1.1.0 March 2022 - Includes Breaking changes.

v1.00 January 2020 - Initial Release.

## Enhancements for next version

- TODO! -> vx.x  -  add plugin jekyll-seo-tag
- VNEXT -> vx.x  -  Convert static pages ie maintenance 404 etc to templated versions
- VNEXT -> vx.x  -  Check every file in use/delete those that are not
- TODO! -> vx.x  -  Tags https://jekyllrb.com/docs/plugins/tags/


## Known Issues


## 3rd Party Apps/Plugins Used

- [jekyll](https://github.com/jekyll/jekyll)
- [bootstrap](https://getbootstrap.com)
- [jekyll-remote-theme](https://github.com/benbalter/jekyll-remote-theme)
- [jekyll-sitemap](https://github.com/jekyll/jekyll-sitemap)
- [jekyll-optional-front-matter](https://github.com/benbalter/jekyll-optional-front-matter/)
- [jekyll-admin](https://github.com/jekyll/jekyll-admin)
- [jekyll-redirect-from](https://github.com/jekyll/jekyll-redirect-from)

## Apps/Plugins to Investigate further

These have caught my attention as I like some on the functionality they provide, and may or may not use them in future.

- TODO? ->  v1.2.121  - [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag)
- VNEXT -> [Jekyll-gist](https://github.com/jekyll/jekyll-gist)
- VNEXT -> [jekyll-spaceship](https://github.com/jeffreytse/jekyll-spaceship)
- VNEXT -> [jekyll-toc](https://github.com/toshimaru/jekyll-toc)
- VNEXT -> [jekyll-random](https://github.com/codecalm/jekyll-random)
- VNEXT -> [jekyll-timeago](https://github.com/markets/jekyll-timeago)
- VNEXT -> [jekyll-humanize](https://github.com/23maverick23/jekyll-humanize)

## Contributing

Bug reports and pull requests are welcome on [github](https://github.com/shanehoey/snooey)

This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
