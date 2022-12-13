from math import log2
from random import randint
while True:
    vezes = 0
    menor = int(input('digite o menor número do intervalo: '))
    maior = int(input('digite o maior número do intervalo: '))
    chances = int(log2(maior - menor + 1))
    sorte = randint(menor, maior)
    print(f'Você tem {chances} chances para acertar')
    while True:
        if vezes == chances:
            print('Infelizmente, suas chances acabaram, mais sorte da próxima')
            break
        tentativa = int(input('digite sua tentativa: '))
        if tentativa == sorte:
            print(f'Parabéns você ganhou depois de {vezes+1} tentativa(s)')
            break
        else:
            print('Tente novamente, você adivinhou um número muito baixo') if tentativa < sorte else print('Tente novamente, você adivinhou um número muito alto')
        vezes+=1
    if input('''.
.
você deseja jogar dnv? [s/n] ''').lower() == 's':
        print('-='*20)
        print('      [Bem-vindo(a) de volta]')
        print('-='*20)
    else:
        print('''.
.
Muito obrigada por jogar, esperamos que tenha gostado!!''')
        break
