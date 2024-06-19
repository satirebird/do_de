# do_de 
Update script for do.de to set your IPv4 address and IPv6 prefix 

The script will be sheduled by systemd. 
To activate the timer, run 
```
sudo systemctl enable do_de.timer
sudo systemctl start do_de.timer
```

Licensed under GPLv3, inspired by Julian K.

https://gist.github.com/corny/7a07f5ac901844bd20c9
