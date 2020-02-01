AIB Core integration/staging tree  [NOT WORKING VER 0.17  MERGE THE SYNCING PART, BUT NOT THE ADDRESS RECEIVING OR SENDING]
=====================================
[Master Branch is our working , it is not stable , and has many bugs]
[Use stable release with Tag Version]


[![Build Status](https://travis-ci.org/aib/aib.svg?branch=master)](https://travis-ci.org/aib/aib)

https://aib.one

What is AIB?
----------------

AIB is an experimental digital asset that enables instant payments to
anyone, anywhere in the world. AIB uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. AIB Core is the name of open source
software which enables the use of this asset.

AIB is also the dual value system to enable the special token econimic system for small projects
It ensure the small , spreaded investment could less risky toward certain projects
It will also enhanced by smart contract on the road.

For more information, as well as an immediately useable, binary version of
the AIB Core software, see [https://www.aib.one](https://www.aib.one).

License
-------

AIB Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/aib/aib/tags) are created
regularly to indicate new official, stable release versions of Bitcoin Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and macOS, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

Translations
------------

Changes to translations as well as new translations can be submitted to
[Bitcoin Core's Transifex page](https://www.transifex.com/projects/p/aib/).

Translations are periodically pulled from Transifex and merged into the git repository. See the
[translation process](doc/translation_process.md) for details on how this works.

**Important**: We do not accept translation changes as GitHub pull requests because the next
pull from Transifex would automatically overwrite them again.

Translators should also subscribe to the [mailing list](https://groups.google.com/forum/#!forum/aib-translators).



Offical AIB development email:
DEV@AIB.one
