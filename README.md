Global Identification Architecture
==================================

Identification workflow made esay!

Abstract
--------

Internet services are constantly being created.
And most of the time, identification, authentification
and authorisation is implemented on their side meaning
those services needs to enforce their own security
guidelines. Otherwise, they could have security breaches.
And it has already happened.

Also, services end-users needs to have an authentification
mean that is, most of the time, a password. This implies
every users needs differents passwords for every services
they use. Or either two-factor authentication is not
widely spread.

This documents suggests a workflow based on
[OpenID Connect 1.0](https://openid.net/connect/).

Build
-----

*PDF builds cannot be done currently due to a Sphinx/Rst2pdf
issue (`issue-number-coming-here`).*

### Requirements

* `python` | [Project site](https://www.python.org/)
  | Downloads: [Windows](https://www.python.org/downloads/windows/)
  [Mac OS X](https://www.python.org/downloads/mac-osx/)
  Linux: use your package manager.
* `sphinx` | [Project site](https://www.sphinx-doc.org/en/master/) | Downloads: use `pip`.
* `rst2pdf` | [Project site](https://rst2pdf.org/) | Downloads: use `pip`.

### Procedure

1. Download using (1) or (2):
   1. Get the source by downloading a zip on GitHub.
   2. Get the source using `git clone https://github.com/Axelandre42/GIA.git`
      (requires Git installed on your computer).
2. Build HTML documents with `make html`.
3. Build the PDF document with `make pdf`.

Contribute
----------

Contributions are welcomed!

Any help or advice on the project can be done using
GitHub issue tracker.

*Templates coming soon*