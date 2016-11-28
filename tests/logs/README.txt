Unit tests and code coverage require mutually exclusive log content. To do so, tests are broken in to days.

The sample logs are stored as:

YYYYMMDD/var/log/emerge.log
YYYYMMDD/var/log/modsecurity2/modsec_audit.log
YYYYMMDD/var/log/messages
YYYYMMDD/var/log/messages.1
YYYYMMDD/var/log/httpd/error_log

where YYYY is the 4 digit year, MM is the 2 digit month, DD is the 2 digit date for the ending of the log 
reporting period. This path is used as a "root" for the logs structure.

