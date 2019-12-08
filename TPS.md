### TPS Competition Questionnaire

*Please replace the square brackets and the text in it with your answers*

**Number of CPUs**

[cluster1->64cpu     cluster2->64cpu   cluster3->64cpu ]

**Memory (GB)**

[ 384G.]

**Storage (GB)**

[ SSD 150G.]

**Network**

[8 Gbps LAN]

**Machine Type (Optional)**

[S3.16XLARGE128（标准型S3，64核128GB） 腾讯云]

**Command Lines for Running Cluster**
```
[Copy the command line here]
```

**Peak TPS**

[23799.00    22314.00]

**Video URL**

[URL for the video showing how you produced the above TPS. Also, the submitted video should include stats of the observations of at least two clusters’ peak TPS.]

**Output From `stats` Tool (Highest TPS)**
```
[============================
QuarkChain Cluster Stats
============================
CPU:                64
Memory:             125 GB
IP:                 172.22.0.16
Chains:             128
Network Id:         3
Peers:              172.22.0.7:38291
============================
Timestamp               Syncing TPS     Pend.TX Conf.TX BPS     SBPS    CPU     ROOT
2019-12-08 10:07:48     true    19284.00        110695  656420  72.15   25.68   100.00  13
2019-12-08 10:07:58     false   16656.00        123419  809135  70.72   24.63   42.17   13
2019-12-08 10:08:08     false   21849.00        68773   912995  69.63   24.25   13.40   13
2019-12-08 10:08:18     false   23799.00        26472   952000  67.95   24.00   3.31    13
2019-12-08 10:08:28     false   23799.00        20258   952000  67.05   23.85   14.68   14
2019-12-08 10:08:38     false   19755.00        32075   954285  67.68   23.80   31.81   14
^Csignal: interrupt]
```
**Output From `stats` Tool (Second highest TPS)**
```
[QuarkChain Cluster Stats
============================
CPU:                64
Memory:             125 GB
IP:                 172.22.0.7
Chains:             128
Network Id:         3
Peers:              172.22.0.16:34276
============================
Timestamp               Syncing TPS     Pend.TX Conf.TX BPS     SBPS    CPU     ROOT
2019-12-08 10:04:53     false   0.00    0       0       75.52   59.87   1.82    6
2019-12-08 10:05:03     false   0.00    0       0       76.28   61.65   2.92    6
2019-12-08 10:05:13     false   0.00    0       0       76.63   57.43   2.62    7
2019-12-08 10:05:23     false   0.00    0       0       74.35   52.38   0.16    7
2019-12-08 10:05:33     false   0.00    0       0       72.65   50.98   100.00  8
2019-12-08 10:05:43     false   0.00    0       0       69.50   54.40   100.00  8
2019-12-08 10:05:53     false   0.00    0       0       67.33   57.58   100.00  9
2019-12-08 10:06:03     false   0.00    7       0       65.25   55.93   100.00  9
2019-12-08 10:06:13     false   342.00  174290  6855    62.75   52.00   99.97   10
2019-12-08 10:06:23     false   2628.00 400716  52560   62.03   48.25   100.00  10
2019-12-08 10:06:33     false   4278.00 430555  85565   61.98   42.67   100.00  10
2019-12-08 10:06:43     false   5964.00 407904  119280  61.62   40.50   100.00  11
2019-12-08 10:06:53     false   10062.00        355160  201275  60.65   38.95   100.00  11
2019-12-08 10:07:03     false   17832.00        238559  356685  60.52   35.42   100.00  11
2019-12-08 10:07:13     false   22314.00        29715   474285  63.62   28.45   100.00  11
2019-12-08 10:07:23     false   19899.00        35016   476000  66.18   25.97   100.00  11
2019-12-08 10:07:33     false   17598.00        173812  478285  68.48   25.40   100.00  12
^Csignal: interrupt]
```

**Cluster Configurations**
[https://github.com/jienidada/goquarkchain/blob/master/tests/loadtest/deployer/deployConfig.json
]

**Additional Comment**

[If you have special setup, e.g., running a single cluster over multiple machines, the above questionnaire might not fit. Note down
whatever you want us to know here to help evaluate the result.]
