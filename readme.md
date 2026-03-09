

Qus.1.What is the difference between var, let, and const?

Ans: ✅ var

       1. Old way to declare variables (before ES6)

       2. Function scoped (not block scoped)

       3. Can be redeclared

    ✅ let
        
        1 Introduced in ES6

        2 Block scoped

        3 Can be updated

    ✅ const

       1 Introduced in ES6

       2 Block scoped

       3❌ Cannot be redeclared


Qus.2. What is the spread operator (...)?

    Ans:✅ Copy arrays(const a = [1,2,3];
                        const b = [...a];)
        ✅ Merge arrays (const a = [1,2];
                            const b = [3,4];
                            const c = [...a, ...b];)
        ✅ Copy objects
        ✅ Add/override object properties




Qus.3 What is the difference between map(), filter(), and forEach()?

    Ans:✅map()

        1. Transforms each element
        2. Returns a new array (same length)

        ✅filter()

       1. Selects elements that match a condition
        2. Returns a new array (may be shorter)
        
        
        ✅forEach()

        1. Runs a function for each element
        2. ❌ Returns nothing (undefined)
        3. Used for side effects (logging, updating UI, etc.)


Qus.4 What is an arrow function?

    Ans: A shorter way to write functions (introduced in ES6).

        Key Features
        ✅Shorter syntax
        ✅If one parameter → no parentheses needed
        ✅If one expression → no return needed

            Arrow function
        const add = (a, b) => a + b;


Qus.5 What are template literals?
 
    Ans: Template literals are strings written with backticks (`) that allow:

        ✅String interpolation
        ✅Multi-line strings
        ✅Expressions inside strings