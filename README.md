Hello every one if any one facing issue to login via ssh. 
using latest parrotos or kali linux use this simple steps to clear these issues.
Check out resolv

open this file /etc/ssh/ssh_config

add this 2 line in 20  line 

PubkeyAcceptedKeyTypes +ssh-dss
HostKeyAlgorithms +ssh-dss

open this file /etc/ssh/sshd_config

add this 2 line in 12  line 

PubkeyAcceptedKeyTypes +ssh-dss
HostKeyAlgorithms +ssh-dss
          or 

use this cmd
ssh -oHostKeyAlgorithms=+ssh-dss username@IP





One more issue for Hydra 

Hydra Brute Force Fix Issue

useage:-
```
step 1 - clone this repo.
step 2 - copy the contents of this file 'ssh_config'
step 4 - paste and replace this copied content into a file at /etc/ssh/ssh_config
step 5 - done :)
```
