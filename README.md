# tlcp-examples
Feel free to fork and issue pull requests. Details of examples found below.

# Files

| File Name     | Returns       | Difficulty| Description |
| ------------- | :------------: | :-------------: | ------------- |
| andff.tlcp | 1 | "Easy" | tests (false and false)|
| andft.tlcp | 1 | "Easy" | tests (false and true)|
| andtt.tlcp | 0 | "Easy" | tests (true and true)|
| div.tlcp | {sel . (ifz sel 3 1)} | "Hard" | implements division |
| fact.tlcp | 6 | "Medium" | implements a factorial |
| fermat.tlcp | Never | "Very Hard" | searches for counterexamples to Fermat's Last Theorem |
| lt.tlcp | 0 | "Medium" | implements integer comparisons |
| omega.tlcp | Never | "Easy" | simple infinite loop |
| orff.tlcp | 1 | "Easy" | tests (false or false)|
| orft.tlcp | 0 | "Easy" | tests (false or true)|
| ortf.tlcp | 0 | "Easy" | tests (true or false)|
| nott.tlcp | 1 | "Easy" | tests (not true)|
| notf.tlcp | 0 | "Easy" | tests (not false)|
| err-bools.tlcp | NONE (as Unit) | "Easy" | uses error stuff to make booleans |
| err-medium.tlcp  | 1 | "Medium"| uses lots of the grammar but doesn't do anything cool |
| nat-bools.tlcp | 0 | "Easy" | uses nats to make booleans|
| prod.tlcp | 4 | "Medium" | computes products |
| pythag.tlcp | 1 | "Hard" | checks if three naturals form a Pythagorean triple |
| sum.tlcp | 2 | "Easy" | computes sums |
| wilson.tlcp | 1 | "Very hard" | verifies Wilson's Theorem up to a certain range |

# Run
```
rlwrap sml -Cprint.depth=9999
CM.make "sources.cm";
Compile.file "FILENAME.tlcp";
```
