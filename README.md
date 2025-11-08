这个是onnxruntime官方发行的预编译包，主要是windows和linux安装包，下载前需要注意以下问题：

第一：如果您是下载GPU版本即cuda版本需要提前去https://blog.csdn.net/FL1623863129/article/details/127887083
对应onnxruntime和cuda对应版本，以确保下载安装包符合自己的cuda版本

第二：
onnxruntime-win-x86表示windows x86系统使用onnxruntime C++库，您可以在x64系统使用这个32位库
onnxruntime-win-x64-gpu表示windows x64系统使用cuda版本onnxruntime C++库，不支持x86系统，cuda版本需要去查对应版本
onnxruntime-win-x64表示windows x64系统使用cpu版本onnxruntime C++库，不支持x86系统
onnxruntime-linux-x64-gpu-cuda12表示linux x64系统使用gpu版本onnxruntime C++库，只支持cuda12版本，对应cuda版本需要查询
onnxruntime-linux-x64-gpu表示linux x64系统使用gpu版本onnxruntime C++库，对应cuda版本需要查询
onnxruntime-linux-x64表示linux x64系统使用cpu版本onnxruntime C++库，只支持cpu推理
以下是汇总： <br>
onnxruntime-1.23.2版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x64-gpu-1.23.2.7z</td><td><a href="https://mbd.pub/o/bread/YZWYmpxwag==">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.23.2.zip</td><td><a href="https://mbd.pub/o/bread/YZWYmpxwbQ==">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.23.2.tgz</td><td><a href="https://mbd.pub/o/bread/YZWYmpxwZw==">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.23.2.tgz</td><td><a href="https://mbd.pub/o/bread/YZWYmpxxZg==">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.23.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x64-gpu-1.23.1.7z</td><td><a href="https://mbd.pub/o/bread/YZWYmpxwaQ==">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.23.1.zip</td><td><a href="https://mbd.pub/o/bread/YZWYmpxwbA==">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.23.1.tgz</td><td><a href="https://mbd.pub/o/bread/YZWYmpxwZg==">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.23.1.tgz</td><td><a href="https://mbd.pub/o/bread/YZWYmpxxZQ==">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.23.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x64-gpu-1.23.0.7z</td><td><a href="https://mbd.pub/o/bread/YZWYmpxwaA==">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.23.0.zip</td><td><a href="https://mbd.pub/o/bread/YZWYmpxwaw==">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.23.0.tgz</td><td><a href="https://mbd.pub/o/bread/YZWYmpxxZw==">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.23.0.tgz</td><td><a href="https://mbd.pub/o/bread/YZWYmpxxZA==">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.22.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.22.1.zip</td><td><a href="https://mbd.pub/o/bread/YZWVl5dwaw==">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.22.1.zip</td><td><a href="https://mbd.pub/o/bread/YZWVl5dwag==">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.22.1.zip</td><td><a href="https://mbd.pub/o/bread/YZWVl5dwaQ==">下载</a></td></tr>
</tbody>
</table>


onnxruntime-1.22.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.22.0.zip</td><td><a href="https://mbd.pub/o/bread/YZWUkplybA==">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.22.0.zip</td><td><a href="https://mbd.pub/o/bread/YZWUkplyag==">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.22.0.zip</td><td><a href="https://mbd.pub/o/bread/YZWUkplyaA==">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.22.0.tgz</td><td><a href="https://mbd.pub/o/bread/YZWUkplyZg==">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.22.0.tgz</td><td><a href="https://mbd.pub/o/bread/YZWUkpppZA==">下载</a></td></tr>
</tbody>
</table>

onnxruntime-1.21.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-linux-x64-gpu-1.21.1.tgz</td><td><a href="https://mbd.pub/o/bread/YZWUkpppZg==">下载</a></td></tr>
</tbody>
</table>

onnxruntime-1.21.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.21.0.zip</td><td><a href="https://mbd.pub/o/bread/YZWUkplyaw==">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.21.0.zip</td><td><a href="https://mbd.pub/o/bread/YZWUkplyaQ==">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.21.0.zip</td><td><a href="https://mbd.pub/o/bread/YZWUkplyZw==">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.21.0.tgz</td><td><a href="https://mbd.pub/o/bread/YZWUkpppZQ==">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.21.0.tgz</td><td><a href="https://mbd.pub/o/bread/YZWUkplybQ==">下载</a></td></tr>
</tbody>
</table>

