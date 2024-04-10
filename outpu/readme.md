codigo criado pela IA - calculadora em python

def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b != 0:
        return a / b
    else:
        return "Error: Division by zero"

# Exemplo de uso
num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))
operation = input("Escolha a operação (+, -, *, /): ")

if operation == "+":
    result = add(num1, num2)
elif operation == "-":
    result = subtract(num1, num2)
elif operation == "*":
    result = multiply(num1, num2)
elif operation == "/":
    result = divide(num1, num2)
else:
    result = "Operação inválida"

print(f"Resultado: {result}")

Você pode executar esse código em um ambiente Python (como o IDLE ou Jupyter Notebook) para testá-lo. Lembre-se de substituir os valores de num1 e num2 pelos números que deseja calcular.

