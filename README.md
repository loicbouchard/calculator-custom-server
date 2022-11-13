# Calculator-server

## start project

- npm install
- npm start

## changes

GET /shop/:shopId/search-combination always returns the previous and next value

example with the value 22 :

```
{
    equal: 22,
    floor: 20,
    ceil: 25
);
```

example with the value 20 :

```
{
    equal: 20,
    ceil: 22
);
```

example with the value 10 :

```
{
    equal: 20,
    ceil: 22
);
```

example with the value 100 :

```
{
    equal: 70,
    floor: 57,
);
```
