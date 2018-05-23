# metrics-antminer
Bash scripts for Antminer's Metrics.

Capturing your Antminer metrics. So you know what's going on.

## Contents

* Script: check_antminer_alive
* Script: check_antminer_avg_hashrate

## check_antminer_alive

Tested miners
* S9
* L3+
* D3
* A3
* B3

Tested host: Ubuntu 16.04

Usage example with S9

```
root@monitor:/usr/lib/nagios/plugins# ./check_antminer_alive -H 192.168.50.147 -p 4028
Port 4028 is opened on 192.168.50.147
```
## check_antminer_avg_hashrate

Tested miners
* S9
* L3+
* D3
* A3
* B3

Tested host: Ubuntu 16.04

Usage example with S9

```
root@monitor:/usr/lib/nagios/plugins# ./check_antminer_avg_hashrate -H 192.168.50.147 -w 11500 -c 11000
HASHRATE OK:  13602
```

