# ostabloswap
Wrapper for ostable i-tokens oswap pools

Deploy an AA with following parameters:
```
{
    base_aa: "XUP6AKBIBRWJQUNUJNQGVYTKEE6OQTNJ",
    params: {
        pool: "oswap pool address",
        stable0: "asset0 stable address",
        stable1: "asset1 stable address"
    }
}
```

Will use underlying i token pool to swap one stable token for another costing 4KB each swap
