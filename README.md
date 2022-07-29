# Projetos-feitos-no-Python
#Calculadora Python

#Calculadora em Python

print("\n******* Calculadora Python*******")
print("\n Selecione o número da operação desejada:")
print("\n 1 - Soma")
print(" 2 - Subtração")
print(" 3 - Multiplicação")
print(" 4 - Divisão ")

opcao_de_operação = int(input(" \n Digite sua opção: (1/2/3/4): "))
x = float(input("Digite o primeiro número: "))
y = float(input("Digite o segundo número: "))

def soma(x,y):
    print( x,"+", y, "=",x + y)
    return
def subtracao(x,y):
    print( x,"-", y, "=",x-y)
    return
def multiplicacao(x,y):
    print( x,"*", y, "=",x*y)
    return
def divisao(x,y):
    print( x,"/", y, "=",x/y)
    return

if opcao_de_operação == 1:
    soma(x,y)
elif opcao_de_operação == 2:
    subtracao(x,y)
elif opcao_de_operação == 3:
    multiplicacao(x,y)
elif opcao_de_operação == 4:
    divisao (x,y)
else:
    print("Opção Inválida")
