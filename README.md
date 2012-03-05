Linux Plumbers Conf 2011 Archive
--------------------------------

Static archive of the 2011 site on http://linuxplumbersconf.org/2011

Archive Creation Notes
----------------------
    wget --exclude-directories=2008,2009,2010 -r -l20 -t1 -nc -N -k -p  --no-host-directories -R "feed" -D www.linuxplumbersconf.org http://www.linuxplumbersconf.org/2011/ 2> wget.log
    find . -type f -exec "" sed -i 's/2011.1/2011\//g' {} \;

