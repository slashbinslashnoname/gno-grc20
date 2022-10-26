# gno-grc20

Implementation or an ERC20 in native Gnolang.
With Test suite.

## Test

```
gnodev test . --verbose --root-dir ../gno
```

## Deploy

````
gnokey maketx addpkg "g1ah79e3txw2kd2e8dscr2y2ucr888lm3qwm3v6e" --gas-fee "1ugnot" --gas-wanted "5000000" --pkgdir "."  --broadcast true --remote "test2.gno.land:36657" --chainid "test2" --pkgpath "github.com/slashbinslashnoname/gno-grc20"
````
