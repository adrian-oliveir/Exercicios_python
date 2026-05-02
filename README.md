# Exercicios_pytho
Esses são os meus exercícios em python para praticar minha lógica de programação.

1) Escreva um algoritmo em Python para calcular a idade de
alguém, sabendo-se seu ano de nascimento.

Resposta:
ano_nascimento = int(input("digite seu ano de nascimento:"))
ano_atual = int(input("digite o ano atual:"))
idade = ano_atual - ano_nascimento
idade_meses = idade * 12
print("Essa é a sua idade:", idade, "e essa é a sua idade em meses:", idade_meses)

2) Escreva um algoritmo em Python para calcular o valor, em
reais, que deve ser pago por um cliente de uma locadora de
carros. Sabe-se que:
• O valor de locação de cada carro é 100,00 reais;
• O cliente pode locar um único carro por vários dias.

Resposta:
selecao_carro = int(input("Selecione quanto carros você deseja alugar: "))
selecao_dias = int(input("Selecione por quantos dias você deseja alugar: "))
multiplicacao = selecao_carro * selecao_dias
multiplicacao2 = multiplicacao * 100
print("O valor que você vai pgar é:", multiplicacao2)



