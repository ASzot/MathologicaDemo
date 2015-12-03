# MathologicaDemo

A simple demo program showing the usage of the Mathologica math evaluation library.

Refer to Program.cs for a generic method of parsing any mathematical expression, presenting the user with a list of evalauation options, and then evaluating the input based on the user's evaluation option selection. This is the same concept of the website application of Mathologica and shows the functioning of the program at a very high level. 

In MathTest.cs is more in depth examples of how Mathologica can be used to represent and manipulate mathematical expressions. At the core of the library is **ExComp** which is any mathematical symbol such as a variable, number, function, or any group of expressions. **AlgebraTerm** is a group of the **ExComp** data type. Due to this abstracted representation any mathematical expression can be represented using the **AlgebraTerm**. To handle equations where equality or inequality signs are used the **EqSides** object is used. This object incorperates multiple **AlgebraTerm** objects equated by some form of comparison sign to form an equation. Simultaneous equations can also be represented in **EqSet**. 

The source code powering Mathologica has not been posted and will not be anytime in the future. For any inquires on using the Mathologica library contact me. 

To see a part of how Mathologica works check AntiDerivativeHelper.cs. The source code in this file demonstrates the flexibility of the Mathologica system and how it can be used to complete the complex process of taking an anti-derivative. 

The program in action can be found at http://mathologica.com/
