# linux-commands-cheat-sheet
1. [MultiTail](https://www.tecmint.com/view-multiple-files-in-linux/) - Monitor Multiple Files Simultaneously in a Single Linux Terminal
- `yum install -y multitail`
- `multitail /var/log/apache2/error.log /var/log/apache2/error.log.1`
- `multitail -s 2 /var/log/mysqld.log /var/log/xferlog`
- `ultitail -ci green /var/log/yum.log -ci yellow -I /var/log/mysqld.log`
- `multitail = tail -f `

2. [tail](https://www.geeksforgeeks.org/tail-command-linux-examples/) - By default it prints the last 10 lines of the specified files
- `tail -n 3 state.txt`
- `tail -3 state.txt`
- The tail command can be piped with many other commands of the unix. In the following example output of the tail command is given as input to the sort command with -r option to sort the last 7 state names coming from file state.txt in the reverse order: `tail -n 7 state.txt // tail -n 7 state.txt | sort -r // cat state.txt | head -n 20 | tail -n 5  > list.txt`
