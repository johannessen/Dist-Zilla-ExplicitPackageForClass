Dist::Zilla::Plugin::ExplicitPackageForClass
============================================

During `dzil build`, this FileMunger plugin for [Dist::Zilla][]
will look through your code for class declarations and insert
a corresponding package statement before them, along with the
package version. For the rationale, see
["File Layout" in Object::Pad](https://metacpan.org/release/PEVANS/Object-Pad-0.807/view/lib/Object/Pad.pm#File-Layout).

[Dist::Zilla]: https://metacpan.org/release/Dist-Zilla


Installation
------------

Released versions of the [ExplicitPackageForClass][] plugin
may be installed via CPAN:

    cpanm Dist::Zilla::Plugin::ExplicitPackageForClass

[![CPAN distribution](https://badge.fury.io/pl/Dist-Zilla-Plugin-ExplicitPackageForClass.svg)](https://badge.fury.io/pl/Dist-Zilla-Plugin-ExplicitPackageForClass)

To install a development version from this repository,
run the following steps:

```sh
git clone https://github.com/johannessen/Dist-Zilla-ExplicitPackageForClass
cd Dist-Zilla-ExplicitPackageForClass
cpanm Dist::Zilla::PluginBundle::Author::AJNN
dzil install
```

This is a “Pure Perl” module, so you generally do not need
Dist::Zilla to contribute patches. You can simply clone the
repository and run the test suite using `prove` instead.

[ExplicitPackageForClass]: https://metacpan.org/release/Dist-Zilla-Plugin-ExplicitPackageForClass
