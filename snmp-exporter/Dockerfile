FROM prom/snmp-exporter:v0.30.1

COPY snmp.yml /etc/snmp_exporter/snmp.yml

ENTRYPOINT ["/bin/snmp_exporter"]
CMD ["--config.file=/etc/snmp_exporter/snmp.yml"]
