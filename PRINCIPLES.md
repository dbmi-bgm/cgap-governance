# Principles and Practices

Last updated: September 5, 2023


## Overview and Mission of The Projects

This document sets forth community principles and practices related to
open source software created by these projects ("The Projects"):

* CGAP (cgap.hms.harvard.edu)
* Fourfront (data.4dnucleome.org)
* SMaHT DAC Portal (data.smaht.org)

CGAP is the Computational Genomics Analysis Platform. The mission of
the CGAP Project is to provide support for computational analysis of
the genome in clinical settings, and to make that work available to
the world as independently deployable open source software.

Fourfront and the SMaHT DAC Portal are web services maintained centrally
at DBMI to provide services in support of collaborators worldwide.

This document describes the "ways of working" for The Projects and
the mechanisms for community contributions to be committed to the various
codebases that implement The Projects (collectively, "The Codebase").


## The Maintainers

The Projects' maintainers ("The Maintainers") are the primary technical
decision-makers for The Codebase.

The Maintainers are those individuals employed by the President and Fellows of
Harvard College (informally, “Harvard University”) for the purpose of such
development and maintenance of The Projects.

The Maintainers will act in accordance with the mission of The Projects to oversee:

* the technical direction of these projects in The Codebase;
* engagement with technical contributors from the broader community; and
* decision-making about technical considerations, such as:
  - The Projects' release processes and cadences;
  - the features and bug fixes that will be addressed; and
  - the pull requests that will be merged into The Codebase.

The Maintainers aspire to take input from and collaborate with the global
community where possible. In all matters where conflict arises, decisions of
The Maintainers are ultimately final.

In the event of a matter which may raise concerns regarding Harvard's
non-profit mission, legal or liability risks, or other such
institutional concerns, Harvard may resolve matters and conflicts in
its discretion to address such concerns. For the avoidance of doubt,
unless explicitly permitted by Harvard in writing, The Maintainers may
_not_ incur or purport to incur obligations or commitments on behalf
of Harvard.


## Contributions

Interested members of the broader community ("The Community"), which
include members of the public who are not The Maintainers,
may contribute to The Projects,
such as by filing Issues and by submitting Pull Requests.

Pull Requests contributed to The Projects must include
Developer Certificate of Origin (DCO) sign-off statements, as more
fully described in the "Licensing" section below.

The Maintainers may from time to time specify additional processes
and technical requirements for contributions, documenting these processes
and requirements in `CONTRIBUTING.md` (or some similar file)
of affected repositories of The Projects.


## Policies

The Projects are hosted and supported by Harvard Medical School's
Department of Biomedical Informatics, and will be operated in
accordance with Harvard University's non-profit purpose and
mission. Participants in The Projects should not act in any manner
that is inconsistent with Harvard University's non-profit, tax-exempt
status or purpose.

The Projects shall operate in an open and transparent manner
at all times; provided that, from time to time, Harvard legal counsel
may be consulted by The Maintainers who are Harvard personnel in a private
manner in order to seek legal guidance regarding the operation of the
project.

All outputs of The Project shall be made available to the public
under open source licenses, as set forth in the "Licensing" section
below.

The Projects shall be operated in a manner that is open to all
contributors (individual, corporate and organizational) who comply
with the policies and ways of working for The Community. The
Maintainers and other contributors should not exclude any participant
for any reason other than those that are reasonable, documented and
applied on a non-discriminatory basis to all community participants.

The project has adopted the
[Contributor Covenant, version 2.1](https://www.contributor-covenant.org/version/2/1/code_of_conduct/)
as its Code of Conduct. All community participants must abide by the
Code of Conduct in their interactions with The Community.
The Maintainers will serve as the community leaders for purposes of
enforcement of the Code of Conduct.


## Licensing

### Project License

As used herein, "Project License" means the open source software license applicable to The Codebase, as follows:

* the [GPL-3.0 license](https://www.gnu.org/licenses/gpl-3.0.html),
  only where specifically marked, for specific pipeline repositories that
  require dependencies under a GPL license or for certain scripts that
  are invoked manually or as part of a CICD pipeline for testing, maintenance or documentation; and

* the [MIT license](https://spdx.org/licenses/MIT.html), for all other parts of The Codebase

See `LICENSE.txt` (or some similar file) for more detailed information
on a per-repository basis. If such a file is missing,
please contact The Maintainers, who will arrange for it to be created.


### Contributions to The Codebase

For each contribution to The Codebase following the adoption of this
Principles and Practices document, the copyright in the contribution
will be retained by the copyright holder. The contribution will be
licensed, not assigned, to the project and the broader community.

Each contribution to The Codebase is to be contributed under the Project
License for the corresponding part of The Codebase.

Each contribution must be accompanied by a
[Developer Certificate of Origin (DCO)](https://developercertificate.org)
sign-off statement in the message body for each commit.
The DCO sign-off statement should be in the standard form commonly used
by other open source projects, as follows:

```
    Signed-off-by: CONTRIBUTOR NAME <EMAIL ADDRESS>
```

The project will adopt tooling to assist in checking for
the presence of DCO sign-off statements in contributed pull requests.


### Dependencies and Licenses

The Projects utilize a variety of install-time dependencies that are not
distributed as part of The Codebase. These dependencies are
licensed under various licenses, including permissive, weak copyleft
and strong copyleft licenses.

The Maintainers will adopt processes to help with checking
compatibility of dependencies' licenses with the Project Licenses and
with the mission of the project.
If you observe flaws in these processes or you have suggestions,
please contact The Maintainers.

If a proposed contribution would introduce a license for a dependency
or modify the nature of its usage in a way that could result in a
potential compatibility concern, The Maintainers should mark the
contribution as "pending review". The Maintainers, being Harvard
personnel, may then privately consult with Harvard legal counsel for
guidance prior to taking action on the proposed contribution.


### Disclaimers

The Maintainers do not provide legal advice. All data, programmatic or other content associated with The Projects
is subject to the disclaimers of warranties and liability set forth in
the applicable license texts. You should consult with your own legal counsel
if you have questions regarding licenses and license compatibility.


## Notices

CGAP is a trademark of President and Fellows of Harvard College. Usage of the CGAP trademark shall be subject to trademark usage guidelines
as set forth by Harvard from time to time.


## Miscellaneous

This Principles and Practices document may be updated by Harvard from time to time.


## Contact

Questions about this document should be addressed to:
[cgap-support@hms-dbmi.atlassian.net](mailto:cgap-support@hms-dbmi.atlassian.net).
Email to this address will open a support ticket.
