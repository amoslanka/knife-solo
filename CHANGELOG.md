# 0.1.0: In progress

## Goals

* Finish support and integration testing for remaining key OSes (Issues #2 and #15)
* Include recipes in integration testing (Issue #17)

# 0.0.8: February 10, 2012

* Add --startup-script which gets sourced before any command to setup env vars (e.g., ~/.bashrc) (d1489f94)
* Use curl + rpm rather than rpm against direct URL for better proxy support (51ad9c51)
* Integration harness improvements (1ac5cce..4be36c2)
* BUG #10: Create .gitkeep's to avoid errors on sparse kitchens (074b4e0a)
* Add --skip-chef-check knife option (a1a66ae)

## Thanks to our contributors!

* [Cyril Ledru][patatepartie]
* [Fletcher Nichol][fnichol]
* [Jason Garber][jgarber]
* [Greg Sterndale][gsterndale]

[patatepartie]: https://github.com/patatepartie
[fnichol]: https://github.com/fnichol
[jgarber]: https://github.com/jgarber
[gsterndale]: https://github.com/gsterndale

# 0.0.7: Dec 9, 2011

* BUG #9: Fix intelligent sudo handling for OSes that don't have it
* Move integration tests into proper test cases
* CentOS 5.6 integration test

# 0.0.6: Dec 8, 2011

* Support for Mac OS 10.5 and 10.6 (00921ebd1b93)
* Parallel integration testing and SLES (167360d447..167360d447)
* Dynamic sudo detection for yum-based systems (5282fc36ac3..256f27658a06cb)

## Thanks to our contributors!

* [Sergio Rubio][rubiojr]
* [Nat Lownes][natlownes]

[rubiojr]: https://github.com/rubiojr
[natlownes]: https://github.com/natlownes

# 0.0.5: Oct 31, 2011

* Started on integration testing via EC2
* Add openSuSE support. Installation via zypper. (64ff2edf42)
* Upgraded Rubygems to 1.8.10 (8ac1f4d43a)

# 0.0.4: Oct 7, 2011

* Chef 0.10.4 based databag and search method (a800880e6d)
* Proper path for roles (b143ae290a)
* Test fixes for CI compatibility (ccf4247125..62b8bd498d)

## Thanks to our contributors!

* [John Dewey][retr0h]

[retr0h]: https://github.com/retr0h

# 0.0.3: July 31, 2011

* Kitchen directory generation
* Prepare tested on ubuntu
* Generate node config on prepare
* Cook via rsync
