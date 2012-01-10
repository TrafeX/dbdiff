DEV
===
* Connect to DB
* SHOW TABLES
* SHOW CREATE TABLE
* Store to SQLlite

Over de gehele DB draaien.
Tabel:

id
database
version
structure

--user
--pass
--host
--database

--diff
--dry-run
--save-version
--show-versions

Requirements
============
* python-mysqldb

TODO
====
    [ ] Diff between DB's
    [ ] Multi driver support
    [ ] Add option to ask for password
    [ ] Add subcommands http://docs.python.org/library/argparse.html#argparse.ArgumentParser.parse_args
    [ ] Create config
    [ ] Limit the number of versions to keep
