ansible-role-monit
=========

CentOSのSSH設定するAnsible Roleです。

###### `ssh_access_conf_list` 設定例


```yaml
ssh_access_conf_list:
  - name: 'acl1'
    permission: '+'
    users: 'root'
    origins: 'ALL'
```

依存関係(Dependencies)
------------

None.

ライセンス(License)
-------

MIT


