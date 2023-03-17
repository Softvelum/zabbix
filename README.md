# Zabbix templates and configs
Zabbix templates and other related files for [Nimble Streamer](https://softvelum.com/nimble/) monitoring


Basic step to add Nimble-specific metrics to your Zabbix server are:
1. Enable Nimble Streamer HTTP API for the server instance which you want to monitor
2. Install cURL if it is not yet installed
3. Import provided Templates to your Zabbix Server
4. Install Zabbix Agent to your Nimble server
5. Update Zabbix Agent configs to make templates work
6. Add Nimble Streamer host to Zabbix server
7. Apply Nimble Streamer Templates to a specific host

Read the description article
https://blog.wmspanel.com/2021/06/zabbix-monitoring-nimble-streamer-srt.html
to learn more about installation and setup process.

Here's a demo video:
https://www.youtube.com/watch?v=_uJhY315WEE
