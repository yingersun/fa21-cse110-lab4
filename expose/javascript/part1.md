1. line 9 prints "values added: 20"
2. "final result: 20"
3. "values added: 20"
4. error because the result variable was defined using let, which is block scope. the line 13 console.log is outside the block which result variable was defined in.
5. error because result is a const and line 7 tries to redefine a const var. line 7 outputs an error that breaks the code and line 9 is never reached.
6. error because result is a const and line 7 tries to redefine a const var. line 7 outputs an error that breaks the code and line 13 is never reached.