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
    print(f"La resta de {num1} y {num2} es: {resta(num1, num2)}")def multiplicar(a, b):
    return a * b

def dividir(a, b):
    if b == 0:
        return "No se puede dividir por cero."
    return a / b

def main():
    print("Elija una operación:")
    print("1. Multiplicar")
    print("2. Dividir")
    opcion = input("Ingrese su opción (1/2): ")

    a = float(input("Ingrese el primer número: "))
    b = float(input("Ingrese el segundo número: "))

    if opcion == '1':
        resultado = multiplicar(a, b)
        print(f"Resultado: {a} * {b} = {resultado}")
    elif opcion == '2':
        resultado = dividir(a, b)
        print(f"Resultado: {a} / {b} = {resultado}")
    else:
        print("Opción inválida.")

if __name__ == "__main__":
    main()
