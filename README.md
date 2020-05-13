# definite_clause_grammars
A script based on the concept DCG (Definite Clause Grammars).

To run that script, run on swipl:

`?- [definite_clause_grammars].`

And then, you will can test all those functions spicified in the script. An example:

```
?- possessive_phrase(X, [and, it, is, so, beautiful]).
X = [this, is, my, tree, and, it, is, so, beautiful] ;
X = [this, is, my, car, and, it, is, so, beautiful] ;
X = [this, is, my, cellphone, and, it, is, so, beautiful] ;
X = [this, is, my, tv, and, it, is, so, beautiful] ;
X = [this, is, your, tree, and, it, is, so, beautiful] ;
X = [this, is, your, car, and, it, is, so, beautiful] ;
X = [this, is, your, cellphone, and, it, is, so, beautiful] ;
X = [this, is, your, tv, and, it, is, so, beautiful] ;
X = [this, is, his, tree, and, it, is, so, beautiful] ;
X = [this, is, his, car, and, it, is, so, beautiful] ;
X = [this, is, his, cellphone, and, it, is, so, beautiful] ;
X = [this, is, his, tv, and, it, is, so, beautiful] ;
X = [this, is, her, tree, and, it, is, so, beautiful] ;
X = [this, is, her, car, and, it, is, so, beautiful] ;
X = [this, is, her, cellphone, and, it, is, so, beautiful] ;
X = [this, is, her, tv, and, it, is, so, beautiful] .

?- future_perfect_progressive_phrase(X, []).
X = [i, will, have, been, playing] ;
X = [i, will, have, been, talking] ;
X = [i, will, have, been, riding] ;
X = [i, will, have, been, waking] ;
X = [i, will, have, been, sitting] ;
X = [i, will, have, been, yawning] ;
X = [you, will, have, been, playing] ;
X = [you, will, have, been, talking] ;
X = [you, will, have, been, riding] ;
X = [you, will, have, been, waking] .

?- superlative_phrase(X, [of, the, world]).
X = [i, am, the, worst, of, the, world] ;
X = [i, am, the, prettiest, of, the, world] ;
X = [i, am, the, strongest, of, the, world] ;
X = [i, am, the, coolest, of, the, world] ;
X = [i, am, the, bestest, of, the, world] ;
X = [i, am, a, worst, of, the, world] ;
X = [i, am, a, prettiest, of, the, world] ;
X = [i, am, a, strongest, of, the, world] ;
X = [i, am, a, coolest, of, the, world] ;
X = [i, am, a, bestest, of, the, world] ;
X = [you, are, the, worst, of, the, world] ;
X = [you, are, the, prettiest, of, the, world] ;
X = [you, are, the, strongest, of, the, world] ;
X = [you, are, the, coolest, of, the, world] ;
X = [you, are, the, bestest, of, the, world] ;
X = [you, are, a, worst, of, the, world] ;
X = [you, are, a, prettiest, of, the, world] ;
X = [you, are, a, strongest, of, the, world] ;
X = [you, are, a, coolest, of, the, world] ;
X = [you, are, a, bestest, of, the, world] ;
X = [he, is, the, worst, of, the, world] ;
X = [he, is, the, prettiest, of, the, world] ;
X = [he, is, the, strongest, of, the, world] ;
X = [he, is, the, coolest, of, the, world] ;
X = [he, is, the, bestest, of, the, world] ;
X = [he, is, a, worst, of, the, world] .
```
