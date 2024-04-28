# nacos_des
A nacos background configuration file decryption program

This tool is used to decrypt the configuration file when it is encrypted when we enter the nacos background. Currently, it only supports the default algorithm. If the current algorithm cannot be decrypted, please contact the author for a version upgrade.

### 中文简介

一个nacos后台配置文件解密程序

这个工具是用来解密当我们进入nacos后台时配置文件被加密的。目前仅支持默认算法。如果当前算法无法解密，请联系作者进行版本升级。

### usage

The key is obtained by searching the password field in jasypt:encryptor:. The ciphertext is the ciphertext we want to obtain. The decryption method is obtained by searching the algorithm. If it is empty, it is the default method. Currently, only the default method is supported. If other Please add the method in time.

### 食用方法

密钥是通过搜索 jasypt:cryptor: 中的密码字段获得的。密文就是我们想要得到的密文。通过搜索算法得到解密方法。如果为空，则为默认方法。目前仅支持默认方式。如有其他请及时添加方法。

<img width="800" alt="image" src="https://github.com/fliggyaa/nacos_des/assets/82925172/4312a596-fc67-43ac-b0e1-b0c09249b8de">

## 仅供技术研究使用，请勿用于非法用途，否则后果作者概不负责

## This is for technical research only, please do not use it for illegal purposes, otherwise the author will not be responsible for the consequences.
