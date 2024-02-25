# github-test
git clone https://github.com/your-username/my-oss-project.git
# calculator.py

def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        raise ValueError("Division by zero is not allowed")
    return a / b
    git add calculator.py
git commit -m "Add basic calculator functions"
git push origin master
