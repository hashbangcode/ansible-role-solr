# Ansible Role: Solr

An Ansible role that installs [Solr](http://tomcat.apache.org/) onto a Tomcat server on RHEL/CentOS and Debian/Ubuntu.


## Requirements

None.


## Role Variables

drupal_solr_package: "search_api_solr"
default_collection_name: "vlad"


## Dependencies

[Tomcat](https://github.com/hashbangcode/ansible-role-tomcat).


## Example Playbook

```
- hosts: servers
  roles:
     - { role: hashbangcode.tomcat }
     - { role: hashbangcode.solr }
```

## License

MIT


## Author Information

This role was created by [Phil Norton](http://www.hashbangcode.com) originally for use with [Vlad](https://github.com/hashbangcode/vlad).
