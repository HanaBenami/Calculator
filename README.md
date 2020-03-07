# Calculator
**A calculator based on a state-machine design pattern and dijkstra algorithm.**
<br/><br/><br/>
:zap: The calculator project contains three moduls (all of them with **O(n)** algorithmic complexity):

1. **A brackets checker** 
2. **A lexer**, which breaks down the input string to expressions and operators
3. **A state machine**, that goes through the string and "solves" it, using the lexer, two stacks, dijkstra algorithm and some simple mathematics functions. 

<br/>
:zap: Currently, the input string may contains: <br/><br/>

* Binary operators: + - * x X / : ^ V(root)
* Unary operators: + - ! %
* Brackets: () [] {}
* Decimal numbers

The above lists can be extended easily, with minor changes. 
