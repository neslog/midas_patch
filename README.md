midas_patch
===========

MIDAS Patch to generate ArcSight CEF formatted syslog output.  The updated midas.py will look for [syslog] stanza in the midas-settings.cfg.  If found it will set the variable do_syslog to true to enable logging.  Example stanza below:
 [syslog]
 loghost = 192.168.1.10
 logport = 514
 
 The patch will also enable varaibles to be set for the CEF log under the settings stanza.
 
deviceVendor: MIDAS
deviceProduct: YARA
deviceVersion:  1

Modified to move files and rename with the MD5 hash of the file.

