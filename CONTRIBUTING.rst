.. highlight:: shell

======================================
Allen Institute Contribution Agreement
======================================

Terms
----------------
This document describes the terms under which you may make “Contributions” —
which may include without limitation, software additions, revisions, bug fixes, configuration changes,
documentation, or any other materials — to any of the projects owned or managed by the Allen Institute.
If you have questions about these terms, please contact us at terms@alleninstitute.org.

You certify that:

• Your Contributions are either:

1. Created in whole or in part by you and you have the right to submit them under the designated license
   (described below); or
2. Based upon previous work that, to the best of your knowledge, is covered under an appropriate
   open source license and you have the right under that license to submit that work with modifications,
   whether created in whole or in part by you, under the designated license; or
3. Provided directly to you by some other person who certified (1) or (2) and you have not modified them.

• You are granting your Contributions to the Allen Institute under the terms of the [2-Clause BSD license](https://opensource.org/licenses/BSD-2-Clause)
  (the “designated license”).

• You understand and agree that the Allen Institute projects and your Contributions are public and that
  a record of the Contributions (including all metadata and personal information you submit with them) is
  maintained indefinitely and may be redistributed consistent with the Allen Institute’s mission and the
  2-Clause BSD license.

Contributing
============

Contributions are welcome, and they are greatly appreciated! Every little bit
helps, and credit will always be given.

You can contribute in many ways:

Types of Contributions
----------------------

Report Bugs
~~~~~~~~~~~

Report bugs at https://github.com/JacksonMaxfield/pywslegislature/issues.

If you are reporting a bug, please include:

* Your operating system name and version.
* Any details about your local setup that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.

Fix Bugs
~~~~~~~~

Look through the GitHub issues for bugs. Anything tagged with "bug" and "help
wanted" is open to whoever wants to implement it.

Implement Features
~~~~~~~~~~~~~~~~~~

Look through the GitHub issues for features. Anything tagged with "enhancement"
and "help wanted" is open to whoever wants to implement it.

Write Documentation
~~~~~~~~~~~~~~~~~~~

pywslegislature could always use more documentation, whether as part of the
official pywslegislature docs, in docstrings, or even on the web in blog posts,
articles, and such.

Submit Feedback
~~~~~~~~~~~~~~~

The best way to send feedback is to file an issue at https://github.com/JacksonMaxfield/pywslegislature/issues.

If you are proposing a feature:

* Explain in detail how it would work.
* Keep the scope as narrow as possible, to make it easier to implement.
* Remember that this is a volunteer-driven project, and that contributions
  are welcome :)

Get Started!
------------

Ready to contribute? Here's how to set up `pywslegislature` for local development.

1. Fork the `pywslegislature` repo on GitHub.
2. Clone your fork locally::

    $ git clone git@github.com:your_name_here/pywslegislature.git

3. Install your local copy into a virtualenv (or anaconda environment). Assuming you have virtualenvwrapper installed, this is how you set up your fork for local development::

    $ mkvirtualenv pywslegislature
    $ cd pywslegislature/
    $ pip install -r requirements_dev.txt
    $ pip install -e .

4. Create a branch for local development::

    $ git checkout -b name-of-your-bugfix-or-feature

   Now you can make your changes locally.

5. When you're done making changes, check that your changes pass flake8 and the
   tests, including testing other Python versions with tox::

    $ flake8 pywslegislature
    $ make test-all

   To get flake8 and tox, just pip install them into your virtualenv.

6. Commit your changes and push your branch to GitHub::

    $ git add .
    $ git commit -m "Resolves gh-###. Your detailed description of your changes."
    $ git push origin name-of-your-bugfix-or-feature

7. Submit a pull request through the GitHub website.

Pull Request Guidelines
-----------------------

Before you submit a pull request, check that it meets these guidelines:

1. The pull request should include tests.
2. If the pull request adds functionality, the docs should be updated. Put
   your new functionality into a function with a docstring, and add the
   feature to the list in README.rst.
3. The pull request should work for Python 3.6 and 3.7, and for PyPy. Check
   https://travis-ci.org/JacksonMaxfield/pywslegislature/pull_requests
   and make sure that the tests pass for all supported Python versions.

Tips
----

To run a subset of tests::

$ py.test tests.test_pywslegislature


Deploying
---------

A reminder for the maintainers on how to deploy.
Make sure all your changes are committed (including an entry in HISTORY.rst).
Then run::

$ bumpversion patch # possible: major / minor / patch
$ git push
$ git push --tags

Travis will then deploy to PyPI if tests pass.
