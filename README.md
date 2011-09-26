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
2. `common::sense`
3. `LWP`
4. `JSON`
5. `IO::Prompt`

The program should work on any major operating system. It has been tested
on Ubuntu 11.10 and Microsoft Vista 32-bit.

# Usage

    $ ./github-clone <username>

This will clone all of the user’s repositories into the current
directory, and existing repositories will be updated.  For example:

    $ mkdir dumb-crap-by-ejmr && cd dumb-crap-by-ejmr
    $ ./github-clone ejmr
    Cloning or fetching ejmr's 4 repositories
    Press y or n to clone repositories.  The default choice is n.

    Clone JTorrent: A Perl script for fetching Japanese media torrents.? y
    remote: Counting objects: 865, done.
    remote: Compressing objects: 100% (382/382), done.
    remote: Total 865 (delta 472), reused 820 (delta 427)
    Receiving objects: 100% (865/865), 141.22 KiB, done.
    Resolving deltas: 100% (472/472), done.
    Clone php-mode: A PHP mode for GNU Emacs? n
    Fetching EmacsPKG
    Clone github-clone: A Script For Cloning All Repos By a Github User? n

# Future Plans

I am open to any ideas people might have that would make this script
more useful.  Please feel free to leave feature requests here, or
email them to me at `Ren at lifesnotsimple dot com`.

# License

`github-clone` is Public Domain.
