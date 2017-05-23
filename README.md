# tlcp-examples
Feel free to fork and issue pull requests. Details of examples found below. Looking for people to write "fix" in tlcp and inductively defined numbers without recursion. 

# Files

| File Name     | Returns       | Difficulty| Description |
| ------------- | :------------: | :-------------: | ------------- |
| andff.tlcp | 1 | "Easy" | tests (false and false)|
| andft.tlcp | 1 | "Easy" | tests (false and true)|
| andtt.tlcp | 0 | "Easy" | tests (true and true)|
| orff.tlcp | 1 | "Easy" | tests (false or false)|
| orft.tlcp | 0 | "Easy" | tests (false or true)|
| ortf.tlcp | 0 | "Easy" | tests (true or false)|
| nott.tlcp | 1 | "Easy" | tests (not true)|
| notf.tlcp | 0 | "Easy" | tests (not false)|
| err-bools.tlcp | NONE (as Unit) | ? | uses error stuff to make booleans |
| err-medium.tlcp  | 1 | "Medium"| uses lots of the grammar but doesn't do anything cool |
| nat-bools.tlcp | 0 | "Easy" | uses nats to make booleans|

# Run
```
rlwrap sml -Cprint.depth=9999
CM.make "sources.cm";
Compile.file "FILENAME.tlcp";
```
