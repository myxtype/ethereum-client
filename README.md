# ethereum-client
ethereum rpc client, offline sign, php

PHP版的以太坊RPC客户端，支持离线交易、生成私钥与地址。你不用专门购买一台服务器来运行以太坊客户端。

你可以使用以太坊公共节点，比如：https://infura.io 你可以将你用户的私钥加密存储在数据库中，使用的时候取出解密，直接发送交易。

这样不仅高效率且安全（如果你执意要使用服务器来运行以太坊客户端，这个项目也支持）。

# 安装
加入代码到您的composer.json文件
```
{
    "require": {
        "myxtype/ethereum-client": "dev-master"
    }
}
```
> 或者 `composer require myxtype/ethereum-client`

然后`composer update`即可。

# 使用
详细使用请参考`examples`文件夹

你可以在这里：https://infura.io/docs 看到更多可使用的RPC方法。
