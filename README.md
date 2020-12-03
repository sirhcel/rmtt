Redmine Time Tracking Tool
==========================

Quick and dirty tool for adding time tracking entries from CSV data to
instances where you don't have API access. Your time tracking tool of choice
likely outputs CSV data which could easily augmented by ticket IDs and
activities (just add them as additional columns).

You may like using a configuration from file specifying the configuration for
your data as follows:
```
$ rmtt @examples/args.txt https://example.com/redmine examples/three-entries.csv
```
And you may even have the URL in your configuration:
```
$ rmtt @examples/example-org-args.txt examples/three-entries.csv
```
