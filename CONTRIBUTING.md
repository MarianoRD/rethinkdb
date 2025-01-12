# Contributing

We're happy you want to contribute! You can help us in different ways:

- [Open an issue][1] with suggestions for improvements
- Fork this repository and submit a pull request
- Improve the [documentation][2] (separate repository)

[1]: https://github.com/rethinkdb/rethinkdb/issues
[2]: https://github.com/rethinkdb/docs

To submit a pull request, fork the [RethinkDB repository][3] and then clone your fork:

    git clone git@github.com:<your-name>/rethinkdb.git

[3]: https://github.com/rethinkdb/rethinkdb

Make your suggested changes, `git push` and then [submit a pull
request][4]. Note that before we can accept your pull requests, you
need to sign our [Contributor License Agreement][5].

[4]: https://github.com/rethinkdb/rethinkdb/compare/
[5]: http://rethinkdb.com/community/cla/

## Building the admin UI

The code for the admin UI is now in a separate branch,
[`old_admin`][1].  It is used to generate the file
`src/gen/web_assets.cc`, which contains the static content served by
RethinkDB's admin UI.  Development instructions are in that repo.

[1]: https://github.com/rethinkdb/rethinkdb/tree/old_admin

## Resources

Some useful resources to get started:
* [Building RethinkDB][6] from source
* Overview of [what to find where][7] in the server source directory
* Introduction to the [RethinkDB driver protocol][8]
* [C++ coding style][9] for the RethinkDB server

[6]: http://rethinkdb.com/docs/build/
[7]: src/README.md
[8]: http://rethinkdb.com/docs/driver-spec/
[9]: STYLE.md
