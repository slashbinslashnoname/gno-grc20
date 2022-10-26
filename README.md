# gno-grc20

Implementation or an ERC20 in native Gnolang.
With Test suite.

## Test

```
gnodev test . --verbose --root-dir ../gno
```

## Deploy

````
gnokey maketx addpkg "MYWALLET" --gas-fee "1ugnot" --gas-wanted "5000000" --pkgdir "." \
> --broadcast true --remote "localhost:26657" --chainid "dev" --pkgpath "gno.land/r/slashcoin"
````
