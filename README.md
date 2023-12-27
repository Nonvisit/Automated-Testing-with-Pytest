# Automated-Testing-with-Pytest
Develop automated tests for a Python module using Pytest.
# Sample Python module (e.g., calculator.py)
def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

# Pytest test script (e.g., test_calculator.py)
import calculator

def test_add():
    assert calculator.add(3, 5) == 8
    assert calculator.add(-1, 1) == 0

def test_subtract():
    assert calculator.subtract(5, 3) == 2
    assert calculator.subtract(-1, -1) == 0
