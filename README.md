# wechat_chat_analytics

This repo's target audiences are Wechat users. Currently, the decryption of Wechat databases is written only in Chinese. English version is one of the issues to solve.

## 如何导出微信数据库 (How to export and decrypt wechat database)

### 第一步：用Bluestacks把EnMicroMsg.db复制出来(Step 1: Copy EnMicroMsg.db out using Android VM on your computer)
可以参考[这个网页](https://www.jianshu.com/p/3065087ea1b0)，我和这个教程不同的地方在于我用的Bluestacks没有开启root权限这么神奇的功能，所以我在Bluestacks上使用了BSTweaker修改root权限。而且第二个和它不同的地方我必须给钱买了一个root file explorer才能把EnMicroMsg.db复制出来。这个我有时间再写个详细教程吧。

### 第二步：用sqlcipher新版本（3.x, 默认不向下兼容!!!!)破解数据库(Step 2: Use sqlcipher to decrypt EnMicroMsg.db)
具体请参考[这个网页](https://www.sy2k.com/2018/%E5%BE%AE%E4%BF%A1%E6%95%B0%E6%8D%AE%E5%BA%93%E5%AF%BC%E5%87%BA%E5%B9%B6%E7%A0%B4%E8%A7%A3/)，这个教程最详细、最实用，里面包含了sqlcipher的文件。不熟悉cmd的人可能会用得别扭一点，但是跟着这个教程一一输入就好了。
