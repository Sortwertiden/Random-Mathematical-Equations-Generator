# Random-Mathematical-Equations-Generator
Generate random mathematical equations for practice.
import random

def generate_math_equation():
    a = random.randint(1, 10)
    b = random.randint(1, 10)
    operator = random.choice(['+', '-', '*', '/'])
    equation = f"{a} {operator} {b}"
    return equation

math_equation = generate_math_equation()
print("Random Math Equation:", math_equation)
