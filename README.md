def adicionar (a, b):
    return a + b
def subtrair (a, b):
    return a - b
def multiplicar (a, b):
    return a * b
def dividir (a ,b):
    return a / b if b != 0 else "erro"

def calculadora ():
    print ("-" * 30)
    print ("Calculadora Simples")
    print ("-" * 30)
    print ("1- adicionar")
    print ("2- subtrair")
    print ("3- multiplicar")
    print ("4- dividir")
    print ("5- sair")
    while True:
        opcao = input("escolha uma opção de 1 a 5: ")
        if opcao == "1":
            num1 = float(input("Adicione um numero: "))
            num2 = float(input("Adicione um numero: "))
            print(f"resultado: {adicionar (num1, num2)}")
        elif opcao == "2":
            num1 = float(input("Adicione um numero: "))
            num2 = float(input("Adicione um numero: "))
            print(f"resultado: {subtrair (num1, num2)}")
        elif opcao == "3":
            num1 = float(input("Adicione um numero: "))
            num2 = float(input("Adicione um numero: "))
            print(f"resultado: {multiplicar (num1, num2)}")
        elif opcao == "4":
            num1 = float(input("Adicione um numero: "))
            num2 = float(input("Adicione um numero: "))
            print(f"resultado: {dividir (num1, num2)}")
        elif opcao == "5":
            print ("encerrando")
            break
        else:
            print("opção inválida")
            
calculadora()
