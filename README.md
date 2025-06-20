# programas-que-suma-y-resta-
def suma(a, b):
    return a + b

def resta(a, b):
    return a - b

if __name__ == "__main__":
    print("Programa que suma y resta dos números.")
    num1 = float(input("Introduce el primer número: "))
    num2 = float(input("Introduce el segundo número: "))
    
    print(f"La suma de {num1} y {num2} es: {suma(num1, num2)}")
    print(f"La resta de {num1} y {num2} es: {resta(num1, num2)}")