onnxruntime-1.20.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.20.1.zip</td><td><a href="https://mbd.pub/o/bread/Z52Uk5py">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.20.1.7z</td><td><a href="https://mbd.pub/o/bread/Z52Uk5pw">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.20.1.zip</td><td><a href="https://mbd.pub/o/bread/Z52Uk5pu">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.20.1.tgz</td><td><a href="https://mbd.pub/o/bread/Z52Uk5ps">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.20.1.tgz</td><td><a href="https://mbd.pub/o/bread/Z52Uk5pq">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.20.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.20.0.zip</td><td><a href="https://mbd.pub/o/bread/Z52Uk5px">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.20.0.7z</td><td><a href="https://mbd.pub/o/bread/Z52Uk5pv">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.20.0.zip</td><td><a href="https://mbd.pub/o/bread/Z52Uk5pt">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.20.0.tgz</td><td><a href="https://mbd.pub/o/bread/Z52Uk5pr">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.20.0.tgz</td><td><a href="https://mbd.pub/o/bread/Z52Uk5pp">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.19.2版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.19.2.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5dp">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.19.2.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5u">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.19.2.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkptx">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.19.2.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphx">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.19.2.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZp">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.19.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.19.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zy">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.19.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5t">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.19.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkptw">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.19.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphw">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.19.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59y">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.18.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.18.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zx">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-cuda12-1.18.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9p">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.18.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5s">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.18.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkptv">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-cuda12-1.18.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkplu">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.18.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphv">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.18.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59x">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.18.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.18.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zw">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-cuda12-1.18.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5y">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.18.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5r">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.18.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkptu">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-cuda12-1.18.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkplt">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.18.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphu">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.18.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59w">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.17.3版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x64-gpu-cuda12-1.17.3.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5x">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.17.3.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5q">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.17.3.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkptt">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-cuda12-1.17.3.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpls">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.17.3.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpht">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.17.3.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59v">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.17.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.17.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zv">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.17.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5p">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-cuda12-1.17.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxt">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.17.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpts">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.17.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphs">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-cuda12-1.17.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZv">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.17.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59u">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.17.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.17.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zu">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.17.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1y">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-cuda12-1.17.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxs">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.17.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkptr">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.17.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphr">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-cuda12-1.17.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZu">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.17.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59t">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.16.3版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.16.3.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zt">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.16.3.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1x">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.16.3.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkptq">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.16.3.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphq">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.16.3.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59s">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.16.2版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.16.2.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zs">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.16.2.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1w">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.16.2.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkptp">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.16.2.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphp">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.16.2.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59r">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.16.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.16.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zr">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.16.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1v">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.16.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppy">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.16.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpdy">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.16.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59q">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.16.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.16.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zq">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.16.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1u">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.16.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppx">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.16.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpdx">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.16.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm59p">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.15.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.15.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5Zp">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.15.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1t">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.15.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppw">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.15.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpdw">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.15.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55y">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.15.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.15.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9y">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.15.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1s">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.15.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppv">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.15.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpdv">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.15.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55x">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.14.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.14.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9x">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.14.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1r">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.14.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppu">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.14.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpdt">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.14.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55w">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.14.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.14.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9w">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.14.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1q">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.14.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppt">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.14.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpds">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.14.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55v">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.13.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.13.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9v">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.13.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp1p">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.13.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpps">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.13.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpdr">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.13.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55u">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.12.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.12.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9u">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.12.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxy">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.12.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppr">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.12.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpdq">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.12.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55t">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.12.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.12.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9t">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.12.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxx">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.12.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppq">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.12.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpdp">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.12.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55s">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.11.1版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.11.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9s">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.11.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxw">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.11.1.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkppp">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.11.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZy">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.11.1.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55r">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.11.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.11.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9r">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.11.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxv">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.11.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkply">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.11.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZx">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.11.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55q">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.10.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.10.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp9q">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.10.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxu">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.10.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkplx">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.10.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZw">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.10.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Wm55p">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.9.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.9.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5dt">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.9.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5w">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.9.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxr">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.9.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkplr">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.9.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZt">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.8.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.8.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5ds">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.8.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxq">下载</a></td></tr>
<tr><td>onnxruntime-win-gpu-x64-1.8.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkplw">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.8.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkplq">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.8.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZs">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.7.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.7.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5dr">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.7.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpxp">下载</a></td></tr>
<tr><td>onnxruntime-win-gpu-x64-1.7.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkplv">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.7.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkplp">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.7.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZr">下载</a></td></tr>
</tbody>
</table>
onnxruntime-1.6.0版本下载列表:
<table>
<thead><tr><th>版本名称</th><th>下载地址</th></tr></thead>
<tbody>
<tr><td>onnxruntime-win-x86-1.6.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xk5dq">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-gpu-1.6.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkp5v">下载</a></td></tr>
<tr><td>onnxruntime-win-x64-1.6.0.zip</td><td><a href="https://mbd.pub/o/bread/Zp2Xkpty">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-gpu-1.6.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2Xkphy">下载</a></td></tr>
<tr><td>onnxruntime-linux-x64-1.6.0.tgz</td><td><a href="https://mbd.pub/o/bread/Zp2XkpZq">下载</a></td></tr>
</tbody>
</table>

