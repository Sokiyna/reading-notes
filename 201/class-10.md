***Error Handling & Debugging***

The JavaScript interpreter uses the concept of execution contexts. There is one global execution context. Also each function creates a new new execution context. They assigned it  to variable scope.

EXECUTION CONTEXT 

Each statement in a script stays inside one of three
execution contexts:
1- Global Context
2- Function Context
3-Evaluation Context (NOT SHOWN)

VARIABLE SCOPE

1- Global Scope

**ERROR OBJECTS**

The error objects can help us find where our mistakes located and browsers have tools to help us to read them.

When the error is created it will contain properties:

1- Name
2-Message
3-FileNumber
4-LineNumber

**A DEBUGGING WORKFLOW**

Debugging is about deduction which is mean eliminating possible causes of an error. 

You can follow these steps to narrow your errors:

1- look at the error  it will contain three parts:

-The relevant script which is cause the problem
-The line where the problem come from
-The type of error.
  
  2- Make sure how the script is running so far.

  3- try ti use brackpoint where the things are going wrong. 
