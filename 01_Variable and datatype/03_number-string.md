
## Number
Number types include integers, floats, and less commonly, complex numbers. Integers have no decimal part, floats have a decimal part, and complex numbers have a real and an imaginary part.

| Operation               | Symbol | Input      | Output                |
|-------------------------|--------|------------|-----------------------|
| Addition                | +      | 3 + 6      | 9                     |
| Subtraction             | -      | 3 - 6      | -3                    |
| Multiplication          | *      | 3 * 6      | 18                    |
| Decimal Division        | /      | 3 / 6      | 0.5                   |
| Integer Division        | //     | 3 // 6     | 0                     |
| Power                   | **     | 2 ** 3     | 8                     |
| Square Root             | **0.5  | 2 ** 0.5   | 1.4142135623730951    |
| Modulus                 | %      | 7 % 3      | 1                     |
| Increment               | += 1   | x = 1; x+=1| 2                     |
| Decrement               | -= 1   | x = 1; x-=1| 0                     |
| Multiplication Assignment| *= 1  | x = 2; x*=3| 6                     |

</br>

## String
A string is a sequence of characters.<br> 
Strings can be created using single quotes ('') or double quotes ("").

| Description                         | Syntax                             | Input                                    | Output           |
|-------------------------------------|------------------------------------|------------------------------------------|------------------|
| String Literals                     | "", ''                             | "Hello"                                  | Hello            |
| Escape Characters                   | \                                  | s="Hell\"o"                              | Hell"o           |
| Concatenation                       | "" + "", " " "                     | s="Hello"+"World"<br>s="Hello" "World"   | HelloWorld       |
| New Line                            | \n                                 | s="Hello\nWorld"                         | Hello<br>World   |
| Multiline Strings                   | """ """                            | """Hello<br>World"""                     | Hello<br>World   |
|                                     |                                    | """Hello<br><br>World"""                 | Hello<br><br>World |
| Repetition                          | *                                  | s="Hello"*3                              | HelloHelloHello  |
| Indexing                            | String[index]                      | s="Hello"<br>print(s[0])                 | H                |
| Substring (inclusive:exclusive)     | String[start:end]                  | s="Hello"<br>print(s[1:4])               | ell              |
| Slice from Start                    | String[start:]                     | s="Hello"<br>print(s[1:])                | ello             |
| Slice to End                        | String[:end]                       | s="Hello"<br>print(s[:4])                | Hell             |
