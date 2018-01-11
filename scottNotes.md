## 2018-01-11
### Results
```
14:53 $ ./benchmark.sh
CPUs/Cores: 8
GOMAXPROCS: 8
find /Users/scottschmidt
find: /Users/scottschmidt/Library/Saved Application State/com.airvpn.client.savedState: Permission denied
 4133270

real    4m57.077s
user    0m4.766s
sys     1m32.543s
./recursive /Users/scottschmidt
 4132861

real    10m36.331s
user    0m22.862s
sys     3m31.862s
./parallel /Users/scottschmidt
 4132880

real    4m26.926s
user    1m20.410s
sys     7m25.234s
./walk /Users/scottschmidt
2018/01/11 15:23:23 open /Users/scottschmidt/Library/Saved Application State/com.airvpn.client.savedState: permission denied
 3068230

real    9m40.697s
user    0m22.632s
sys     3m10.911s
You have new mail in /var/mail/scottschmidt
(tkcml) ✔ ~/ScottDev/golang-parallel-io [ssdev|…8]
15:23 $
```