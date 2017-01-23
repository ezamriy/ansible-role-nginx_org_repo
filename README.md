# nginx_org_repo

An Ansible role that installs nginx.org repository on EL 5/6/7 and its derivatives.


## Role Variables

Available variables and their default values are listed below:

* `nginx_org_repo_enabled: yes` - enable or disable nginx.org repository.
* `nginx_org_repo_mainline: no` - use mainline version instead of stable.


## Example Playbook

```yaml
    ---
    - hosts: all
      roles:
        - { role: ezamriy.nginx_org_repo, nginx_org_repo_enabled: no }
```

## License

MIT


## Authors

* [Eugene Zamriy](https://github.com/ezamriy)
