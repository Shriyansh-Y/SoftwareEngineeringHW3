# HW4
Software Engineering HW4 on Complexity


Complete and extend the workshop to solve the following measures:

1. Do a simple calculations (50 points)

   Per Function:

   * **ParameterCount**: The number of parameters for function.
   * **Returns**: The number of return statements in function. 

   For File:
 
   * **AllConditions**: The total number of conditions in file.
   * **String Usage**: How many string literals are used in file.
   * **PackageComplexity**: The number of imports used in file.

2. Using multiple visitors (50 points).

   * **SimpleCyclomaticComplexity**: The number of if statements/loops + 1.
   * **MaxMessageChains**: The max length of a message chain in a function. A message chain can be formed from a method call (), a data access (.), or array access [n].
     For example, 
     
     ```
     // Message Chain: 4
     mints.name.toString().split(".")[0];
     ``` 
