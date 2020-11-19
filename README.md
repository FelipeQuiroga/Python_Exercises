# Python_Exercises
####PEDRA PAPEL TESOURA!!####
from time import sleep
import random
print("Suas opções: ")
print("[ 0 ] PEDRA ")
print("[ 1 ] PAPEL ")
print("[ 2 ] TESOURA ")
opção = int(input("Qual sua jogada? "))
print("JO")
sleep(0.5)
print("KEN")
sleep(0.5)
print("PO!!!")
sleep(0.5)

computador = ['pedra', 'papel', 'tesoura']
jogada = random.choice(computador)

print("-="*13)
print("Computador jogou {}".format(jogada.capitalize()))
###y = len(x)
###print("O comprimento da frase x é {}".format(y))
if opção == 0:
    print("Jogador jogou Pedra")
elif opção == 1:
    print("Jogador jogou Papel")
elif opção == 2:
    print("Jogador jogou Tesoura")
print("-="*13)
sleep(0.5)
if jogada == "pedra" and opção == 0:
    print("EMPATE")
elif jogada == "pedra" and opção == 1:
    print("Jogador VENCE")
elif jogada == "pedra" and opção == 2:
    print("Jogador PERDE\nA MAQUINA GANHA DO HOMEM MAIS UMA VEZ")
elif jogada == "papel" and opção == 0:
    print("Computador VENCE\nA MAQUINA GANHA DO HOMEM MAIS UMA VEZ")
elif jogada == "papel" and opção == 1:
    print("EMPATE!!!")
elif jogada == "papel" and opção ==2:
    print("Jogador VENCE")
elif jogada == "tesoura" and opção == 0:
    print("Jogador VENCE")
elif jogada == "tesoura" and opção == 1:
    print("Computador VENCE\nA MAQUINA GANHA DO HOMEM MAIS UMA VEZ")
elif jogada == "tesoura" and opção == 2:
    print("EMPATE!!!!")
