oracle-autocomplete
===================

A set of scripts to enable readline on sqlplus with smart autocomplete


How to use it
=============

The core script is /sqlplus-wrap/
Pass to it the connection string you would pass to sqlplus:

`./sqlplus-wrap scott/tiger@127.0.0.1/xe`


The script will check for a specific conmpletition list for the connection: if not found, it will build it for you.

To tune the autocompletition you should take a look to readline configuration file called .inputrc


References
----------------
https://github.com/hanslub42/rlwrap


#Local variables:
#mode:markdown
#mode:visual-line
#End:
