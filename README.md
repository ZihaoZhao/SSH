# SSH

### Problem:

  VSCode/Pycharm SFPT upload error
  
    [error] Error: Unable to start subsystem: sftp

### Solution:

```bash
cp this_repository/sshd_config /etc/ssh/sshd_config

/etc/init.d/ssh start
/etc/init.d/ssh restart
/etc/init.d/ssh start
```
