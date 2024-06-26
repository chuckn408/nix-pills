# Nix Pills

This is a ported version of the Nix Pills, a series of blog posts written by Luca Bruno (aka Lethalman) and originally published in 2014 and 2015. It provides a tutorial introduction into the Nix package manager and Nixpkgs package collection, in the form of short chapters called 'pills'.

Since the Nix Pills are considered a classic introduction to Nix, an effort to port them to the current format was led by Graham Christensen (aka grahamc) and other contributors in 2017.

For an up-to-date version, please visit https://nixos.org/guides/nix-pills/. An EPUB version is also available.

If you encounter problems, please report them on the nixos/nix-pills issue tracker.
***
Available online as a [multi-page HTML](https://nixos.org/guides/nix-pills/) or an [e-book in EPUB format](https://nixos.org/guides/nix-pills/nix-pills.epub).

You can also build them locally:

    nix-build release.nix -A html-split && firefox result/share/doc/nix-pills/index.html

Similarly, for an [EPUB](https://www.w3.org/publishing/epub32/) version, run:

    nix-build release.nix -A epub && foliate result/share/doc/nix-pills/nix-pills.epub
