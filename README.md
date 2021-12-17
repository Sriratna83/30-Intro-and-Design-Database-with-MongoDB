1. One to one

   Schema : 

```js
{
"_id": "ObjectId('AAA')",
"fullName": "Sri Ratna Ningsih",
"email": "sriratnaningsih53@gmail.com",
"phoneNumber": "087864456651"
}
```
2. Relasi one to many

   Schema : 
```js
{
    "_id": "ObjectId('AAA')",
    "fullName": "Sri Ratna Ningsih",
    "phoneNumber": "087864456651"
    "address": ["Surabaya","Bandung",]
}
```

3. one to many

   Schema : 

```js
{
    "_id": "ObjectId('AAA')",
    "productName": "Kaos Polos",
    "brandName": "SkilShirt",
    "variant": [{
        "variantName": "Kaos Polos Hitam",
        "color": "Hitam",
        "quantity": 12,
        "price": "Rp 99.000",
    },{
        "variantName": "Kaos Polos Navy",
        "color": "Navy",
        "quantity": 10,
        "price": "Rp 99.000",
    }]
}
```

4. one to many

  Schema : 

```js
[
    {
    "_id": "ObjectId('AAA')",
    "cinemaName": "CGF",
    "films": [
        "ObjectId('Venom 2')",
        "ObjectId('Spiderman No Way Home')"
    ],
    "location": "Pondok Indah Mall"
    },
    {
    "_id": "ObjectId('BBB')",
    "cinemaName": "Cinema 31",
    "films": [
        "ObjectId('Venom 2')",
        "ObjectId('Spiderman No Way Home')"
    ],
     "location": "Mall Kelapa Gading"
    }
]
```
