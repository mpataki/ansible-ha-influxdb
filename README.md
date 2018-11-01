# ansible-ha-influxdb

[InfluxDB](https://www.influxdata.com/) is a time series database that has many applications, one of which is storing home monitoring data which can be provided by home assistant.

This ansible role installs and configures InfluxDB for this purpose on a raspberry pi running hassbian.

What this role doesn't (currently) do is setup influx user credentials, so you may want to do this yourself until it is added here.

## Requirements

Really this should work on any debian based system, but has been tested on a Raspberry Pi running Hassbian.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

```yml
    - hosts: pi
      roles:
         - role: mpataki.ha-influxdb
```

## License

MIT
