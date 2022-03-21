# linux-commands-cheat-sheet
- [MultiTail](https://www.tecmint.com/view-multiple-files-in-linux/) - Monitor Multiple Files Simultaneously in a Single Linux Terminal
- `yum install -y multitail1
- `multitail /var/log/apache2/error.log /var/log/apache2/error.log.1`
- `multitail -s 2 /var/log/mysqld.log /var/log/xferlog`
- `ultitail -ci green /var/log/yum.log -ci yellow -I /var/log/mysqld.log`
