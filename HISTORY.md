# RELEASE HISTORY

## 1.3.0 | 2012-12-14

This release provides a fairly comprehensive set of RELAXED html tags/attributes
and allowed html entities. All thanks to David Wright. The release also adds
a basic command line interface.

Changes:

* Make RELAXED set fairly comprehensive.
* Add basic command line executable.


## 1.2.1 | 2011-10-26

This release is simply a maintenance release to bring the 
projects build configuration up to date.

Changes:

* Modernize build configuration.


## 1.2.0 | 2010-10-13

Finally removed the lowercase variations on the class names.
You must use HTMLFilter now and not HtmlFilter.

Changes:

* Remove lowercase variations on class names.
* No longer Multiton.


## 1.1.0 | 2009-11-24

This is release adjusts the names of the classes to
be capitialized according to the actual use of the
terms. Some alternate options presets have been added
as well, and this releaseo sheds the Multiton, which
was basically a YAGNI.

Changes:

* Renamed HtmlFilter to HTMLFilter.
* Renamed CssFilter to CSSFilter
* HTMLFilter is no longer a Multiton.
* Old names are still available temporarily.
* Added built-in option constants.
* CssTree is now CSSFilter::Tree.


## 1.0.0 | 2009-06-25

First stand-alone release.

Changes:

* Birthday! (Spun-off from Ruby Facets)

