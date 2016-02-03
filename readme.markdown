# Trexler Website CSS Cleanup

Since our website's redesign ~3 years ago + migration to a new CMS this past
summer (2015), we've taken on a lot of cruft. This is an attempt to slim that
down as well as update the site to better fit existing on a CMS.

## Current CSS order

* `bootstrap.min.css`
  * Bootstrap v2.3.2
* `google-fonts.css`
  * links to `Asap` and `Open Sans` fonts hosted by Google
* `font-awesome.min.css`
  * FontAwesome v3.2.1
* `akmalz-wide.css`
* `akmalz-style.css`
  * Styles from a WrapBootstrap theme
* [`bcag-alterations.css`][bcag]
  * Styles from our 2012 redesign
* [`t4-updates.css`][t4]
  * Updates for CMS migration
* [`beetbox.css`][bb]
  * Styles for search box on mindex

[bcag]: ./bcag-alterations.css
[t4]: ./t4-updates.css
[bb]: ./beetbox.css
