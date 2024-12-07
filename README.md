This repository demonstrates a common error in Haskell: using an undefined variable.  The `bug.hs` file contains the erroneous code, which attempts to add 5 to an undefined variable. The `bugSolution.hs` file shows the corrected code.

This example highlights the importance of ensuring all variables have defined values before use in Haskell, which has a strong static type system and evaluates expressions lazily.  Failure to do so results in a runtime error.