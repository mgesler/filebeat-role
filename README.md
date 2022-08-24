Install and configure filebeat role
=========

Install and configure filebeat

Requirements
------------

Supports only Ubuntu, Debian, CentOS or RHEL 

Role Variables
--------------

|Variable|Description|
|--------|-----------|
|filebeat_version| Version of Filebeat|
|filebeat_install_type| If "remote" a filebeat package will download from web, otherwise you must put package in "files" folder|
|elastic_host| IP of the host with installed Elasticsearch|
|kibana_host| IP of the host with installed kibana|

License
-------

MIT
