# Permission Impossible CTF Challenge

**Difficulty**: Moderate

**Categories**: Shell Commands, Priveledge Escalation

## Description
Welcome to the Permission Impossible CTF challenge! The goal of this challenge is to perform a priveledege escalation exploit to gain access to the root account on the Linux virtual machine to find the flag file in the home directory titled "flag.txt". To begin this challenge, you first have to connect to the virtual machine using ssh with the following command.

```bash
ssh Player@158.101.112.73
```

You then will be prompted for a Player account password before you are connected to the machine. The password for the account is.

```bash
Exploit123@
```

Once the password has been entered and are connected, you can begin the challenge. The following Hints section will contain valuable information in order to successfully perform the exploit and capture the flag. Good luck and happy hunting!

## Hints

1. The sudo permissions for the account will be hidden in a folder somewhere in the home directory of the player account in a file named “config.txt”

2. To switch to the root directory an, account with root access will have to be used

3. The range of unsigned integers is from 0 to 4294967295

4. Some helpful shell commands you may want to use include ls, cd, sudo, find, cat, su, more, less, grep
