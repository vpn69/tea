<h1>租用Vultr VPS图文教程</h1>

租用VPS用来翻墙，基本原则：国外的VPS服务商；在世界上已经被广泛使用，名气比较大的，口碑好的，没有出现安全问题的；可自主更换IP或机房，这对建立VPN和代理服务器至关重要；付款方便，最好是支持支付宝、paypal付款的。首选国际知名的vultr，速度不错、稳定且性价比高，按小时计费，能够随时开通和删除服务器，新服务器即是新ip。可以用支付宝付款。

<b>广告插播，如果你觉得自己折腾VPS太麻烦，可以考虑这个服务哦（非本库服务）：</b><br>
<a href="https://github.com/killgcd/justmysocks/blob/master/README.md"><img src="https://raw.githubusercontent.com/killgcd/justmysocks/master/images/bwgss.jpg" alt="搬瓦工翻墙 Just My Socks"></a>

Vultr注册地址：https://www.vultr.com/?ref=8762855-6G
（新用户通过此活动链接注册，可获赠100美元，有效期1个月，为了获得100美元赠送必须绑定信用卡或Paypal。Vultr 云主机在全球15个数据中心可选，KVM框架，最低2.5美元/月。）如果以后这个vultr注册地址被墙了，那么就用<a href="https://github.com/bannedbook/fanqiang/wiki/Chrome%E4%B8%80%E9%94%AE%E7%BF%BB%E5%A2%99%E5%8C%85">翻墙软件</a>打开，或者用[ss/ssr免费账号](https://github.com/bannedbook/fanqiang/wiki/%E5%85%8D%E8%B4%B9ss%E8%B4%A6%E5%8F%B7)

<a href="https://www.vultr.com/?ref=8762855-6G"><img src="https://www.vultr.com/media/banner_2.png" width="468" height="60"></a>

虽然是英文界面，但是现在的浏览器都有网页翻译功能，鼠标点击右键，选择网页翻译即可翻译成中文。

注册并邮件激活账号，充值10美元后即可购买服务器。充值方式是支付宝或paypal，使用paypal有银行卡（包括信用卡）即可。paypal注册地址：https://www.paypal.com （paypal是国际知名的第三方支付服务商，注册一下账号，绑定银行卡即可购买国外商品）

|价格 | CPU | 内存| SSD硬盘 | 带宽 |  流量/月  | 备注   
|---------- | --- | ---| --- | --- |  ---  | --- 
|2.5美元/月 | 单核 | 512M| 10G | 1Gbps |  500G  | (**仅提供ipv6 ip**)
|3.5美元/月 | 单核 | 512M| 10G | 1Gbps |  500G  |  (**推荐**) 
|5美元/月 |   单核 | 1G  | 25G | 1Gbps |  1000G |  (**推荐**)  
|10美元/月 |  单核 | 2G  | 55G | 1Gbps |  2000G | 
|20美元/月 |  2cpu | 4G  |80G  | 1Gbps |  3000G | 
|40美元/月 |  4cpu | 8G  |160G | 1Gbps |  4000G |
|80美元/月 |  6cpu | 16G |320G |1Gbps  |5000G   | (**获赠送100美元可玩这个**) 

**注意：2.5美元套餐只提供ipv6，如果你用不了ipv6，那么你可以买3.5美元的套餐。另外，并非所有地区都有3.5美元的套餐，需要自己去看。由于资源的短缺，有的地区有时候有3.5美元的套餐，有时候没有，一般5美元的每个机房都有保障，也可以用5美元的。不过，用我们的[推荐链接](https://www.vultr.com/?ref=8762855-6G)注册，马上赠送100美元哦，看看如果100美元到帐的话，也可以搞个大服务器玩一下，虽然带宽都是1G，但大服务器性能好，应该会稍快一些。因为100美元有效期只有一个月，不用的话，30天后反正也就没了，所以不如先玩个大的，切记切记快到一个月时记得删除服务器，再换成小的即可。**

**重要的话重复一遍，如果用赠送金额搞了大服务器，切记切记快到一个月时记得删除服务器，再换成小的即可，如果你豪气，不在乎这点钱，也可以忽略这句话哦。**

vultr实际上是折算成小时来计费的，比如服务器是5美元1个月，那么每小时收费为5/30/24=0.0069美元 会自动从账号中扣费，只要保证账号有钱即可。如果你部署的服务器实测后速度不理想，你可以把它删掉（destroy），重新换个地区的服务器来部署，方便且实用。因为新的服务器就是新的ip，所以当ip被墙时这个方法很有用。当ip被墙时，为了保证新开的服务器ip和原先的ip不一样，先开新服务器，开好后再删除旧服务器即可。在账号的Billing选项里可以看到账户余额。

**账号充值如图**：

![](https://raw.githubusercontent.com/vpn69/tea/main/2021-01-05_205033.png)

![](https://raw.githubusercontent.com/vpn69/tea/main/2021-01-05_204934.png)

**开通服务器步骤如图**

![](https://raw.githubusercontent.com/Alvin9999/pac2/master/vultr/vultr1.PNG)

服务器位置首选美国西海岸的 Los Angeles、或者亚洲的东京、新加坡，当然其它国家地区都可以尝试。建议在[Vultr测速网站](https://sgp-ping.vultr.com/?ref=8762850)选择各个不同的Server Location下载测试一下，然后再根据测试情况选择。 要在自己电脑上 ping 那个ip ，不要在网页上直接ping，ping 的时候，看每一行 里 time ，越小越好；还可以下载那个100m的文件测试数据传输速度。

![](https://raw.githubusercontent.com/Alvin9999/pac2/master/vultr/vultr2.PNG)

**vps操作系统选择**

**vps操作系统这里选择Debian 10 x 64**

![](https://raw.githubusercontent.com/bannedbook/fanqiang/master/v2ss/images/vps/vultr-debian.jpg)


![](https://raw.githubusercontent.com/Alvin9999/pac2/master/vultr/vultr5.PNG)

![](https://raw.githubusercontent.com/vpn69/tea/main/2021-01-06_201644.png)

![](https://raw.githubusercontent.com/vpn69/tea/main/2021-01-06_194708.png)

**开通服务器时，当出现了ip，不要立马去ping或者用SSH去连接，再等5分钟之后，有个系统安装启动的时间。完成购买后，找到系统的密码记下来，部署服务器时需要用到。vps系统的密码获取方法如下图：**

![](https://raw.githubusercontent.com/vpn69/tea/main/2021-01-05_224721.png)

![](https://raw.githubusercontent.com/vpn69/tea/main/2021-01-05_224814.png)

**如果需要删掉服务器时，参考下图**：

删除服务器时，先开新的服务器后再删除旧服务器，这样可以保证新服务器的ip与旧ip不同。

![](https://raw.githubusercontent.com/vpn69/tea/main/2021-01-06_203143.png)

![](https://raw.githubusercontent.com/bannedbook/fanqiang/master/v2ss/images/ss/de2.PNG)

![](https://raw.githubusercontent.com/bannedbook/fanqiang/master/v2ss/images/ss/de5.png)

一个被墙ip的vps被删掉后，其ip并不会消失，会随机分配给下一个在这个数据中心新建服务器的人，这就是为什么开新服务器会有一定几率开到被墙的ip。被墙是指在IP地址被中共防火墙屏蔽，在中国大陆无法连接这个IP，但在国外是可以连通的，vultr是面向全球服务，如果这个被墙ip被国外的人开到了，它是可以被正常使用的，一般一段时间后就会被解封，那么这就是一个良性循环。

本文属于bannedbook系列翻墙教程的一部分，欢迎体验我们提供的免费翻墙软件和教程：
<ul>
<li><a href="https://github.com/bannedbook/fanqiang/wiki/%E5%AE%89%E5%8D%93%E7%BF%BB%E5%A2%99%E8%BD%AF%E4%BB%B6">安卓手机翻墙</a></li>
 <li><a href="https://github.com/bannedbook/fanqiang/wiki/Chrome%E4%B8%80%E9%94%AE%E7%BF%BB%E5%A2%99%E5%8C%85" >Chrome一键翻墙包</a></li>
 <li><a href="https://github.com/bannedbook/fanqiang/wiki/%E7%81%AB%E7%8B%90firefox%E4%B8%80%E9%94%AE%E7%BF%BB%E5%A2%99%E5%8C%85" >火狐firefox一键翻墙包</a></li>
 <li><a href="https://github.com/bannedbook/xxjw" >XX-Net禁闻版</a></li>
 <li><a href="https://github.com/bannedbook/fanqiang/blob/master/v2ss/%E8%87%AA%E5%BB%BAV2ray%E6%9C%8D%E5%8A%A1%E5%99%A8%E7%AE%80%E6%98%8E%E6%95%99%E7%A8%8B.md" >自建V2ray服务器简明教程</a></li>
</ul>

***

本教程改编修订自自 [Alvin9999的文章](https://github.com/Alvin9999/new-pac/wiki/%E8%87%AA%E5%BB%BAv2ray%E6%9C%8D%E5%8A%A1%E5%99%A8%E6%95%99%E7%A8%8B) ,感谢Alvin9999朋友。

版权所有，转载必须保留文章所有链接。

