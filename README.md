# Runway modeling language support for Atom

This is a package for the [Atom](https://atom.io) text editor that provides
syntax highlighting for Runway specifications.
[Runway](https://github.com/SalesforceEng/runway-compiler) is a tool for
modeling concurrent and distributed systems as state machines. This package is
also used by [runway-browser](https://github.com/SalesforceEng/runway-browser)
to apply syntax highlighting to Runway models being viewed in a web browser.

To install, use `apm link` to create a symlink into `~/.atom/packages`:

    git clone https://github.com/SalesforceEng/language-runway.git
    cd language-runway
    apm link

Then restart Atom.

If you're looking for syntax highlighting of Runway models for the Vim text
editor, that's available in the
[runway-compiler](https://github.com/SalesforceEng/runway-compiler) repo.
