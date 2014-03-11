oracle-autocomplete
===================

A set of scripts to enable readline on sqlplus with smart autocomplete.
This work si based on previous work listed in the Credits section.
We have added the ability to do specific completition based on specific connetion.



How to use it
=============

The core script is /sqlplus-wrap/
Pass to it the connection string you would pass to sqlplus:

`./sqlplus-wrap scott/tiger@127.0.0.1/xe`


The script will check for a specific completition list for the connection: if not found, it will build it for you.



Credits
================
The autocomplete mechianigs is heavliy based on the following work:

http://www.tuicool.com/articles/M3MJbm
http://www.linuxification.at/rlwrap_ext.html.en

References
----------------
https://github.com/hanslub42/rlwrap


#Local variables:
#mode:markdown
#mode:visual-line
#End:
