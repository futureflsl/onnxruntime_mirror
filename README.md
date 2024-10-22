这个是onnxruntime官方发行的预编译包，主要是windows和linux安装包，下载前需要注意以下问题：

第一：如果您是下载GPU版本即cuda版本需要提前去https://blog.csdn.net/FL1623863129/article/details/127887083对应onnxruntime和cuda对应版本，以确保下载安装包符合自己的cuda版本

第二：
onnxruntime-win-x86表示windows x86系统使用onnxruntime C++库，您可以在x64系统使用这个32位库

onnxruntime-win-x64-gpu表示windows x64系统使用cuda版本onnxruntime C++库，不支持x86系统，cuda版本需要去查对应版本

onnxruntime-win-x64表示windows x64系统使用cpu版本onnxruntime C++库，不支持x86系统

onnxruntime-linux-x64-gpu-cuda12表示linux x64系统使用gpu版本onnxruntime C++库，只支持cuda12版本，对应cuda版本需要查询

onnxruntime-linux-x64-gpu表示linux x64系统使用gpu版本onnxruntime C++库，只支持cuda11版本，对应cuda版本需要查询

onnxruntime-linux-x64表示linux x64系统使用cpu版本onnxruntime C++库，只支持cpu推理

以下是汇总：

1、onnxruntime-1.19.2版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.19.2.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5dp">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.19.2.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5u">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.19.2.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkptx">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.19.2.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphx">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.19.2.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZp">点我下载</a></td></tr>
</tbody>
</table>
2、onnxruntime-1.19.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.19.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zy">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.19.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5t">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.19.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkptw">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.19.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphw">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.19.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59y">点我下载</a></td></tr>
</tbody>
</table>
3、onnxruntime-1.18.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.18.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zx">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-cuda12-1.18.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9p">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.18.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5s">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.18.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkptv">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-cuda12-1.18.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkplu">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.18.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphv">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.18.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59x">点我下载</a></td></tr>
</tbody>
</table>
4、onnxruntime-1.18.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.18.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zw">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-cuda12-1.18.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5y">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.18.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5r">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.18.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkptu">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-cuda12-1.18.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkplt">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.18.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphu">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.18.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59w">点我下载</a></td></tr>
</tbody>
</table>
5、onnxruntime-1.17.3版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x64-gpu-cuda12-1.17.3.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5x">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.17.3.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5q">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.17.3.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkptt">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-cuda12-1.17.3.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpls">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.17.3.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpht">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.17.3.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59v">点我下载</a></td></tr>
</tbody>
</table>
6、onnxruntime-1.17.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.17.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zv">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.17.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5p">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-cuda12-1.17.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxt">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.17.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpts">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.17.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphs">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-cuda12-1.17.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZv">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.17.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59u">点我下载</a></td></tr>
</tbody>
</table>
7、onnxruntime-1.17.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.17.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zu">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.17.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1y">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-cuda12-1.17.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxs">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.17.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkptr">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.17.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphr">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-cuda12-1.17.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZu">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.17.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59t">点我下载</a></td></tr>
</tbody>
</table>
8、onnxruntime-1.16.3版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.16.3.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zt">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.16.3.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1x">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.16.3.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkptq">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.16.3.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphq">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.16.3.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59s">点我下载</a></td></tr>
</tbody>
</table>
9、onnxruntime-1.16.2版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.16.2.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zs">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.16.2.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1w">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.16.2.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkptp">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.16.2.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphp">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.16.2.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59r">点我下载</a></td></tr>
</tbody>
</table>
10、onnxruntime-1.16.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.16.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zr">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.16.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1v">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.16.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppy">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.16.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpdy">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.16.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59q">点我下载</a></td></tr>
</tbody>
</table>
11、onnxruntime-1.16.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.16.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zq">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.16.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1u">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.16.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppx">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.16.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpdx">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.16.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59p">点我下载</a></td></tr>
</tbody>
</table>
12、onnxruntime-1.15.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.15.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zp">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.15.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1t">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.15.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppw">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.15.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpdw">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.15.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55y">点我下载</a></td></tr>
</tbody>
</table>
13、onnxruntime-1.15.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.15.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9y">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.15.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1s">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.15.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppv">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.15.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpdv">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.15.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55x">点我下载</a></td></tr>
</tbody>
</table>
14、onnxruntime-1.14.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.14.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9x">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.14.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1r">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.14.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppu">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.14.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpdt">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.14.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55w">点我下载</a></td></tr>
</tbody>
</table>
15、onnxruntime-1.14.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.14.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9w">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.14.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1q">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.14.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppt">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.14.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpds">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.14.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55v">点我下载</a></td></tr>
</tbody>
</table>
16、onnxruntime-1.13.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.13.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9v">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.13.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1p">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.13.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpps">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.13.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpdr">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.13.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55u">点我下载</a></td></tr>
</tbody>
</table>
17、onnxruntime-1.12.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.12.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9u">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.12.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxy">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.12.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppr">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.12.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpdq">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.12.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55t">点我下载</a></td></tr>
</tbody>
</table>
18、onnxruntime-1.12.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.12.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9t">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.12.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxx">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.12.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppq">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.12.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpdp">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.12.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55s">点我下载</a></td></tr>
</tbody>
</table>
19、onnxruntime-1.11.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.11.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9s">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.11.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxw">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.11.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppp">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.11.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZy">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.11.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55r">点我下载</a></td></tr>
</tbody>
</table>
20、onnxruntime-1.11.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.11.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9r">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.11.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxv">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.11.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkply">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.11.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZx">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.11.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55q">点我下载</a></td></tr>
</tbody>
</table>
21、onnxruntime-1.10.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.10.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9q">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.10.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxu">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.10.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkplx">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.10.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZw">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.10.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55p">点我下载</a></td></tr>
</tbody>
</table>
22、onnxruntime-1.9.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.9.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5dt">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.9.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5w">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.9.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxr">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.9.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkplr">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.9.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZt">点我下载</a></td></tr>
</tbody>
</table>
23、onnxruntime-1.8.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.8.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5ds">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.8.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxq">点我下载</a></td></tr>
<tr><td>onnxruntime-win-gpu-x64-1.8.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkplw">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.8.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkplq">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.8.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZs">点我下载</a></td></tr>
</tbody>
</table>
24、onnxruntime-1.7.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.7.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5dr">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.7.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxp">点我下载</a></td></tr>
<tr><td>onnxruntime-win-gpu-x64-1.7.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkplv">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.7.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkplp">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.7.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZr">点我下载</a></td></tr>
</tbody>
</table>
25、onnxruntime-1.6.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.6.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5dq">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.6.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5v">点我下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.6.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpty">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.6.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphy">点我下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.6.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZq">点我下载</a></td></tr>
</tbody>
</table>

