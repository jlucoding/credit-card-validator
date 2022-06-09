Describe: luhnAlgorithm()

Test 1: "It should return 0 if the number is 0."
Code:
const number = 0;
luhnAlgorithm(number);
Expected Output: 0

Test 2: "It should double the digit if the number is not 0."
Code:
const number = 1;
luhnAlgorithm(number);
Expected Output: 2

Test 3: "It should take multiple digits and double all digits separately."
Code:
const number = 123;
luhnAlgorithm(number);
Expected Output: 246

Test 4: 
Code:
Expected Output: