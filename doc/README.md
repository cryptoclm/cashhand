Cashhand Core
=============

Setup
---------------------
[Cashhand Core](http://cashhand.org/wallet) is the original Cashhand client and it builds the backbone of the network. However, it downloads and stores the entire history of Cashhand transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run Cashhand Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/cashhand-qt` (GUI) or
- `bin/cashhandd` (headless)

### Windows

Unpack the files into a directory, and then run cashhand-qt.exe.

### macOS

Drag Cashhand-Qt to your applications folder, and then run Cashhand-Qt.

### Need Help?

* See the documentation at the [Cashhand Wiki](https://github.com/CashHand-Project/cashhand/Cashhand-Wiki)
for help and more information.
* Ask for help on [BitcoinTalk](https://bitcointalk.org/index.php?topic=5228772.0).
* Join our Discord server [Discord Server](https://discord.gg/PAMusms)

Building
---------------------
The following are developer notes on how to build Cashhand Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Cashhand repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [BitcoinTalk](https://bitcointalk.org/index.php?topic=5228772.0).
* Join the [Cashhand Discord](https://discord.gg/PAMusms).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
