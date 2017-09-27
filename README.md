# Terminal Commands

## Find & Scan Wireless Networks from the Command Line in Mac OS X

1. Making a symbolic link for airport tool

`$ sudo ln -s /System/Library/PrivateFrameworks/Apple80211.framework/Versions/Current/Resources/airport /usr/local/bin/airport`

2. Scan for and find all wireless networks within range

`$ airport -s`

## Traceroute
displaying the path and measuring transit delays of packets across an Internet Protocol (IP) 

`$ traceroute www.google.com`

---

## Built-in camera macbook pro not working

`$ sudo killall VDCAssistant`

## Keep computer from sleeping
1 hour = (60 minutes/hour) × (60 seconds/minute) = 3600 seconds/hour

7200 seconds it's 2 hours

`$ caffeinate -u -t 7200`