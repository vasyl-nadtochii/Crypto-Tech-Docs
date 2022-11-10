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

## Get Details

- Path: `/getDetails.php`
- Method: `GET`

### Response

|Field Name|Type|Required|
|---|---|---|
|currentPrice|Double|Yes|
|periodPrices|Array|Yes|
|periodPrices[].id|String|Yes|
|periodPrices[].date|Date|Yes|
|periodPrices[].price|Double|Yes|
|news|Array|Yes|
|news[].id|String|Yes|
|news[].date|Date|Yes|
|news[].title|String|Yes|
|news[].url|String|Yes|
