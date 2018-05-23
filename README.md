# metrics-antminer
Bash scripts for Antminer's Metrics.

Capturing your Antminer metrics. So you know what's going on.

### Contents

* Supported miners
* Usage

### Supported miners

* S9
* L3+
* D3
* A3
* B3

### Usage

Tested on Ubuntu 16.04.

Script : check_antminer_alive

S9 miner
```
root@monitor:/usr/lib/nagios/plugins# ./check_antminer_alive -H 192.168.50.147 -p 4028
Port 4028 is opened on 192.168.50.147
```
Script : check_antminer_avg_hashrate

S9 miner
```
root@monitor:/usr/lib/nagios/plugins# ./check_antminer_avg_hashrate -H 192.168.50.147 -w 11500 -c 11000
HASHRATE OK:  13602
```

