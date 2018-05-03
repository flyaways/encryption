# 加解密算法分类

<!-- TOC -->

- [加解密算法分类](#加解密算法分类)
    - [1 算法对比](#1-算法对比)
    - [2 对称加密](#2-对称加密)
    - [3 非对称加密](#3-非对称加密)
    - [4 散列算法](#4-散列算法)

<!-- /TOC -->

## 1 算法对比

|算法类型 | 特点 | 优势 | 缺陷 | 代表算法|应用场景|
|-| ----- | ----- | ----- | ---------|--------|
|对称加密 | 加解密密钥相同或可推算 | 计算效率高，加密强度高 | 需提前共享密钥，易泄露 | DES、AES、RC4|敏感数据加密|
|非对称加密 | 加解密密钥不相关 | 无需提前共享密钥 | 计算效率低，仍存在中间人攻击可能 | RSA、ECC、DSA|秘钥加密|
|散列算法|不可逆（加密性强的）|算法公开|通过散列结果，无法推出任何部分的原始信息|MD5、SHA1|验证消息完整性|


## 2 对称加密

> 指加密和解密使用相同密钥的加密算法。对称加密算法的优点在于加解密的高速度和使用长密钥时的难破解性。

```bash
常见对称加密算法：DES、3DES、DESX、Blowfish、IDEA、RC4、RC5、RC6和AES
```


## 3 非对称加密

> 指加密和解密使用不同密钥的加密算法，也称为公私钥加密。

```bash
常见非对称加密算法：RSA、ECC（移动设备用）、Diffie-Hellman、El Gamal、DSA（数字签名用）
```
 
## 4 散列算法

> 用户可以通过Hash算法对目标信息生成一段特定长度的唯一的Hash值，却不能通过这个Hash值重新获得目标信息。

```bash
常见散列算法：MD2、MD4、MD5、HAVAL、SHA、SHA-1、HMAC、HMAC-MD5、HMAC-SHA1
```
