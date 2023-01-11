# Java Access Modifiers

Access modifiers in Java help to restrict the scope of a class, constructor, variable, method, or data member.
There are four types of access modifiers:
    1. Default (no keyword required)
    2. Private
    3. Protected
    4. Public

### Default (No Keyword Req'd)
When no access modifer is specified, the class, method, or data member is accessible only within the same package

### Private
Methods or data members using the 'private' keyword are accessible only within the class in which they are declared
Any other class of the same package will not be able to access these members
Top level classes orr interfaces can not be declared as private because:
    - private means "only visible within the enclosing class"
    - protected means "only visible withing the enclosing class and any subclasses"

### Protected
Methods or data members declared as protected are accessible within the same package or subclasses in different packages

### Public
Methods or data members declared as public are accessible from everywhere in the program.
There is no restriction on the scope of public data members.


### General Rule of Thumb
Use the private access modifier unless you have a good reason not to.