# Overpass
**Overpass** — _an open source web font family_

+Sponsored by [Google Fonts](https://fonts.google.com) and [Red Hat](http://www.redhat.com), Inspired by [Highway Gothic](http://en.wikipedia.org/wiki/Highway_Gothic), Designed by [Delve Fonts](http://www.delvefonts.com)

        

For more information, please visit  [overpassfont.org](http://overpassfont.org  "overpassfont.org")



---
## Contributors

#### Designers
* Delve Withrington
* Dave Bailey
* Thomas Jockin

#### Reviewers
* Jakub Steiner
* Ben Dubrovsky
* Andy Fitzsimon


## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you particularly want to build fonts manually on your own computer, you will need to install the [`yq` utility](https://github.com/mikefarah/yq). On OS X with Homebrew, type `brew install yq`; on Linux, try `snap install yq`; if all else fails, try the instructions on the linked page.

Then:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

## License

Copyright 2016 Red Hat, Inc.,

This Font Software is dual licensed under the SIL Open Font License and the GNU Lesser General Public License,
LGPL 2.1 : http://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html
OFL  1.1  : http://scripts.sil.org/OFL


## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.