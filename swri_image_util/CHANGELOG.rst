^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package swri_image_util
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.9 (2016-03-04)
------------------
* Properly installs the normalize_response node.
* No longer installs the geometry_util.test file.
* Contributors: P. J. Reed

0.0.8 (2016-01-06)
------------------
* Fixes nodelet description for normalize_response.
* Tweaks contrast stretching to increase blending of min/max bounds across grid.
* Removes some C-style casts.
* Adds parameters for masking out over exposed areas out of the contrast stretch processing.
* Adds normalize response image normalization method.
* Contributors: Marc Alban

0.0.7 (2015-11-18)
------------------

0.0.6 (2015-11-17)
------------------
* Image normalization now supports normalization to a min/max range.
* Contributors: Marc Alban

0.0.5 (2015-09-27)
------------------

0.0.4 (2015-09-27)
------------------

0.0.3 (2015-09-26)
------------------
* Fixes missing depend on swri_opencv_util in swri_image_util.
* Clean up dependencies
  Remove unneeded ones, add required ones not specified
* Contributors: Ed Venator, Jerry Towler

0.0.2 (2015-09-25)
------------------
* Renames opencv_util package to swri_opencv_util. Refs `#231 <https://github.com/swri-robotics/marti_common/issues/231>`_
* Renames math_util to swri_math_util. Refs `#231 <https://github.com/swri-robotics/marti_common/issues/231>`_.
* Renames image_util package to swri_image_util. Refs `#231 <https://github.com/swri-robotics/marti_common/issues/231>`_.
* Contributors: Edward Venator

0.0.1 (2015-09-25)
------------------
