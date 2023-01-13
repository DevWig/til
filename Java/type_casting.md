# Java Type Casting

Type casting is when you assign a value of one primitive data type to another type.

In Java, there are two types of casting:

    1. Widening Casting
        - happens automatically (no keywords needed)
        - converting a smaller type to a larger type
        - byte > short > char > int > long > float > double

    2. Narrowing Casting
        - must be done manually

            * done by placing the type in parenthesis in front of the value

        - converting a larger type to a smaller type
        - double > float > long > int > char > short > byte
    
#### Example of Narrowing Casting
    ```java
    List listOfItems = ["apple", "pear", "orange"];
    ArrayList arrayListofItems = (ArrayList)listOfItem;
    ```