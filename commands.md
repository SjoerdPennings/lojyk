## Gates
NOT
AND
OR
XOR
NOR
NAND
XNOR

## Commands

| Command                            | With optional args           | Without optional args                     |
| :--------------------------------: | :--------------------------: | :---------------------------------------: |
|[var] ! [arg?]                   | var = NOT arg                | var = NOT var                             |
|[var] & [arg1] [arg2?]           | var = arg1 AND  arg2         | var = var AND  arg1                       |
|[var] | [arg1] [arg2?]           | var = arg1 OR   arg2         | var = var OR   arg1                       |
|[var] ^ [arg1] [arg2?]           | var = arg1 XOR  arg2         | var = var XOR  arg1                       |
|[var] !|  [arg1] [arg2?]           | var = arg1 NOR  arg2         | var = var NOR  arg1                       |
|[var] !& [arg1] [arg2?]           | var = arg1 NAND arg2         | var = var NAND arg1                       |
|[var] !^ [arg1] [arg2?]           | var = arg1 XNOR arg2         | var = var XNOR arg1                       |
|< [1] [2] [3] [4] [5] [6] [7] [8]   | Output 1-8 as one UTF-8 byte | If less than 8 bytes, output what's there |
|> [1] [2] [3] [4] [5] [6] [7] [8]   | See above, but its input     | If less than 8 bytes, input the first n   |

