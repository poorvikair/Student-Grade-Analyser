# Student-Grade-Analyser
Module 1 Project: Student Grade Analyser
You have learned how to create NumPy arrays, slice them, apply operations, and use mathematical functions. Now put those skills together.

You will build a grade analyser for two exam classes. Tools like this power gradebooks, academic dashboards, and automated reporting systems.

This project has three parts. Your code carries forward between parts — what you build in Part 1 is the foundation for Part 2 and Part 3.
Student Grade Analyser
Create grade arrays for two classes and print the mean, max, and min score for each.
In this part you will

Import NumPy as np
Create two arrays: class_a and class_b with the scores provided in the starter code
Print each class's mean (1 decimal place), max, and min using np.mean, np.max, np.min
Example output

Class A stats:
  Mean:  78.2
  Max:   96
  Min:   55
Class B stats:
  Mean:  75.4
  Max:   93
  Min:   45
Apply a +5 mark curve to all scores (capping at 100) and print a full letter grade distribution.
In this part you will

Keep all output from Part 2
Apply a +5 curve to the combined array using np.minimum(combined + 5, 100)
Count how many curved scores fall into each band: A (>=90), B (75–89), C (60–74), F (<60)
Print the grade distribution table and the new mean (1 decimal place)
Example output

Class A stats:
  Mean:  78.2
  Max:   96
  Min:   55
Class B stats:
  Mean:  75.4
  Max:   93
  Min:   45
Class A: 9/10 passed
Class B: 9/10 passed
Combined mean: 76.8
Top score overall: 96
Grade distribution after +5 curve:
  A (90-100): 7
  B (75-89):  8
  C (60-74):  4
  F (<60):    1
New mean: 81.8
