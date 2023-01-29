# systemd service files for cardano-node

These .service files assume you're running on the mainnet and that you have your cardano-node binary installed in `/usr/local/bin`, your database directory and socket in `/var/lib/cardano/mainnet` and your configuration files in `/etc/cardano/mainnet(/keys)`. If not, you can modify the paths in these .service files.

Make sure you have a user and group named `cardano` on your system.

By default the service will start a local relay or block producer instance (both IPv4 and IPv6) on port 3001.

HAPPY Staking Pool 🥳\
ID: e9e7e497cdda1681cff48e4d8c5a726e2e030c65a3cf7f9be8007466
