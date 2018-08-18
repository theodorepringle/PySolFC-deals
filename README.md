# PySolFC-deals

The impossible and intractable 4-freecells and 5-freecells deals in
[PySol FC](https://pysolfc.sourceforge.io/)’s Range of
Deals - from 1 to 1,410,100,000, where the first 32,000
deals are compatible with
[Microsoft FreeCell](https://en.wikipedia.org/wiki/Microsoft_FreeCell).

These lists are based on the efforts of Theodore Pringle.

# More Information

* [Thread on fc-solve-discuss](https://groups.yahoo.com/neo/groups/fc-solve-discuss/conversations/messages/1597)

# License

MIT/Expat license see [the LICENSE file](./LICENSE) .

# Generating the deals

```
$ make_pysol_freecell_board.py -F -t 100000 freecell
5C 5S JD 7H QC 3S 3H
2D 2H 8H 8S AH 9D 3C
9H 6S 5H 7C 9C 7D 3D
6D 4D QS JH 7S KS AC
TH JS 2C 6H KH AS
4S 9S 5D 2S JC 6C
TD QD 4C AD TC QH
4H TS 8C KC 8D KD
```

(from the [Freecell Solver](http://fc-solve.shlomifish.org/) distribution.)
