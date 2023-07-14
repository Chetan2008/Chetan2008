class Calculator:
    def add(self, a, b):
        return a + b

    def subtract(self, a, b):
        return a - b

    def multiply(self, a, b):
        return a * b

    def divide(self, a, b):
        if b != 0:
            return a / b
        else:
            return "Cannot divide by zero"


# Example usage
calculator = Calculator()
print(calculator.add(5, 3))
print(calculator.subtract(5, 3))
print(calculator.multiply(5, 3))
print(calculator.divide(5, 3))
