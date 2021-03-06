Historical data of LLKS
=======================

Historical data of LLKS (流量矿石). From around April 2014.

All JSON data files are generated by a bot in
[llks-monitor](https://github.com/caiguanhao/llks-monitor).
Data will be updated for around every half an hour.

There are **NO** guarantees that all these data on server are all up-to-date and
pushed here completely.

Some JSON files are too **BIG** to view online. You need to download and view
them locally.

All JSON files are pretty-printed and all date time values (UNIX timestamps)
are in UTC.

History
-------

Historical price and volume data.

```
Timestamp  / Price / Volume
1395306000 , 1.35  , 1295
```

Mineral
-------

Statistics of the miners and the minerals.

```
Year / M / D / Hr / Rate MB/s / This Hour / Yesterday / Today     / Total /  Difficulty / Miner Count
2014 , 4 , 2 , 13 , 66558.13  , 7809.61   , 9462.45   , 136201.31 , 12086608.06 , 29.97 , 67998
```

Miners
------

Near-real-time miner data of some LLKS accounts.

```
Timestamp  / Account / IP Address        / Rate KB/s / Yesterday / Today   / Total    / Status
1396448956 , "CGH"   , "199.***.154.228" , 1126.4    , 0         , 1.62992 , 24.88025 , "在线"
```

Log
---

* [2014-04-02] The 1MB file size problem is fixed and new feature is added to
llks-monitor, but some data were accidentally deleted, especially the miners
data on 2014-04-02.
* [2014-05-20] Web app has been moved to other server. Some data were missing
due to a wrong timezone setting of the server.

License
-------

The MIT License (MIT)

Copyright (c) 2014 Cai Guanhao (Choi Goon-ho)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
