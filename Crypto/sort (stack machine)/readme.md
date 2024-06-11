`score:930` `solve_count:3`    
a stack machine without memory, loop or branch.

**(Tips: file run_rkt.zo is same as stack machine)**

Clarifications for `stack machine` series:
- The stack machine does not have any opcode about control flow. It simply runs from the first instruction to the last.
- The stack machine does not use memory either (so there are no opcode to read or write memory). It only work on two stacks. Since the machine has no internal state, you can run each opcode one-by-one.
- For most opcodes, you don't need to reverse run_rkt.zo to know what they do - exploring the run function is enough. Focus on the `code` file instead.

Hint: here is a (partial) alternative implementation of the stack machine: https://pastebin.com/SkM9Jw3d
* This alternative implementation is enough to solve this challenge, and forward compatible with the original (i.e. you can develop your exploit with the alternative implementation, and it will also work in the original task; opcodes not in this alternative implementation are not relevant to this task)
* This challenge is a sequel of `sort` series in TPCTF 2023, see https://github.com/sajjadium/ctf-archives/blob/main/ctfs/TPCTF/2023/crypto/sort_level_1/sort.py

**Note:if you think your exploit could works localy but not remote,pls open-ticket we could check it localy and give your flag!**
