## reading notes
# class 22

What is a ‘call’? Primarily used for function invocation.
How many ‘calls’ can happen at once? One at a time, from top to bottom.
What does LIFO mean? Last In, First Out
Draw an example of a call stack and the functions that would need to be invoked to generate that call stack. 
function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();
What causes a Stack Overflow? When there is a recursive function (a function that calls itself) without an exit point. (Links to an external site.)
What is a ‘reference error’? When a variable that doesn't exist
What is a ‘syntax error’? A character or string incorrectly placed
What is a ‘range error’? Thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value.
What is a ‘type error’? An error when an operation could not be performed, typically (but not exclusively) when a value is not of the expected type.
What is a breakpoint? A stopping or pausing place in a program, put in place for debugging purposes.
What does the word ‘debugger’ do in your code? To run your code step by step in a debugging tool, to find the exact point where you made a programming mistake. 
