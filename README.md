### Ingesting pfsense data via logstash -> elasticsearch -> kibana

Pfsense 2.6
Logs:
  "Firewall Events"
  "DNS Events"

Format:
```
<134>Jun 17 13:37:58 filterlog[59716]: 130,,,1575729688,igb1,match,pass,in,4,0x0,,64,55831,0,DF,6,tcp,60,192.168.2.12,54.221.200.137,60293,443,0,S,3825784625,,29200,,mss;sackOK;TS;nop;wscale
```
