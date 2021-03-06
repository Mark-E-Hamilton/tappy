Releases
========

Version 1.9, In Development
---------------------------

* Add support for Python 3.5.
* Perform continuous integration testing on OS X.
* Drop support for Python 3.2.

Version 1.8, Released November 30, 2015
---------------------------------------

* The ``tappy`` TAP consumer can read a TAP stream
  directly from STDIN.
* Tracebacks are included as diagnostic output
  for failures and errors.
* The ``tappy`` TAP consumer has an alternative, shorter name
  of ``tap``.
* The pytest plugin now defaults to no output
  unless provided a flag.
  Users dependent on the old default behavior
  can use ``--tap-files`` to achieve the same results.
* Translated into Arabic.
* Translated into Chinese.
* Translated into Japanese.
* Translated into Russian.
* Perform continuous integration testing on Windows with AppVeyor.
* Improve unit test coverage to 100%.

Version 1.7, Released August 19, 2015
-------------------------------------

* Provide a plugin to integrate with pytest.
* Document some viable alternatives to tappy.
* Translated into German.
* Translated into Portuguese.

Version 1.6, Released June 18, 2015
-----------------------------------

* ``TAPTestRunner`` has a ``set_stream`` method to stream all TAP
  output directly to an output stream instead of a file.
  results in a single output file.
* The ``nosetests`` plugin has an optional ``--tap-stream`` flag to
  stream all TAP output directly to an output stream instead of a file.
* tappy is now internationalized. It is translated into Dutch, French,
  Italian, and Spanish.
* tappy is available as a Python wheel package, the new Python packaging
  standard.

Version 1.5, Released May 18, 2015
----------------------------------

* ``TAPTestRunner`` has a ``set_combined`` method to collect all
  results in a single output file.
* The ``nosetests`` plugin has an optional ``--tap-combined`` flag to
  collect all results in a single output file.
* ``TAPTestRunner`` has a ``set_format`` method to specify line format.
* The ``nosetests`` plugin has an optional ``--tap-format`` flag to specify
  line format.

Version 1.4, Released April 4, 2015
-----------------------------------

* Update ``setup.py`` to support Debian packaging. Include man page.

Version 1.3, Released January 9, 2015
-------------------------------------

* The ``tappy`` command line tool is available as a TAP consumer.
* The ``Parser`` and ``Loader`` are available as APIs for programmatic
  handling of TAP files and data.

Version 1.2, Released December 21, 2014
---------------------------------------

* Provide a syntax highlighter for Pygments so any project using Pygments
  (e.g., Sphinx) can highlight TAP output.

Version 1.1, Released October 23, 2014
--------------------------------------

* ``TAPTestRunner`` has a ``set_outdir`` method to specify where to store
  ``.tap`` files.
* The ``nosetests`` plugin has an optional ``--tap-outdir`` flag to specify
  where to store ``.tap`` files.
* tappy has backported support for Python 2.6.
* tappy has support for Python 3.2, 3.3, and 3.4.
* tappy has support for PyPy.

Version 1.0, Released March 2014
--------------------------------

* Initial release of tappy
* ``TAPTestRunner`` - A test runner for ``unittest`` modules that generates
  TAP files.
* Provides a plugin for integrating with **nose**.

