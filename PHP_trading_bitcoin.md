# How to trade bitcoin through PHP language

## Solution One: pay to ExinCore API
[Exincore](https://github.com/exinone/exincore) provide a commercial trading API on mixin network.

You pay USDT to ExinCore, ExinCore transfer Bitcoin to you on the fly with very low fee and fair price. Every transaction is anonymous to public but still can be verified on blockchain explorer. Only you and exincore know the details.

ExinCore don't know who you are because ExinCore only know your client's uuid.

### Pre-request:
You should already have created a wallet based on Mixin Network. Create one by reading [PHP Bitcoin tutorial](https://github.com/wenewzhang/mixin_labs-php-bot).

#### Install required SDK
```
code
```
#### Deposit USDT into your Mixin Network account and read balance
```
code
```
#### read market price
```
code
```
#### Create a memo to prepare order
```
code
```
#### Pay USDT to API gateway with generated memo
```
code
```
#### Read Bitcoin balance
```
code
```

## Solution Two: List your order on Ocean.One exchange
