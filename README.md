# ansible-proserver-tika

An Ansible role that installs Apache Tika and manages it with supervisord.

## Dependencies
* [ansible-proserver-supervisord](https://github.com/punktDe/ansible-proserver-supervisord)

## Configuration
The default configuration values can be found in `defaults/main.yaml`.

```yaml
tika:
  prefix:
    home: /var/opt/solr/tika
    logs: /var/log/solr-ansible
  version: 3.2.3
  user: solr
  group: solr
  java_opts: -Xmx1g
  host: localhost
  port: 9998
```
