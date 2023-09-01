from fractions import Fraction
total_outcomes = 6 * 6
favorable_outcomes = 0
for die1 in range(1, 7):
    for die2 in range(1, 7):
        if die1 != die2 and die1 + die2 == 6:
            favorable_outcomes += 1
probability = Fraction(favorable_outcomes, total_outcomes)
print(probability)
