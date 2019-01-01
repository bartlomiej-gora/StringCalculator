# StringCalculator
StringCalculator for TDD workshops


<b>Before you start:<br>
Try not to read ahead.<br>
Do one task at a time. The trick is to learn to work incrementally.<br></b><br>
Make sure you only test for correct inputs. there is no need to test for invalid inputs for this kata
This kata is one of the simplest and best ways to practice step-by-step fluent tdd, and provides an easy way to get proficient in a language.

Write a method add under an object StringCalculator that, given a delimited string, returns the sum of the numbers in the string.

1. An empty string returns zero '' => 0
2. A single number returns the value '1' => 1 '2' => 2
3. Two numbers, comma delimited, returns the sum '1,2' => 3 '10,20' => 30
4. Two numbers, newline delimited, returns the sum '1\n2' => 3
5. Three numbers, delimited either way, returns the sum '1\n2,3\n4' => 10
6. Negative numbers throw an exception with the message '-1,2,-3' => 'negatives not allowed: -1,-3'
