README haproxy-utils

A sub-set of shell commands to simplify life when dealing with an HA
pair of machines in active/standby, that don't share the same storage
for the configuration of haproxy (or any other file, really).

This utility is originally intended to be included in a bashrc, either
by sourcing or by cut & paste.

lbhelp is the main help command once you're in the login shell that
loads this utility.

There are also a couple other things included; one is an init.d script
for haproxy, and the other is the /etc/sysconfig/ configuration file
that informs the init script.

WRITTEN FOR CENTOS 5/6.  It may require some massaging of at least
file locations if you intend to use it elsewhere.

haproxy-initscript is supposed to go in /etc/init.d/

haproxy-sysconfig is supposed to go in /etc/sysconfig/

haproxy-bashrc is supposed to be sourced or pasted into your .bashrc


