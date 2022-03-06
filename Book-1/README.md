# Learn Ansible

Learning about ansible and Vagrant to try out few things

## Objective

- Install Vagrant based boxes
- Launch playbook that installs chronyd

```bash
systemctl status chronyd
● chronyd.service - NTP client/server
   Loaded: loaded (/usr/lib/systemd/system/chronyd.service; enabled; vendor preset: enabled)
   Active: active (running) since Sun 2022-03-06 08:36:23 UTC; 45min ago
     Docs: man:chronyd(8)
           man:chrony.conf(5)
  Process: 663 ExecStartPost=/usr/libexec/chrony-helper update-daemon (code=exited, status=0/SUCCESS)
  Process: 644 ExecStart=/usr/sbin/chronyd $OPTIONS (code=exited, status=0/SUCCESS)
 Main PID: 655 (chronyd)
   CGroup: /system.slice/chronyd.service
           └─655 /usr/sbin/chronyd
```