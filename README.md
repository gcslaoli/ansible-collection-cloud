# Ansible Collection - gcslaoli.cloud

Documentation for the collection.

## playbooks

获取主机信息

```bash
ansible-playbook gcslaoli.cloud.info
```

限制主机 ubuntu-amd64

```bash
ansible-playbook gcslaoli.cloud.info -l ubuntu-amd64
```

运行脚本

```bash
ansible-playbook gcslaoli.cloud.init
```

执行标签为 common 的任务

```bash
ansible-playbook gcslaoli.cloud.init --tags common
```

执行标签为 firewall 的任务

```bash
ansible-playbook gcslaoli.cloud.init --tags firewall
```

执行标签为 docker 的任务

```bash
ansible-playbook gcslaoli.cloud.init --tags docker
```
