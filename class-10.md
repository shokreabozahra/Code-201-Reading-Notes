# Ch. 10, “Error Handling & Debugging”
## The Stack
### A stack is usually a continuous region of memory allocating local context for each executing function
## EXECUTION CONTEXT & HOISTING
### Each time a script enters a new execution context, there are two phases of activity:
1. PREPARE 
2. EXECUTE
## ERROR OBJECTS
### EvalError
- Creates an instance representing an error that occurs regarding the global function eval().
### RangeError
-Creates an instance representing an error that occurs when a numeric variable or parameter is outside of its valid range.
### ReferenceError
- Creates an instance representing an error that occurs when de-referencing an invalid reference.
### SyntaxError
- Creates an instance representing a syntax error.
### TypeError
- Creates an instance representing an error that occurs when a variable or parameter is not of a valid type.
### URIError
- Creates an instance representing an error that occurs when encodeURI() or decodeURI() are passed invalid parameters.
### AggregateError
- Creates an instance representing several errors wrapped in a single error when multiple errors need to be reported by an operation, for example by Promise.any().
### InternalError 
- Creates an instance representing an error that occurs when an internal error in the JavaScript engine is thrown.

## DEBUGGING TIPS 
### practical tips when debugging scripts:
- ANOTHER BROWSER
- ADD NUMBERS 
- SEARCH
- CODE PLAYGROUNDS
- VALIDATION TOOLS

<img src = "https://miro.medium.com/max/700/1*EAlxWCsiV4x39VjYRzhOUw.png" width="400" height="400" >