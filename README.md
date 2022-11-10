# Crypto-Tech-Docs

## Base URL

`https://crypto2211.000webhostapp.com/`

## Get Coins

- Path: `/getCoins.php`
- Method: `GET`

### Response

|Field Name|Type|Required|
|---|---|---|
|coins|Array|Yes|
|coins[].id|String|Yes|
|coins[].name|String|Yes|
|coins[].price|Double|Yes|
|coins[].imageURL|String|Yes|
