# BAC
Not a Big hAdron Collider, its simple description of **Build A Questions technique**

## What about objects and the properties of objects?


Again, there are many benchmarks for Q&A. And nowadays, neural networks with a 30 mb size can find answers better than humans.
And with Q&A it's possible to get almost any information about objects (what is the **color** of **object_name**).

It takes two modules to do that - first module projects objects to syntax tree:

**{book {num_of_pages = 10, color = white, author=null}}** - **white book with 10 pages**

the second one - builds a question to properties 

**{book {num_of_pages = 10, color = white, author=null}}**, - **Who is the author of white book with 10 pages?**



Note that we can ask many questions, and even incorrect ones (that will lead us to incorrect results), so we need add some attributes (to define right question for that item). (Whenwolf)

After all of that will be completed - we can extract **data about all defined objects** and their properties.

So defining the simpliest generator of questions based on json-like object descriptions is the trivial thing. (That's called reading :) )

And we dont need to train transformer with 20 billion parameters to get information about any objects (in final specification or in design rules).

We can extract any data about objects and states with questions.


## What with rules (functions) and so on?


We have defined primitives (with parameters). 
And text rules (with descriptions of positive and negative examples, where properties of objects are described).

Most funny and "unthinkable" thing is that rules consist of objects, and rules are actually is objects too :).

So we can build a basic abstractions (sizes/forces/etc), rules, based on json, and read all specifications. And make even complex rules (with objects and operators).

Also, we need to add some functions that describe relations between objects (size, positions, and other connections). 
And detect them. Note that we can also describe that in json notation (and generate questions, and get information).

(Note that we can write functions bodies like code that takes objects (he he), or use approximations based on machine learning, or even build them from primitives (DreamCoder, DARPA)). Even **Reading functions** can be developed (to get information for knowledge database).

So we can build text-based rules (and functions).

That will work better than traditional aproaches because we have context synonyms and other "syntaxis shugar" inside our Q&A net.
And we can get all objects, functions and other primitives on home PC in minutes. (Even without using of supercomputer)

And we can also add changing of objects (counts and types). That is the function too ).


## What with levels of abstractions? ##


Abstraction can be represented as Sets of objects that translates with some function to another object (and back). Directly with properties mapping or in a complex way.
If we can define translation functions with a few examples (or use approximation based on machine learning) its not hard to build a hierarcy of abstraction levels.
And define heuristics/constrains and result properties on any level of abstraction.


