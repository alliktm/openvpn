Role openvpn-client
=========

Role for deploy and configure openvpn client for ubuntu 16 (xenial)


Role Variables
--------------

* `openvpn_ca_cert`: Text, contains CA certificate.
* `openvpn_client_cert`: Text, contains client certificate.
* `openvpn_client_key`: Text, contains client certificate key.
* `openvpn_config_name`: Clent filename
* `openvpn_server_connect`: IP or DNS name of openvpn server
* `openvpn_server_port`: PORT of openvpn server
* `openvpn_server_proto`: Protocol, used for openvpn (TCP or UDP)
* `openvpn_tls_key`: Text, contains openvpn static key
* `openvpn_version`: openvpn package version
* `openvpn_scene_install: false` Set a variable if you do not want to install. Default - True
* `openvpn_scene_config: false` Set a variable if you do not want to configure. Default - True


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
      - openvpn-client

License
-------

BSD

Author Information
------------------

Zimin Aleksey (zimin.aleksey@gmail.com)
