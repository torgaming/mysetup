Information and documentation about micro-httpd can be found in this directory where this file is located.

When micro-httpd is first installed it doesn't automatically start a server. This has to be configured.

* man micro-httpd
- to see the manual

* sudo which micro-httpd
- to find out where the micro-httpd executable is

- Create this file /etc/inetd.conf
* sudo touch /etc/inetd.conf

- now according to the manual try to paste these 2 lines of text into that file, the 2nd line has 3 spaces in front of it:
micro-http  stream tcp nowait nobody \
   /usr/sbin/micro-httpd micro-httpd dir

* sudo kwrite /etc/inetd.conf
- sudo kwrite or your favourite editor, ie. sudo mousepad /etc/inetd.conf
- now paste in the config text mentioned previously.
- modified it even more to select a directory, hope I put it in right.

* sudo kwrite /etc/services
- put in this line(based partly on what the manual instructed me to do):
 micro-http		85/tcp		www		# Micro HTTP server
