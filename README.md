# ossec
OSSEC is an open source Host based intrusion detection system (HIDS). It can run on Linux and Windows.
It inclues functionalities of a SIEM and FIM. It is easy to monitor and filter logs using OSSEC, it can help detect rookits and malwares. All the logs are sent to the ossec manager which can be forwarded to syslog (port 514).

The newer version of OSSEC consists of the ossec-authd (daemon) feature which allows the agent to be added to the  ossec manager by creating the key automatically. (you need to open port 1515)
OSSEC is highly scalable.
