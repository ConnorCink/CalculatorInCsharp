# CalculatorInCsharp
Made a calculator in C#

To activate:
  Input two numbers, then select a simple operation.
  
Guts:
  Uses a method for each operation, string conversion is validated by a validator method using int32.TryParse. The operation is selected via a switch within a while loop, so that the default represents an incorrect input and restarts the loop.
