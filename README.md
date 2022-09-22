<img src = "gif bob.gif" width = "325px">

#😎 Seja bem vindo ao meu Github criado para armazenar o script da Atividade Extensionista || 

- Estudante De Gestão De T.I na Uninter

- Conta criada para entrega de trabalho 

nome = (input('Nome da criança:'))
idade = int(input('Idade:'))
if idade <= 5:
    ensino = 'educação infantil'
    print('O(A) aluno(a) {} possui {} ano(s) e está no {}'.format(nome,idade,ensino))
if 6 <= idade and idade <= 10:
    ensino = 'ensino fundamental |'
    print('O(A) aluno(a) {} possui {} ano(s) e está no {}'.format(nome, idade,ensino))
if 11 <= idade and idade <= 14:
    ensino = 'ensino fundamental ||'
    print('O(A) aluno(a) {} possui {} ano(s) e está no {}'.format(nome, idade,ensino))
if idade >= 15:
    ensino = 'ensino médio'
    print('O(A) aluno(a) {} possui {} ano(s) e está no {}.'.format(nome, idade,ensino))
continuar = int(input('Deseja continuar? \nDigite 1 para Sim \nDigite 2 para Não \n:'))
while(continuar == 1):
    nome = (input('Nome da criança:'))
    idade = int(input('Idade:'))
    if idade <= 5:
        ensino = 'educação infantil'
        print('O(A) aluno(a) {} possui {} ano(s) e está no {}'.format(nome, idade, ensino))
    if 6 <= idade and idade <= 10:
        ensino = 'ensino fundamental |'
        print('O(A) aluno(a) {} possui {} ano(s) e está no {}'.format(nome, idade, ensino))
    if 11 <= idade and idade <= 14:
        ensino = 'ensino fundamental ||'
        print('O(A) aluno(a) {} possui {} ano(s) e está no {}'.format(nome, idade, ensino))
    if idade >= 15:
        ensino = 'ensino médio'
        print('O(A) aluno(a) {} possui {} ano(s) e está no {}.'.format(nome, idade, ensino))
    continuar = int(input('Deseja continuar? \nDigite 1 para Sim \nDigite 2 para Não \n:'))


print('=^.^=')
print('HOTEL DOS ANIMAIS')
print('Especificando posição')
print('[1,2,3,4]')
print('[5,6,7,8]')
print('Fase 1')
hotel = [['*','*','-','G'],['R','-','*','*']]
for linha in hotel:
    print(linha)
posrato = int(input('Qual casa deseja colocar o rato:'))
posgato = int(input('Qual casa deseja colocar o gato:'))

while True:
 if (posgato == 4 and posrato == 5):
  print('Você venceu,próxima fase!')

  print('Fase 2')
  hotel = [['-', '*', '*', '*'], ['*', 'C', '-', '-']]
  for linha in hotel:
      print(linha)
  poscão = int(input('Qual casa deseja colocar o câo:'))
  pososso = int(input('Qual casa deseja colocar o osso:'))
  while True:
    if (poscão == 1 and pososso == 8):
      print('Você venceu!Próxima fase!')

      print('fase 3')
      hotel = [['-', '*', '*', '*'], ['-', 'G', '-', '-']]
      for linha in hotel:
          print(linha)
      posrat = int(input('Qual casa deseja colocar o rato:'))
      pososso = int(input('Qual casa deseja colocar o osso:'))
      while True:
        if (posrat == 1 and pososso == 5 or pososso == 8):
            print('Você venceu!,próxima fase!')

            print('fase 4')
            hotel = [['-', '-', '-', '*'], ['*', 'R', '*', '*']]
            for linha in hotel:
                print(linha)
            posqueijo1 = int(input('Qual casa deseja colocar o 1° queijo?'))
            posqueijo2 = int(input('Qual casa deseja colocar o 2° queijo?'))
            pososso = int(input('Qual casa deseja colocar o osso?'))
            while True:
             if (posqueijo1 == 1 or posqueijo1 == 3 and posqueijo2 == 3 or posqueijo2 == 1 and pososso == 2):
               print('Você venceu o jogo, parabéns!!')
             else:print('Game over!')
             break
        else:print('Game over!')
        break
    else:print('Game over!')
    break
 else:print('Game over!')
 break


print('Encerrando o programa...')





def converter(x):
     if (x == 'A'):
         return '@'
     if (x == 'E'):
         return '&'
     if (x == 'I'):
         return x.replaceAll(['I'],['!'])
     if (x == 'O'):
         return '#'
     if (x == 'U'):
         return '*'
nome = input('Qual seu nome?')
x = print(list(nome.upper()))
converter(x)


nome = input('Qual seu nome?')
def converter():
 if(list(nome.upper()) == 'A'):
  quero_trocar = "A"
  trocar_por = "@"
  frase = list(nome.upper()).replaceAll(quero_trocar, trocar_por,len((list(nome.upper()))))
  print(frase)
converter()

nome = input('Qual seu nome?')
nome = nome.upper()
def troca(quero_trocar, trocar_por, nome):
    nova = []
    for c in nome:
        if c == quero_trocar:
            nova.append(trocar_por)
        else:
            nova.append(c)

    return ''.join(nova)

s1 = print(troca('A', '@', nome))



nome = input('Qual seu nome?')
def converter(nome):
    if (list(nome.upper()) == 'A'):
        return '@'
    if (list(nome.upper()) == 'E'):
        return '&'
    if (list(nome.upper()) == 'I'):
        return '!'
    if (list(nome.upper()) == 'O'):
        return '#'
    if (list(nome.upper()) == 'U'):
        return '*'
print(converter(nome))



