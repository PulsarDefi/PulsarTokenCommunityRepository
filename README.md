# 🪙 PulsarTokenCommunityRepository

<br/>

## ⚒️ Why This Repository?

- At Pulsar its impossible to keep up with all indexers and tokens available or any single chain. To help with this, we've created this repository where the community can support with adding information about newly added tokens that otherwise would have taken longer to be picked up by Pulsar
  <br/>

## 🧩 Schema

#### Token Data Schema

```
Type AssetType(Enum, String) {
    native,
    contract
}

Type TokenID {
    "token_type": AssetType,
    "token_value": String,
    "decimals": Number
    "chain": String,
}

Type Token {
    "token_id": TokenID
    "name": String,
    "symbol": String,
    "description": String,
    "logo": String | null,
    "coingecko_id": String | null,
}
```

#### Notes

...

<br/>

## 📚 Useful Links

- [Website](https://pulsar.finance)
- [Discord](https://discord.gg/MEeEeyuYsU)
- [Telegram](https://t.me/pulsarfinance)
- [Twitter](https://twitter.com/Pulsarfinance)
