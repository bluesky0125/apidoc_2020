

 # HTDF 2020版API 文档
 
 
 
## token数量单位
- 我们的数量单位，完全参考BTC
- 两个数量单位 HTDF、satoshi（聪）
- 最小单位是 satoshi（聪）

```
1 HTDF =  100000000 satoshi（聪）
1 satoshi（聪） = 0.00000001 HTDF
```


## 与历史版本的比对
- [HTDF 2019版API文档](https://github.com/orientwalt/apidoc)

> 不带智能合约

> 查交易明细RPC接口： /transaction/{hash}

- [HTDF 20202版API文档](https://github.com/orientwalt/apidoc_2020)
> 带智能合约

> 消息格式，在HTDF 2019版基础上做了少量字段的改动
>> 详见Demo和 RPC文档，并留意HTDF 2019版 和 HTDF 2020版的差别

> 查交易明细RPC接口： /txs/{hash}
>> 应答结果与 /transaction/{hash}  有一定差别； 详见接口文档



