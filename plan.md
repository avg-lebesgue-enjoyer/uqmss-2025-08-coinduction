[x] Vanilla Induction 
  [ ] Specify $\mathbb{N}$: Recursion principle, Constructors
  [ ] 2 examples of recursion (include `Nat.add`)
  [ ] Thm. Induction principle
  [ ] 2 examples of induction

[x] Vanilla Corecursion
  [ ] Def $\coN := \mathbb{N} \squ \No$
  [ ] Def $\pred : \coN \r \coN$, *partial functions*
  [ ] Construction. Corecursion principle (call `corec := wait`)
    [ ] Note: Cases for $\pred (\wait\ f\ x)$
    [ ] Note: This doesn't mention $\infty$ at all! Or any particular conatural number, for that matter!
    [ ] Note: For categorically brained, $pred$ is the *terminal partial function*
        ^^ maybe do this later?
  [ ] Examples: `CoList.length`, `coNat.add`
    [ ] (These exist in the Lean project, if you wanna demo them)

[x] Vanilla Coinduction
  [ ] Thm. (Simple) Coinduction principle
    [ ] Note: Useful even if you don't know what the conats are! i.e. perfect for reasoning about corecursive functions
    [ ] Note: It gets rid of case-splitting on $\infty$
    [ ] Give pfsk?
  [ ] Ex: $\forall x \in \coN, x + 0 = x$
  [ ] Ex: $\forall x, y, y' \in \coN, y' = \pred y \implies \pred (x + y) = x + y'$
  [ ] Ex: $\forall x, y \in \coN, x + y = y + x$
  [ ] Ex: Sketch of $\forall x, y, z \in \coN, (x + y) + z = x + (y + z)$

[ ] Higher-level: Recursive structures, Structural induction

[ ] Higher-level: Corecursive structures, Simple coinduction
