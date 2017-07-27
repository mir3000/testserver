总结一下 bench.sh 特点：
1、显示当前测试的各种系统信息；
2、取自世界多处的知名数据中心的测试点，下载测试比较全面；
3、支持 IPv6 下载测速；
4、IO 测试三次，并显示平均值。


再配合 unixbench.sh 脚本测试，即可全面测试 VPS 的性能。

使用方法：

命令：

wget -qO- https://raw.githubusercontent.com/mir3000/testserver/bench.sh | bash
或者

curl -so- https://raw.githubusercontent.com/mir3000/testserver/bench.sh | bash
