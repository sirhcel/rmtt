Redmine Time Tracking Tool
==========================

Overview
--------

Quick and dirty tool for adding time tracking entries from CSV data to
instances where you don't have API access. Your time tracking tool of choice
likely outputs CSV data which could easily augmented by ticket IDs and
activities (just add them as additional columns).


Beware
------

Here be dragons! This is a quick-and-dirty tool in an early stage. Use
`--dry-run` to check possible outcome before actually creating time entries.
And think twice.


Usage
-----

You may like using a configuration from file specifying the configuration for
your data as follows:
```
$ rmtt @examples/args.txt https://example.com/redmine examples/three-entries.csv
```
And you may even have the URL in your configuration:
```
$ rmtt @examples/example-org-args.txt examples/three-entries.csv
```

License
-------

Licensed under either of

* Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
* MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your discretion.
