# Unbound-in-a-Box
A [shipit](https://github.com/padthaitofuhot/shipit)-ized OpenNTPD container for whatever needs doing.

# How?
```
$ git clone https://github.com/padthaitofuhot/unbound-in-a-box
$ cd openntpd-in-a-box
$ sudo ./shipit.sh
```

# What's in the box?
* The OpenNTPD NTP server
* Sane vanilla-ish default configuration:
    * Uses pool.ntpd.org for time
    * Uses google.com for drift and MitM attack constraint
* Plays well with other in-a-box containers
