Change Log
==========

Version 3.0.0 *(2018-03-05)*
----------------------------

 * New: `dex-fields-list` command for listing field references.
 * New: Added `DexFields` and `DexField` types for listing field references.
 * Fix: Ignore `META-INF` contents.

Note: The dx and dex dependencies are no longer shadowed in the jar dependency.


Version 2.0.0 *(2017-10-12)*
----------------------------

 * New: Show non-`void` return types.
 * New: API now returns a model object representing methods.
 * The Dalvik and Dex dependencies are now shaded to prevent conflicts in some environments.


Version 1.2.0 *(2016-02-28)*
----------------------------

 * New: Support for reading the `.jar` inside of `.aar` files.
 * New: Add `--hide-synthetic-numbers` flag for removing the number suffix from synthetic methods.


Version 1.1.0 *(2016-02-04)*
----------------------------

 * New: Support for `.class` and `.jar` files!


Version 1.0.0 *(2016-01-02)*
----------------------------

Initial release.
