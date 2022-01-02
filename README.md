# ossec
OSSEC is an open source Host based intrusion detection system (HIDS). It can run on Linux and Windows.
It inclues functionalities of a SIEM and FIM. It is easy to monitor and filter logs using OSSEC, it can help detect rookits and malwares. All the logs are sent to the ossec manager which can be forwarded to syslog.

The newer version of OSSEC consists of the much easier *ossec-authd* (daemon) feature which allows the agent to be added to the  ossec manager by creating the key automatically. For this, you can either create a password /var/ossec/etc/authd.pass or a certificate at /var/ossec/etc/CA.cert which can be used to add and verify the agent to the manager.

OSSEC is highly scalable.
You need to open ports UDP/1514 and TCP/1515 for agent and manager to communicate.
