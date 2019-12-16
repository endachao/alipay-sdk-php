# alipay-sdk-php
由于目前项目都是通过 composer 来构建第三方包，但是支付宝这个还是得手动的去导入，迫于无奈只能自己封装一个。

使用 `PSR-4` 来加载 class，所以直接命名空间使用即可

使用 `PSR-2` 加载了 `AopCertification.php`,`AopEncrypt.php`, 所以函数直接正常使用即可

只是在官方的基础上增加了 `composer`，其余的没有什么改动

# 当前版本:4.2.0  生成时间:2019-11-15 14:33:33
