## Hello World with Lit

Here is an overview of a hello world Haskell program.  We define * as the macro from which all other code or macros exist.
```Haskell
<< * >>=
<< a trivial comment >>
<< print a string >>
```
Now we can define each of the above macros,
beginning with an inconsequential comment!
```Haskell
<< a trivial comment >>=
-- this is a hello world haskell program
```
Lastly our program needs to print hello world
```Haskell
<< print a string >>=
main = putStr "Hello, World!"
```
