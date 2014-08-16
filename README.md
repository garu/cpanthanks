cpanthanks
==========

Thank a CPAN author today!

This program will parse all perl files/modules from a given list of directories
to try and find module authors to thank for. If you can, please find the time
to thank every author whose module helped you in your projects/work :D


#### Installation ####

From CPAN:

    cpanm App::cpanthanks

From within this repository:

    cpanm .

### Usage ###

    cpanthanks [options] -- path [, path2, ...]

    Options:
        --limit NUMBER                     only shows top NUMBER entries (default: 5)
        --order-by popularity|diversity    order your results (default: popularity)
        --skip-modules LIST                skip modules (default: lib strict warnings)
        --skip-authors LIST                skip authors (default: none skipped)


### Examples ###

    cpanthanks --skip-authors MYCPANID --limit 3 -- some/path other/path
    cpanthanks --order-by=diversity -- my/project/path


THANKS!
-------

This tiny app would not be possible without the incredible developers who
wrote the modules that it depends on! So...

* Thank you B<Masaaki Goshima> for L<Compiler::Lexer>!

*  Thank you B<David Golden> for L<Path::Class::Rule>!

*  Thank you B<Mickey Nasriachi> and B<Sawyer> for L<MetaCPAN::Client>!

*  Thank you B<Tatsuhiko Miyagawa> and B<Audrey Tang> for L<Term::Encoding>!

*  Thank you B<Russ Allbery> for L<Term::ANSIColor>!

*  Thank you B<Jean-Louis Morel> for L<Win32::Console::ANSI>!

*  Thank you B<Graham Barr> and B<Paul Evans> for L<List::Util>!

*  Thank you B<Yuval Kogman> and B<Jesse Luehrs> for L<Try::Tiny>!

*  Thank you B<Johan Vromans> for L<Getopt::Long>!

*  Thank you B<Marek Rouchal> and B<Brad Appleton> for L<Pod::Usage>!

### License and Copyright ###

Copyright (c) 2014, Breno G. de Oliveira. All rights reserved.

This module is free software; you can redistribute it and/or
modify it under the same terms as Perl itself. See the "perlartistic" license.


