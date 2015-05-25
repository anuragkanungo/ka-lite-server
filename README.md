ka-lite-server
===============

The package configures nginx and uwsgi for KA Lite Webserver.
It requires nginx and uwsgi to be installed via apt-get.

To build the deb file, install the `devscripts` package and run the `./build_deb_file.sh` command.

After building and install deb file, run :

sudo service nginx restart
sudo service kalite restart