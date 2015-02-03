About
=====

This repository simply has a .travis.yml to build and release Pentadactyl xpis for firefox.

Since Pentadactyl no longer releases binaries or nightlies on it's [official website](http://5digits.org/pentadactyl/), every firefox update breaks the compatibility with the existing plugin. This is simply because of a "maxVersion" incomatability in the `install.rdf` file.

The way most people who use pentadactyl now do one of the following:

1. Delay updating Firefox (ciritical updates are missed out)
2. Manually download the source, make required changes and build+install
3. Migrate to something else (Vimperator maybe?)

This repo mitigates the need for this by:

1. Pulling the latest source
2. Applying a hacky maxVersion Patch on the fly to the appropriate file (you were going  to do this anyway -.-')
3. Building the xpi and making it available for download under the `/releases` section.

You should ideally be able to simply download the xpi and install it.

Please feel free to raise issues, add feature requests.
Feedback always welcome.
