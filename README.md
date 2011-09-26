# github-clone

This simple Perl script has its roots in an email from a
[good friend](https://github.com/richardcpeterson):

    Maybe there should be a repo browser like your anime downloader
    script. You would run the script, give it the name of a github
    user, and it would let you pull clone some or all of his repos
    into subdirectories. Then you could also add batch fetches and
    stuff.

Thus `github-clone` was born.

# Requirements

1. Perl 5.10 or Higher
2. `Modern::Perl`
3. `LWP`
4. `JSON`

The program should work on any major operating system, but has only
been tested on Ubuntu 11.10.

# Usage

    $ ./github-clone <username>

This will clone all of the user’s repositories into the current
directory.  For example:

    $ mkdir dumb-crap-by-ejmr && cd dumb-crap-by-ejmr
    $ ./github-clone ejmr
    Cloning JTorrent: A Perl script for fetching Japanese media torrents.
    Cloning php-mode: A PHP mode for GNU Emacs
    Cloning EmacsPKG: A Simple Tool for Collecting Elisp Files

# Future Plans

I am open to any ideas people might have that would make this script
more useful.  For certain I plan on adding some method of interaction
so that you can decide which repositories to clone.  Please feel free
to leave feature requests here, or email them to me at `Ren at
lifesnotsimple dot com`.

# License

`github-clone` is Public Domain.
