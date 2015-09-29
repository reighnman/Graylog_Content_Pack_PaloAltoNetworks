# Palo Alto Networks Content Pack

Tested with PAN-OS 6.1.3/Graylog 1.2

This content pack provides GROK extractors for PAN Firewalls and a few example dashboards:
* PAN Threat Summary (24h)
* PAN Threat Summary - High & Critical (24h)
* PAN URL Filtering Summary (24h)
* PAN GlobalProtect Portal Login Summary (7d)

## Includes

* Input PAN-syslog (Syslog tcp 5514)
* GROK Patterns (BASE10NUM DATE_US2 GREEDYDATA HOST HOSTNAME HOUR IP IPORHOST MINUTE MONTHDAY MONTHNUM MONTHNUM2 NOTCOMMA QS QSORNC QUOTEDQUOTES QUOTEDSTRING SECOND TIME TZ YEAR)
* Extractors (PAN_THREAT, PAN_SYSTEM, PAN_CONFIG, PAN_TRAFFIC, PAN_POSTPROCESS_GlobalProtect_Login)
* Dashboards 

## Requirements

* Palo Alto Networks Firewall (or Panorama) with SYSLOG configured for tcp 5514 BSD format, no custom settings

## Screenshots

![gpportal](http://www.ohjeah.net/wp-content/uploads/2015/09/PAN_gpportal.png)

![threatsum](http://www.ohjeah.net/wp-content/uploads/2015/09/PAN_threatsum.png)

![urlfiltering](http://www.ohjeah.net/wp-content/uploads/2015/09/PAN_urlfiltering.png)