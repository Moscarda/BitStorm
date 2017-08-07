# BitStorm: a lightweight torrent tracker anyone can install!

BitStorm was originally written by [Peter Caprioli](https://caprioli.se/) as a lightweight bittorrent tracker contained in a single PHP file. As it used only a single flat file as a database, it had difficulty scaling past ~10 announces per second.
A fork of the project added MySQL support, allowing it to scale. In 2011, [Josh Duff](https://joshduff.com/) aka [@TehShrike](https://github.com/TehShrike) made some changes to allow more efficient use of the database, and further scaling.
