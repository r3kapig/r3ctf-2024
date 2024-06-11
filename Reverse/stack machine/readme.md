`score:964` `solve_count:2`    
a stack machine without memory, loop or branch.

**Tips: run_rkt.zo of Attachment is same as sort (stack machine)**

Clarifications for `stack machine` series:
- The stack machine does not have any opcode about control flow. It simply runs from the first instruction to the last.
- The stack machine does not use memory either (so there are no opcode to read or write memory). It only work on two stacks. Since the machine has no internal state, you can run each opcode one-by-one.
- For most opcodes, you don't need to reverse run_rkt.zo to know what they do - exploring the run function is enough. Focus on the `code` file instead.

Hint: here is a (partial) alternative implementation of the stack machine: https://pastebin.com/SkM9Jw3d
* This alternative implementation does not contain all opcodes so you are not able to run the code directly using that
* However, this challenge will be more like crypto or misc when alternative implementation is released
* Why is code only 625 bytes after compression?

