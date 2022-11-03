# APCctrl-zabbix
 
1. Copy `APCctrl.conf` to your zabbix's client folder.
2. Import `APCctrl Template 60.yaml` to Zabbix server.
3. Add the template to your hosts.

Items:
- APCctrl: Get Attributes
- APCctrl Battery Charge
- APCctrl Battery Voltage
- APCctrl Line Frequency
- APCctrl Line Voltage
- APCctrl Load (%)
- APCctrl Load (W)
- APCctrl Load VA
- APCctrl Max Line Voltage
- APCctrl Min Line Voltage
- APCctrl Output Current
- APCctrl Output Voltage
- APCctrl Status
- APCctrl Time Left on Battery
- APCctrl Time on Battery

Triggers:
- APC is running on battery
