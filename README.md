# ansible-ambari

This repo aims to deploy Apache Ambari with Ansible quickly.

There three tas in [site.yml](site.yml) that we can setup Ambari step by step:

- pre-ambari

- ambari-server

- ambari-agent

Before excuting 

```shell

ansible-playbook site.yml --tags pre-amabari -i hosts

```

you must modify [hosts](hosts) to assign nodes with different responsibility.
