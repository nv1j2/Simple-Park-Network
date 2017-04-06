#构建中小型园区网_试验
<pre>
1、PC1和PC2均是两台服务器，网关在RT2上，实现不同服务器之间的互相通信。
2、rt2和rt3均为dhcp服务器，pc3和pc4均可以自动获得地址。
3、RT1、2、3、4、5运行ospf协议，实现内网互通。
4、rt6为运营商设备，互联地址为202.1.1.0/28的地址。
5、RT1位边界设备，用所学技术，实现内网到外网的访问。
6、内部所有的路由器都可以被互相Telnet
7、实现全网互通。
8、使用ip地址规划技术，所有的互联地址掩码均为/30
9、使用acl技术，让PC1和PC2不能够互相访问，但都能够和网关通信。
</pre>
拓扑图
https://github.com/nv1j2/Simple-Park-Network/blob/master/%E8%AF%95%E9%AA%8C%E6%8B%93%E6%89%91%E5%9B%BE.png
