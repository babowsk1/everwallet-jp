# ウォレットのタイプ

EVER Walletは、動作の仕様が異なる数種類のウォレットの作成に対応しています：

**SafeMultisig** - 正式認証されたマルチシグウォレットです。\
**SafeMultisig24** - カストディアンによるSafeMultisigウォレットの確認は最大1時間、SafeMultisig24では確認までに最大24時間かかります。制限時間内に必要な署名数に達しない場合、トランザクションは無効となります。\
**SetCodeMultisigWallet** - コードやカストディアンを変更できるマルチシグウォレットです。 **BridgeMultisigWallet** - このタイプのウォレットは、SafeMultisigとは異なり、ペイロード制限を設けていません。

{% hint style="info" %}
[FlatQube](broken-reference/)と[Octus Bridge](https://docs.octusbridge.io/)で、3つ以上のカストディアンを持つマルチシグウォレットを使用したい場合は、必ず**BridgeMultisigWallet**タイプをご使用ください！
{% endhint %}

**Surf** - 技術的には、このタイプのウォレットはSetCodeMultisigと同じです。Ever Surfウォレットをインポートするには、このタイプのウォレットを使用する必要があります。\
**WalletV3** - 転送と同時にウォレットをデプロイできる小さくてシンプルなコントラクトで、24単語のシードフレーズで構成されています。
