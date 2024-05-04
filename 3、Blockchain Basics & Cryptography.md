## 3、Blockchain Basics & Cryptography

### 1、bitcone design feature



### 2、Crypetographic hash function

hash算法得在明确的输入的前提下得到一致的输出，不可以是随机的，很长的输入下得到一致长度的输出

### 3、timestamp append only

![img](https://cdn.nlark.com/yuque/0/2024/png/8426723/1714807132171-68ff5403-de25-4d01-ba8c-3db69b751046.png)

### 4、block header &merkle tree

Version

previous block hash

markle root hash 是一种获取所有交易信息的方式，是一颗二叉hash树

![img](https://cdn.nlark.com/yuque/0/2024/png/8426723/1714808128126-4579b022-66c7-4c37-893f-ebfc757ea754.png)

timestamp 时间戳

difficulty target  困难程度

nonce 随机数，随着区块数增加，如果从不同输入但是得到相同的hash值，用这个来区分两个区块

### 5、asymmetric cropotography &digital signature

生成key-paire，公钥和私钥通过随机数是一起生成的