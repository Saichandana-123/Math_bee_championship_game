ICS MAJOR PROJECT
MATHBEE SIMULATOR-(A Math Adventure)
The Math Bee Championship Simulator is a simple program written in C that simulates a math bee 
competition. In this competition, participant is  asked a series of math questions.
There are mainly 4 levels Based on level of difficulty  and at the beginning of the game, the player
is prompted to select a difficulty level from the options: EASY, MEDIUM, DIFFICULT, or EXPERT.
In the code we defined  functions to generate each question in the each level. As the levels
progress, users are challenged with increasingly complex mathematical concepts
Rules for Playing the game :
A player is permitted to engage only in the level they have selected.
Score:
Easy Level: This level consists of 5 questions. Each correct answer awards 30 points, while incorrect answers yield no points.
Medium Level: This level also presents 5 questions, but each correct answer is worth 50 points.
Difficult Level: This level has 4 questions, with each correct answer granting 65 points.
Expert Level: In this level, each correct answer is rewarded with 85 points.

Concepts of C programming language  Used :
Conditional statements,Functions,pointers,strings,arrays,loops,2 inbuilt functions srand,rand and beep
Type of Questions:
1.Arithmetic Operations: Basic operations like addition and subtraction are executed using loops to
iterate through the digits of the numbers, add or subtract corresponding digits, and manage carries 
or borrows.

2.Area Calculations: To compute the area of various geometric shapes, specific functions for each
shape are implemented. For instance, the function calculateRectangleArea() is defined to compute the
area of a rectangle using length and width as parameters.

3.Unit Conversion: Functions are defined to convert units. For example, convertKilogramsToGrams()
takes weight in kilograms and returns the equivalent weight in grams. Each function accepts the value 
to be converted, applies the conversion formula, and returns the result.

4.BODMAS Expression Evaluation: The expression is broken down into tokens (operands and operators) 
for processing. Stacks are used to manage operators and operands during evaluation, following the
BODMAS rule. The expression tokens are iterated through, evaluating sub-expressions according to the
BODMAS rule.

5.Arithmetic and Geometric Progression Problem Solving: The type of progression (AP or GP) is
identified based on the pattern of terms. Formulas are used to calculate the nth term and the sum of
the first n terms for both AP and GP. Separate functions are implemented for these calculations.

6.Quadratic Equation Solving: Two integers representing the sum and product of the roots of the
quadratic equation are accepted. The coefficients of the quadratic equation are calculated using 
these roots, and the discriminant is computed to determine the nature of the roots. The roots are
then computed based on the value of the discriminant and displayed.

7.Riddle Questions Generation: A riddle is randomly selected from a collection and presented to the
user. The user’s answer is validated against the stored answer for the selected riddle, and feedback
is provided based on the correctness of the user’s answer.

8.Pattern Printing: User-defined parameters such as the number of rows and columns are accepted to
determine the pattern’s size and shape. Nested loops are used to iterate through the pattern’s
elements, and specific patterns are generated using conditional statements or mathematical
calculations. The pattern is displayed to the user with potential enhancements like borders, colors,
or additional shapes.

9. Probability Calculations: The function probability(int *score) generates a random probability
question from a predefined list, prompts the user for an answer, and checks the user's answer against
 the correct answer. If the user's answer is within an acceptable tolerance, the user's score is
 increased. If the user's answer is incorrect, the correct answer and an explanation are provided.

10. Integration Calculations: The function calculate_integral(double parameters[], int value)
calculates the integral of a polynomial function. The polynomial's coefficients are stored in an
  array, and the function iterates over these coefficients to compute the integral.

11. Differentiation Calculations: The function calculate_derivative_coefficients(int coefficients[],
 int derivative[]) calculates the coefficients of the derivative of a polynomial function. The
function iterates over the coefficients of the original polynomial, multiplies each coefficient by
 its corresponding power, and stores the result in the derivative array.

12. Unit Place Digit in Power Calculation: The function generate_question(int *score) generates a
 random base and exponent, calculates the last digit of the base raised to the exponent, and prompts
the user to guess this digit. If the user's guess is correct, their score is increased. If the user's
 guess is incorrect, the correct answer is provided.

BUZZER SOUND USED IN PROJECT: when displaying the incorrect answer there is a sound that is played so that the user gets to know it. 

Instructions to run:
Code Editor: You will need a code editor to work with the project files. We recommend using Visual Studio Code for its excellent support for various programming languages and extensions.

Compiling Tool: The project is developed using the C programming language, so you will need a C compiler to build and run the code. We suggest using the GNU Compiler Collection (GCC), which is widely used and available on most platforms.

Group members :
1.Penmetsa Navyasri (B23CS1052)
2.Karuturi Sumasri (B23CI1018)
3.MeMeejuru Lakshmi Sowmya(B23CM1024)
4.Tumma Sai chandana(B23EE1077)
