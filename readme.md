# Mercurius: A WordPress P2 Child Theme.

Mercurius is a modern and responsive child theme for [WordPress's P2](http://p2theme.com/). Mercurius, latin for Mercury, was how the romans named the planet "because it appears to move so swiftly," a little like P2. This is a fork of the [Mercury child theme by Ryan Sommers](https://github.com/ryansommers/mercury).


## Core Template Changes
* `header.php`
  - Viewport meta tag added to support zooming.
  - The sidebar div was removed from the header.

* `footer.php`
  - The sidebar div was added to the footer.

* `functions.php`
  - Removes the native P2 iPhone styles and the viewport meta tag that disabled zooming.

* `style.css` 
  - Lots of high specificity rules to override the parent theme. Written mobile first, with media queries immediately following their default values.


## Demo and Download
Coming soon


## Changelog

### Version 1.0
- Initial release.
