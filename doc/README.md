Terracash Core
=============

Setup
---------------------
Terracash Core is the original Terracash client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Terracash transactions (which is currently more than 7 GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Terracash Core, visit [terracash.org](https://terracash.org).

Running
---------------------
The following are some helpful notes on how to run Terracash on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/terracash-qt` (GUI) or
- `bin/terracashd` (headless)

### Windows

Unpack the files into a directory, and then run terracash-qt.exe.

### OS X

Drag Terracash-Core to your applications folder, and then run Terracash-Core.

### Need Help?

* See the documentation at the [Terracash Wiki](https://terracash.info/)
for help and more information.
* Ask for help on [#terracash](http://webchat.freenode.net?channels=terracash) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=terracash).
* Ask for help on the [TerracashTalk](https://terracashtalk.io/) forums.

Building
---------------------
The following are developer notes on how to build Terracash on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Terracash repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/terracash/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [TerracashTalk](https://terracashtalk.io/) forums.
* Discuss general Terracash development on #terracash-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=terracash-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
