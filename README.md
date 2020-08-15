# SSH

### Problem:

  VSCode/Pycharm SFPT upload error
  
    [error] Error: Unable to start subsystem: sftp

### Solution:

```shell
cp PATH/sshd_config /etc/ssh/sshd_config

/etc/init.d/ssh start
/etc/init.d/ssh restart
/etc/init.d/ssh start
'''
