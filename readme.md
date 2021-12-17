**1. *Skiljek***

```js
{
    "_id" : "ObjectId('AAA')"
    "fullName" : "bujank",
    "email" : "bujank@mail,com",
    "phoneNumber" : "088288888888"
}
```

**2. *Skilshop***

```js
{
    "_id" : "ObjectId('AAA')",
    "fullName" : "bujank",
    "phoneNumber" : "088288888888",
    "address" : [
        {"street" : "jl. jalan", "city" : "balikpapan", "country" : "indonesia"},
        {"street" : "jl. mundur", "city" : "papanbalik", "country" : "indonesia"}
    ]
}
```

**3. Varian *Skilshop***

Product
```js
{
    "productName" : "Kaos Polos",
    "brandName" : "Skilshirt"
    "catalog" : ["ObjectId('XXX')", "ObjectId('YYY')", "ObjectId('ZZZ')"]
}
```
Varian 1
```js
{
    "_id" : "ObjectId('XXX')",
    "varianName1" : "Kaos Polos Hitam",
    "color" : "Hitam",
    "quantity" : "12",
    "price" : "99000"
}
```
Varian 2
```js
{
    "_id" : "ObjectId('YYY')",
    "varianName1" : "Kaos Polos Navy",
    "color" : "Navy",
    "quantity" : "10",
    "price" : "99000"
}
```

**4.*Skilflix***

First Cinema
```js
{
    "_id" : "ObjectId('AX1')",
    "cinemaName" : "CGF",
    "films" : ["ObjectId('AY1')", "ObjectId('AY2')"],
    "location" : "Pondok Indah Mall"
}
```
Second Cinema
```js
{
    "_id" : "ObjectId('AX2')",
    "cinemaName" : "Cinema31",
    "films" : ["ObjectId('AY1')", "ObjectId('AY2')"],
    "location" : "Mall Kelapa Gading"
}
```
Movie 1
```js
{
    "_id" : "ObjectId('AY1')",
    "movieName" : "Venom 2",
    "cinema" : ["ObjectId('AX1')", "ObjectId('AX2')"]
}
```
Movie 2
```js
{
    "_id" : "ObjectId('AY2')",
    "movieName" : "Spiderman No Way Home",
    "cinema" : ["ObjectId('AX1')", "ObjectId('AX2')"]
}
```
