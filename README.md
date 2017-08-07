# A fork of BitStorm (a super-thin bittorrent tracker), now with MySQL support!

BitStorm was originally written by Peter Caprioli as a lightweight bittorrent tracker contained in a single PHP file. As it used only a single flat file as a database, it had difficulty scaling past ~10 announces per second.
Peter created a fork of his project to add MySQL support, allowing it to scale. In 2011, Josh Duff made some changes to allow more efficient use of the database, and further scaling.
