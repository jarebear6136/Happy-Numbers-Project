C# READ-ME FILE

TO COMPILE: mcs Program.cs
TO RUN: mono Program.exe


OUTPUT EXAMPLES:
  a) 10-30
    First Argument: 10
    Second Argument: 30
    19
    28
    23
    13
    10

  b) 200-50 (with swap of course)
    First Argument: 50
    Second Argument: 200
    188
    193
    190
    192
    139
    176
    167
    133
    94
    129

  c)410-430 (Nobody's happy example)
    First Argument: 410
    Second Argument: 430
    NOBODIES HAPPY!
    
    
METHODS
  MAIN:
    1.declare data structures to store normed values (List of type Double), and a dictionary for storing and sorting the map (dictionary of types Double (key) and Integer (value)
    2. obtain user input (firstNum and secondNum).
    3. swap the values if firstNum is greater than the secondNum.
    4. adding normedvalues to treemap and it does the math for them (forloop), starts by checking if a number isHappy then do the math for it. It adds it to the dictionary then clears normedValues. After that call the print reverse treemap method.
      
  sumDigitSquare:
      1. sumDigitSquare does math to calculate if a number is a happy number.
    
    isHappy:
      1. Uses a hash set and checks if the values are happy-numbers based off of sumDigitSquare math calculations.
    
    breakdown:
      1. Breakdown method breaks down the happy numbers and calculates the normed values for them.
      
    printReverseTreeMap:
      1. Iterates through the dictionary and prints it in descending order.
      2. It also will check if the tree map is empty and prints "NOBODIES HAPPY!" if the values entered are not happy numbers.