# Ansible Collection - gcslaoli.cloud

Documentation for the collection.

## playbooks

获取主机信息

```bash
ansible-playbook gcslaoli.cloud.info.yml
# 限制主机 ubuntu-amd64
ansible-playbook gcslaoli.cloud.info.yml -l ubuntu-amd64
```

测试脚本

```bash
ansible-playbook gcslaoli.cloud.test.yml
```
