I am seeking a tool for converting a Perl 5 lexical var inside the class's
main method and passed by the arg list to helper methods, into an object wide
accessor ( using https://metacpan.org/release/Class-XSAccessor or https://metacpan.org/pod/Moo or similar.)

An example for this kind of refactoring change is [this commit](https://github.com/thewml/website-meta-language/commit/67f289b146a0aefb1c0a245adf01aa6a87f3fd8f) .

I don't expect the tool to be flawless.
