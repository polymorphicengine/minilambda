# minilambda

An experimental investigation into extending the Tidal Mini-Notation to a Lambda-Calculus style programming language

MiniLambda code is compiled into Haskell code which is then evaluated interactively via Hint and results in a Tidal Pattern.

We therefore have lazy evaluation and full pattern-matching within MiniLambda.

TODO:

- figure out how to deal with control statements, i.e. booleans
- add a lot of syntactic sugar (non-lambda function notation, alternations, polymetric sequences)
- add the random choice construct, where period [x | y] = [period x | period y]
