# Battle Hero - Rest API

## Endpoints

* [Sells history](https://51.210.246.47/history/sells/) : `GET https://51.210.246.47/history/sells/:page?`

**Response**

```json
[
  {
    "_id": "61b6d48991f2c36d345ea9ed",
    "buyerAddress": "0xC51dCf1db923f70beA6cf0cfE677f7Ee94A23dbD",
    "sellerAddress": "0xA2f9eeDBD2c4769CCD1587f9b204C71d681021e0",
    "heroId": 199394,
    "price": 200,
    "auctionId": 2343,
    "blockNumber": 13430472,
    "blockTimestamp": 1639371912,
    "__v": 0
  }
]
```
* [Hero](https://51.210.246.47/hero/10004) : `GET https://51.210.246.47/hero/:id`

**Response**

```json
{
  "owner": "0x0000000000000000000000000000000000000000",
  "id": "10004",
  "genetic": "1330086039471300",
  "name": "TERRORIST",
  "rarity": "COMMON"
}
```
