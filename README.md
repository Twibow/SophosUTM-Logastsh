# Logstash Grok Pattner for Sophos UTM (9.x)

This repo contain my integration of Sophos UTM log's in ELK. 
For send you log's in ELK from Sophos UTM, you can go on : 
**->** Logging & Reporting **->** Log Settings **->** Remote Syslog Server
> Add your Syslog server and Syslog port (default 514)
> **Note:** You don't have a Syslog TLS capability on Sophos.

# Configure your Rsyslog Input
I've choosen to send all my log in one file log file. Find a sample configuration in repo.
