DBDiff
======
Compare database scheme with previous saved versions.

Beware: this is a unstable version, it's possible that new versions aren't backwards compatible so you lose the saved versions.

Usage
=====
<pre>
usage: dbdiff [--help] [--database DATABASE] [--username USERNAME]
              [--password PASSWORD] [--host HOST] [--version VERSION]
              [--save-version] [--diff]

dbdiff - Database diff

optional arguments:
  --help                show this help message and exit
  --database DATABASE, -d DATABASE
                        Database to use
  --username USERNAME, -u USERNAME
                        User for login (default: root)
  --password PASSWORD, -p PASSWORD
                        Password for user
  --host HOST, -h HOST  Host to connect to (default: localhost)
  --version VERSIONS, -v VERSIONS
                        The database version
  --save-version        saves the current version as new
  --diff                compare current database with previous
</pre>

Work in progress
================
This tool is still in progress. If you want a feature to be added, please let me know or send a pull request.

TODO
----
    [ ] Documentation
    [ ] Use subcommands in the ArgumentParser for simpler usage
    [ ] Multi DB-driver support
    [ ] Add option to ask for password
    [ ] Use a config file for the database credentials
    [ ] Limit the number of versions to keep (configurable)
    [ ] Compare triggers
    [ ] Create a deb package
