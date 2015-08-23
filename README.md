# gfwlist2pac

fork from clowwindy's gfwlist2pac

usage:


```
python main.py -i gfwlist.txt -f ss.pac -p 192.168.1.17:1080 --user-rule myrule --precise
```

```
pip install gfwlist2pac

   usage: gfwlist2pac [-h] [-i GFWLIST] -f PAC -p PROXY [--user-rule USER_RULE]
                  [--precise]

   optional arguments:
     -h, --help            show this help message and exit
     -i GFWLIST, --input GFWLIST
                           path to gfwlist
     -f PAC, --file PAC    path to output pac
     -p PROXY, --proxy PROXY
                           the proxy parameter in the pac file, for example,
                           "SOCKS5 127.0.0.1:1080;"
     --user-rule USER_RULE
                           user rule file, which will be appended to gfwlist
     --precise             use adblock plus algorithm instead of O(1) lookup

```
