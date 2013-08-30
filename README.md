DBDiff
======
Compare database schema with previous saved versions. Changes are printed in the unified diff format.

Beware: this is a unstable version, it's possible that new versions aren't backwards compatible so you lose your saved database versions.

Current limitations
===========
* Only supports MySQL
* Only shows changes in the table schema, not for triggers and views

Usage
=====
<pre>
usage: dbdiff [--help] [--database DATABASE] [--username USERNAME]
              [--password PASSWORD] [--host HOST] [--version VERSION] [--list]

dbdiff - Compare database schema with previous saved versions

optional arguments:
  --help                show this help message and exit
  --database DATABASE, -d DATABASE
                        Database to use
  --username USERNAME, -u USERNAME
                        User for login (default: root)
  --password PASSWORD, -p PASSWORD
                        Password for user
  --host HOST, -h HOST  Host to connect to (default: localhost)
  --version VERSION, -v VERSION
                        The database version
  --list                listing of all the saved versions.

</pre>


Work in progress
================
This tool is still in progress. If you want a feature to be added, please let me know or send a pull request.

Roadmap
-------
    [ ] Documentation
    [ ] Use subcommands in the ArgumentParser for simpler usage
    [ ] Compare views
    [ ] Multi DB-driver support
    [ ] Add option to ask for password
    [ ] Use a config file for the database credentials
    [ ] Limit the number of versions to keep (configurable)
    [ ] Compare triggers
    [ ] Create a deb package


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/TrafeX/dbdiff/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

