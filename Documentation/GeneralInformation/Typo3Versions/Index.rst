.. include:: ../../Includes.txt


.. _typo3-versions:
.. _typo3-lifecycle:


TYPO3 CMS versions and lifecycle
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TYPO3 CMS is offered in Long Term Support (LTS) and Sprint Release versions.

The first versions of each branch are Sprint Release versions. A Sprint Release
version only receives support until the next Sprint Release got published. E.g.
TYPO3 CMS 8.0.0 was the first Sprint Release of the 8 branch and its support
ended when TYPO3 CMS 8.1.0 got released.

An LTS version is planned to be created every 18 months. LTS versions are created
from a branch in order to finalize it: Prior to reaching LTS status, a number of
Sprint Releases has been created from that branch and the release of an LTS version
marks the point after which no new features will be added to this branch. LTS
versions get full support (bug fixes and security fixes) for at least three years.
TYPO3 CMS version 7 and 8 are such LTS versions.

Starting with TYPO3 CMS 7 LTS the minor-versions are skipped in the official
naming. 7 LTS is version 7.6 internally, 8 LTS is 8.7. Versions inside a
major-version have minor-versions as usual (8.0, 8.1, ...) until at some
point the branch receives LTS-status.

Support and security fixes are provided for the current as well as the
preceding LTS release. For example, when TYPO3 CMS 8 is the current LTS release,
TYPO3 CMS 7 is still actively supported, including security updates.

For users of version 7 an update to version 8 is
recommended. All versions below TYPO3 CMS 7 are outdated and
the support of these versions has ended, including security updates.
Users of these versions are strongly encouraged to update their systems
as soon as possible.

LTS and Sprint Releases offer new features and often a modified
database structure. Also the visual appearance and handling of the
backend may be changed and appropriate training for editors may be
required. The content rendering may change, so that updates in
TypoScript, templates or CSS code may be necessary. With LTS and
Sprint Releases also the system requirements (for example PHP or MySQL
version) may change. For a minor release (i.e.
changing from release 8.7.0 to 8.7.1) the database structure and
backend will usually not change and an update will only require the
new version of the source code. The terminology "patch" is sometimes
used instead.


