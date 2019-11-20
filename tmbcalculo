genero = input('"1" para Homem ou "2" para Mulher: ')
nome = input('Digite seu nome: ')
idade = input('Digite sua idade: ')
altura = input('Digite sua altura(Em Centimetros): ')
peso = input('Digite seu peso: ')
tmbhomem = ''
tmbmulher = ''
atividade0 = ''
atividade1 = ''
atividade2 = ''

if genero == '1':
    tmbhomem = 66 + 13.7 * int(peso) + 5 * int(altura) - 6.8 * int(idade)
    print('\n*****************************************************************************')
    print(f'Olá {nome}! ')
    print(f'Sua Taxa de metabolismo basal é {tmbhomem:.2f}.')
    atividade0 = (tmbhomem * 0.25) + tmbhomem
    atividade1 = (tmbhomem * 0.35) + tmbhomem
    atividade2 = (tmbhomem * 0.45) + tmbhomem
    print(f'Necessidade calorica sem praticar nenhuma atividade fisica: {atividade0:.2f}')
    print(f'Necessidade calorica praticando atividade fisica MODERADA: {atividade1:.2f}')
    print(f'Necessidade calorica praticando atividade fisica INTENSA: {atividade2:.2f}')
    print('\n')
    print('Atividade MODERADA: Meia hora de caminhada por dia 4 vezes por semana')
    print('Atividade INTENSA: Uma hora de caminhada por dia pelo menos 4 vezes por semana')
    print('\n******************************************************************************')

elif genero == '2':
    tmbmulher = (655 + (9.6 * int(peso)) + (1.7 * int(altura)) - (4.7 * int(idade)) )
    print('\n******************************************************************************')
    print(f'Olá {nome}! ')
    print(f'{tmbmulher:.2f} é sua taxa de metabolismo basal')
    atividade0 = (tmbmulher * 0.20) + tmbmulher
    atividade1 = (tmbmulher * 0.30) + tmbmulher
    atividade2 = (tmbmulher * 0.40) + tmbmulher
    print(f'Necessidade calorica sem praticar nenhuma atividade fisica: {atividade0:.2f}')
    print(f'Necessidade calorica praticando atividade fisica MODERADA: {atividade1:.2f}')
    print(f'Necessidade calorica praticando atividade fisica INTENSA: {atividade2:.2f}')
    print('\n******************************************************************************')
    print('Atividade MODERADA: Meia hora de caminhada por dia 4 vezes por semana')
    print('Atividade INTENSA: Uma hora de caminhada por dia pelo menos 4 vezes por semana')
