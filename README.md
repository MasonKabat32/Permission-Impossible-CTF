# Permission Impossible CTF Challenge

**Difficulty**: Moderate

**Categories**: Buffer Overflow, Shell Commands, Privilege Escalation

## Description
Welcome to the Permission Impossible CTF challenge! Your mission is to perform a privilege escalation exploit to gain root access on a Linux virtual machine and retrieve the flag file located in the home directory, titled flag.txt.

However to connect to the virtual machine, you’ll need its IP address and password but they’ve been stolen by a ravenous monster! The monster isn’t giving them up easily. To earn its cooperation, you’ll have to prepare a delicious meal for it. Only then might it reveal the connection details.

To get started:

1. Download the provided executable, which will help you prepare the perfect meal for the monster.

2. Convince the monster to reveal the IP and password. Be warned, I’ve tried countless times, following its instructions to the letter, but it’s never satisfied!

3. Once you successfully obtain the connection details, you can connect to the virtual machine and begin the main task, escalating your privileges to root and finding the flag.

Good luck, and happy hunting!

## Hints

1. When running the executable, the monster may provide some valuable information

2. The monster told me its favorite meal is letter soup

3. The sudo permissions for the account will be hidden in a folder somewhere in the home directory of the player account in a file named “config.txt”

4. To switch to the root directory an, account with root access will have to be used

5. The range of unsigned integers is from 0 to 4294967295

6. Some helpful shell commands you may want to use include ls, cd, sudo, find, cat, su, more, less, grep
