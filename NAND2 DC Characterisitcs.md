### Code
``` Netlist

v1 1 0 5
vdd 4 0 5
Mp1 5 1 4 4 CMOSP L=3U W=141U
Mp2 5 1 4 4 CMOSP L=3U W=141U
Mn1 5 1 3 3 CMOSN L=3U W=47U
Mn2 3 1 0 0 CMOSN L=3U W=47U
.dc v1 0 5 0.1

.MODEL CMOSN NMOS LEVEL=2 LD=0.250000U TOX=408.000001E-10
+ NSUB=6.264661E+15 VTO=0.77527 KP=5.518000E-05 GAMMA=0.5388
+ PHI=0.6 UO=652 UEXP=0.100942 UCRIT=93790.5
+ DELTA=1.000000E-06 VMAX=100000 XJ=0.250000U LAMBDA=2.752568E-03
+ NFS=2.06E+11 NEFF=1 NSS=1.000000E+10 TPG=1.000000
+RSH=31.020000 CGDO=3.173845E-10 CGSO=3.173845E-10 +CGBO=4.260832E-10
+ CJ=1.038500E-04 MJ=0.649379 CJSW=4.743300E-10 MJSW=0.326991 PB=0.800000
.MODEL CMOSP PMOS LEVEL=2 LD=0.213695U TOX=408.000001E-10
+ NSUB=5.574486E+15 VTO=-0.77048 KP=2.226000E-05 GAMMA=0.5083
+ PHI=0.6 UO=263.253 UEXP=0.169026 UCRIT=23491.2
+ DELTA=7.31456 VMAX=17079.4 XJ=0.250000U LAMBDA=1.427309E-02
+ NFS=2.77E+11 NEFF=1.001 NSS=1.000000E+10 TPG=-1.000000
+ RSH=88.940000 CGDO=2.712940E-10 CGSO=2.712940E-10 CGBO=3.651103E-10
+ CJ=2.375000E-04 MJ=0.532556 CJSW=2.707600E-10 MJSW=0.252466 PB=0.800000
```
### Output
![image](https://github.com/userofmeet27/Netlist/assets/154442221/4137b550-2c6a-4f33-8de5-b1d1a6111b6d)

