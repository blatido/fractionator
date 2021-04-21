# fractionator

Command line app to perform basic operations (add, substract, divide, multiply) with fractional numbers.

This app iw written using C# language. To run it, create a new NET console app using Visual Studio or VS Code, then copy & paste the code in Program.cs file. This file contains the Main procedure and all needed code to run.

The syntax to use the console app is basically

? numerator/denominator operand whole_numerator/denominator

where the ? character followed by a single space is required. Numerator and Denominator are integer numbers separated by a / sign. Whole is an optional integer number, and must be separated by a _ sign. Operand must be any of these signs: +, -, * or / and must be separated by a single space before and after.

Examples:

? 1/2 + 1/7
? 3_4/6 / 2_1/5
? 3/7 * 3_1/9
