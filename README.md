

# snmp-vlanfiltering-mib

Based on snmp-bridge-mib in https://github.com/net-snmp/net-snmp,the original version only supports traditional bridge with vlan port member.
Usage is the same as snmp-bridge-mib: \<path to>\snmp-vlanfiltering-mib \<bridge name>

## Add these lines in /etc/snmp/snmpd.conf before restart snmpd
```sh
master          agentx
agentxsocket /var/agentx/master
agentxperms 777 777
```

