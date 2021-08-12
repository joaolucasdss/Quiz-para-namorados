# Defining Score variables
import time

x = 0
score = x
print('=-=' * 50)
print('QUIZ DE NAMORO')
print('=-=' * 50)
print('Este quiz avaliará seus conhecimentos acerca desse namoro com 10 questões')
print(
    'Eis os baremas:\n10 acertos: Iguaria sem lactose\n9 acertos: Ticket de ida ao Açai \n8 acertos: Batata frita do McDonalds\n'
    '7 acertos: Ticket Oggi\nAbaixo de 6 acertos deverá me dar um beijo')
print('Você terá 10 segundo para responder as questões')
print()
print("=-=" * 50)
input(str('Está pronta para começar? '))
print('')

# Question One
print("Onde demos nosso primeiro beijo?")
start = time.time()
equ = input("(a)Sala\n(b)Carro\n(c)Garupa da moto\n(d)Quarto\n:")
end = time.time()
answer_1 = "b"
if end - start >= 10:
    print('Demorou!')
elif equ == answer_1:
    print('Correto!')
    x = x + 1
else:
    print('Errado, foi no carro! Não me ama mais?')
print('=-=' * 30)

# Question Two
print("Qual foi o primeiro ambiente familiar onde nos vimos?")
start = time.time()
equ = input("(a)Sua casa\n(b)Minha casa\n(c)Casa da minha avô\n:")
end = time.time()
answer_2 = 'a'
if end - start >= 10:
    print('Demorou!')
elif equ == answer_2:
    print('Correto!')
    x = x + 1
else:
    print("Errado! Como podes esquecer disso?!")
print('=-=' * 30)

# Question Three
print("O que mais comemos quando nos vemos?")
start = time.time()
equ = input("(a)Açai\n(b)Pipoca\n(c)Sorvete\n(d)McDonalds\n(e)Pizza\n:")
end = time.time()
answer_3 = 'b'
if end - start >= 10:
    print('Demorou!')
elif equ == answer_3:
    print('Correto!')
    x = x + 1
else:
    print("Errado! Não valoriza os momentos comigo?")
print('=-=' * 30)

# Question Four
print("Quantos dias temos de namoro?")
start = time.time()
equ = input("(a)1460\n(b)1561\n(c)1461\n(d)1200\n(e)1350\n:")
end = time.time()
answer_4 = 'c'
if end - start >= 10:
    print('Demorou!')
elif equ == answer_4:
    print('Correto!')
    x = x + 1
else:
    print("Errado! Além de não me amar nã sabe fazer conta!")
print('=-=' * 30)

# Question Five
print("Qual o primeiro lugar que saímos para comer?")
start = time.time()
equ = input("(a)Pizzaria\n(b)Hamburgueria\n(c)Churrascaria\n(d)Lanchonete\n:")
end = time.time()
answer_5 = 'd'
if end - start >= 10:
    print('Demorou!')
elif equ == answer_5:
    print('Correto!')
    x = x + 1
else:
    print("Errado! Que valor tem nossas memórias para você?")
print('=-=' * 30)

# Question six
print("Desde o inicio do namoro qual a média de dias que nos vemos por semana?")
start = time.time()
equ = input("(a)5 dias\n(b)3 dias\n(c)4 dias\n(d)2 dias\n(e)6 dias\n:")
end = time.time()
answer_6 = 'b'
if end - start >= 10:
    print('Demorou!')
elif equ == answer_6:
    print('Correto!')
    x = x + 1
else:
    print("Errado! Nossos momentos diários são irrelevantes?")
print('=-=' * 30)

# Question seven
print("Qual desses itens nunca foi dado como presente?")
start = time.time()
equ = input("(a)Perfume\n(b)Papéis\n(c)Chocolate\n(d)Jóia\n(e)Caneta\n:")
end = time.time()
answer_7 = 'e'
if end - start >= 10:
    print('Demorou!')
elif equ == answer_7:
    print('Correto!')
    x = x + 1
else:
    print("Errado! Vou pegar os presentes que dei de volta")
print('=-=' * 30)

# Question 8
print("Quantas viagens já fizemos juntos?")
start = time.time()
equ = input("(a)1\n(b)2\n(c)3\n(d)4\n(e)5\n:")
end = time.time()
answer_8 = 'c'
if end - start >= 10:
    print('Demorou!')
elif equ == answer_8:
    print('Correto!')
    x = x + 1
else:
    print("Errado! Com quem você andou viajando??")
print('=-=' * 30)

# Question 9
print("Que barreira natural pulamos na viagem para a ilha?")
start = time.time()
equ = input("(a)Córrego de água\n(b)Monte de areia\n(c)Pilha de blocos\n(d)Onda\n(e)Montanha\n:")
end = time.time()
answer_9 = 'a'
if end - start >= 10:
    print('Demorou!')
elif equ == answer_9:
    print('Correto!')
    x = x + 1
else:
    print("Errado! Venha pular em cima de mim")
print('=-=' * 30)

# Question 10
print("Quais os destinos de viagem primariamente expostos em nosso namoro?")
start = time.time()
equ = input("(a)Luxemburgo e Los Angeles\n(b)Paris e Londres\n(c)Bariloche e Gramado\n(d)Reykjavik e Machu Picchu\n(e)Machu Picchu e Yelatski\n:")
end = time.time()
answer_10 = 'd'
if end - start >= 10:
    print('Demorou!')
elif equ == answer_10:
    print('Correto!')
    x = x + 1
else:
    print("Errado! Decida para onde de uma vez por todas!")
print('=-=' * 30)
print('=-=' * 30)

# Total Score
score = float(x / 10) * 100
print('Você acertou', x, "de 10, sua porcentagem de acerto foi", score, "%")
print('=-=' * 30)

#Rewards
if score == 100:
    print('Parabéns! Você ganhou todos os prêmios!')
elif score == 90:
    print("Você não foi 100% mas foi bem, ganhou o ticket do Mcdonald's, do Açai e da Oggi.")
elif score ==80:
    print('Você teve um desempenho razoável, ganhou o ticket do Açai e da Oggi.')
elif score ==70:
    print('Você foi bem mais ou menos, ganhou apenas o ticket da Oggi.')
else:
    print('Sua performance decepcionou, você que terá que me presentear com um beijo.')

