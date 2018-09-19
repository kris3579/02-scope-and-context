## Question 1

### Identify all the LHS look-ups (there are 3!).

a = ...

b = ...

c = ...

## Question 2

foo(...)

... = a

a + ...

... + b

### Identify all the RHS look-ups (there are 4!).


## Conversation

Engine: Hey Scope, I have an RHS reference for foo. Ever head of it?

Scope: Why yes, I have. Compiler declared it just a second ago. He's a function. Here you go.

Engine: Great, thanks! OK, I'm executing foo.

Engine: Hey, Scope, I've got an LHS reference for a, ever heard of it?

Scope: Why yes, I have. Compiler declared it as a formal parameter to foo just recently. Here you go.

Engine: Hey, Scope, I've got an LHS reference for b, ever heard of it?

Scope: Why yes, I have. Compiler declared it just a second ago. He is a variable. Here you go.

Engine: Hey, Scope, I've got an RHS reference for a, ever heard of it?

Scope: Why yes, I have. Compiler declared it as a formal parameter to foo earlier, Here you go.

Engine: Helpful as always, Scope. Thanks again. Now, time to assign a to b.

Engine: Hey, Scope, I've got an RHS reference for a, ever heard of it?

Scope: Why yes, I have. Compiler declared it as a formal parameter to foo earlier, Here you go.

Engine: Hey, Scope, I've got an RHS reference for b, ever heard of it?

Scope: Why yes, I have. it was set as equal to a earlier, Here you go.

Engine: Great I will now add a and b together.

Engine: Hey, Scope, I've got an LHS reference for c, ever heard of it?

Scope: Why yes, I have. Compiler declared it as a variable, Here you go.

Engine: Hey Scope, I have an RHS reference for foo. Ever head of it?

Scope: Why yes, I have. Compiler declared it awhile ago. He's a function. Here you go.

Engine: Great, I will now run the function and assign the result to c.
