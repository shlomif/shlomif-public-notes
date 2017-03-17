I am seeking an application to populate a directory tree with files based
on some customisations, configurations, plugins and plugin-bundles.

[Dist-Zilla](http://dzil.org/) comes closest to what I want, but I need:

1. For it to take place in the current directory while not creating a pristine
temporary build directory.

2. Not be as centric to generating CPAN distributions.

## Examples

If I have something like that:

```
[@Shlomif::Sites]
```

Then it will generate [this dir](https://github.com/shlomif/perl-begin/tree/master/lib/Shlomif/Spelling) with the files there as well as
[this file](https://github.com/shlomif/perl-begin/blob/master/Tests/spell-check.t) and [this file](https://github.com/shlomif/perl-begin/blob/master/Tests/spell-check-is-sorted.t)
which I so far have tracked in several repositories,

Note that I can have customisations:

```
[@Shlomif::Sites]
test_files_dir = name
```

## Update

I ran into [cookiecutter](https://github.com/audreyr/cookiecutter) which
seems to do what I want.

## References

* [Draft of a document of the Dist-Zilla 's dist.ini format](https://github.com/shlomif/dzil-dist-ini-format-documentation)
