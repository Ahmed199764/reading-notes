# Class10

## Error Handling and Debugging
We all have problems and errors when we deal with javascript , thats normal cuz its a really hard lang to learn, even pro programmers keep do error and mistakes with it.
Also its really good to know how scripts are proceesed its helping in find errors.
JaveScripts read and use codes line by line at a time ,When a statment needs data from another function, it stacks the new function on top of the current task.

##### Each time a script enters a new execution context, there are two phases of activity:-
1. Prepare 
2. execute

#### prepare :-
1. the new scope is created
2. Variables,functions are created
3. the value of this word is created

#### execute :-
1. now it can assign to varibales 
2. Refreneces functions and run their code
3. excute statments

notice : If a JavaScript statement generates an error, then it throws an exception.

### Error objects 
Error objects can help you find where your mistakes are and browsers have tools to help you read them.

### HOW TO DEAL WITH ERRORS?
1. DEBUG THE SCRIPT TO FIX ERRORS
2. HANDLE ERRORS GRACEFULLY

## How to look at errors in ?
by browsers console. 
such as chrome , firefox , opera.

##### How to login data into console ?
consle.log();

#### more console methods :-
1. console.info() can be used for general information
2. console.warn() can be used for warnings 
3. console.error() can be used to hold errors 


### Breakpoints 
You can pause the execution of a script on any line using breakpoints. Then you can check the values stored in variables at that point in time.

