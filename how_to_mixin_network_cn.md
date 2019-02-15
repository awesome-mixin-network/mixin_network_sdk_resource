
## How to create a Bitcoin wallet by mixin network api
1. Create a Mixin Network account by calling API [APP User](https://developers.mixin.one/api/alpha-mixin-network/app-user/), [Ruby](), [Python3](), [Golang SDK by Mixin team](https://github.com/MixinNetwork/bot-api-go-client/blob/d9ba64afb222b7603343a18f7a3184337d28490d/user.go#L18), [Golang SDK by Foxone](https://github.com/MooooonStar/mixin-sdk-go/blob/86ceb8befd01e7fc7004f161cd1abf3ac69e4bf3/network/network.go#L169), [PHP](https://github.com/ExinOne/mixin-sdk-php/blob/c5753262672a162fddd77af94e0aa1e22c1ccbf2/src/Apis/Network.php#L112), [Node.js](), [CSharp](https://github.com/ibigbug/Mixin-SDK-CSharp/blob/aa4d8855fb8f6d13af67b77a777a240702fb1e8a/Mixin.Network/Network.cs#L174)
2. Then create a Bitcoin deposit address by calling API [Deposit/Read Asset](https://developers.mixin.one/api/alpha-mixin-network/deposit/), [Ruby](https://github.com/an-lee/mixin_bot/blob/8bf4ee4e8f1d46e897275760147fa02aaab35d62/lib/mixin_bot/api/me.rb#L29), [Python3](https://github.com/includeleec/mixin-python3-sdk/blob/631094e95b5b405b033fb200c5f0314a6aee5205/mixin_api.py#L464), [Golang SDK by Mixin team](https://github.com/MixinNetwork/bot-api-go-client/blob/0a312e20e4595767b8df29cc4289cb1b36ed1571/asset.go#L46), [Golang SDK by Foxone](https://github.com/MooooonStar/mixin-sdk-go/blob/86ceb8befd01e7fc7004f161cd1abf3ac69e4bf3/network/network.go#L42), [PHP](https://github.com/ExinOne/mixin-sdk-php/blob/3491a33cb70ce298f0b14ba3c907da15cd01f1fc/config/config.php#L45), [Node.js](https://github.com/wangshijun/mixin-node-client/blob/0fa893441f900bb0db65788507c293aba11f00d3/lib/endpoints.js#L122), [CSharp](https://github.com/ibigbug/Mixin-SDK-CSharp/blob/aa4d8855fb8f6d13af67b77a777a240702fb1e8a/Mixin.Network/Network.cs#L36)


## How to check balance of Bitcoin
1. Read bitcoin asset by calling [Read Asset](https://developers.mixin.one/api/alpha-mixin-network/read-asset/), [Ruby](https://github.com/an-lee/mixin_bot/blob/8bf4ee4e8f1d46e897275760147fa02aaab35d62/lib/mixin_bot/api/me.rb#L29), [Python3](https://github.com/includeleec/mixin-python3-sdk/blob/631094e95b5b405b033fb200c5f0314a6aee5205/mixin_api.py#L464), [Golang SDK by Mixin team](https://github.com/MixinNetwork/bot-api-go-client/blob/0a312e20e4595767b8df29cc4289cb1b36ed1571/asset.go#L46), [Golang SDK by Foxone](https://github.com/MooooonStar/mixin-sdk-go/blob/86ceb8befd01e7fc7004f161cd1abf3ac69e4bf3/network/user.go#L113), [PHP](https://github.com/ExinOne/mixin-sdk-php/blob/c5753262672a162fddd77af94e0aa1e22c1ccbf2/src/Apis/Wallet.php#L147), [Node.js](https://github.com/wangshijun/mixin-node-client/blob/0fa893441f900bb0db65788507c293aba11f00d3/lib/endpoints.js#L15), [CSharp](https://github.com/ibigbug/Mixin-SDK-CSharp/blob/aa4d8855fb8f6d13af67b77a777a240702fb1e8a/Mixin.Network/Network.cs#L107)
2. Or read all assets by calling [API](), [Ruby](), [Python3](), [Golang SDK by Mixin team](), [Golang SDK by Foxone](), [PHP](), [Node.js](), [CSharp]()

## How to transfer bitcoin to another mixin network account
1. Make sure the account has already created a PIN code
2. Developer transfer the Bitcoin to another account for user by calling [API](), [Ruby](), [Python3](), [Golang SDK by Mixin team](), [Golang SDK by Foxone](), [PHP](), [Node.js](), [CSharp]()
3. Developer read the transfer status to confirm the transfer result by calling [API](), [Ruby](), [Python3](), [Golang SDK by Mixin team](), [Golang SDK by Foxone](), [PHP](), [Node.js](), [CSharp]()
4. Developer can also read payment status to confirm the transfer result  by calling [API](), [Ruby](), [Python3](), [Golang SDK by Mixin team](), [Golang SDK by Foxone](), [PHP](), [Node.js](), [CSharp]()

## How to transfer bitcoin inside Mixin Network account to another exchange, wallet
1. Make sure the account has already created a PIN code
2. Make sure the account has created a withdrawal address


## what is PIN code
PIN code is a six digit number. It is part of security design of Mixin Network account. User need to provide correct PIN code to update PIN code, transfer asset, create withdraw address and other operation.
Developer can create PIN code by calling [API](), [Ruby](), [Python3](), [Golang SDK by Mixin team](), [Golang SDK by Foxone](), [PHP](), [Node.js](), [CSharp]()
## How to create PIN code
