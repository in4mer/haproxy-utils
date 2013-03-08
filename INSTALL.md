haproxy-bashrc INSTALL requirements:

Edit the basic data to suit your haproxy installation.  All the file locations
are specified at the beginning of the script.

NOTE:  There must be a common string in the hostname that's unique to the two
HA nodes.  The script uses the common string and the machine's hostname
that you're editing on to determine what other host(s) to synchronize the files
to
