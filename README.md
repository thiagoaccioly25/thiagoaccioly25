<img src = "gif bob.gif" width = "325px">

#😎 Seja bem vindo ao meu Github criado para armazenar o script da Atividade Extensionista || 

- Estudante De Gestão De T.I na Uninter

- Conta criada para entrega de trabalho 

nome = (input('Nome da criança:')) <br />
idade = int(input('Idade:')) <br />
if idade <= 5: <br />
    ensino = 'educação infantil' <br />
    print('O(A) aluno(a) {} possui {} ano(s) e está no {}'.format(nome,idade,ensino)) <br />
if 6 <= idade and idade <= 10: <br />
    ensino = 'ensino fundamental |' <br />
    print('O(A) aluno(a) {} possui {} ano(s) e está no {}'.format(nome, idade,ensino)) <br />
if 11 <= idade and idade <= 14: <br />
    ensino = 'ensino fundamental ||' <br />
    print('O(A) aluno(a) {} possui {} ano(s) e está no {}'.format(nome, idade,ensino)) <br />
if idade >= 15: <br />
    ensino = 'ensino médio' <br />
    print('O(A) aluno(a) {} possui {} ano(s) e está no {}.'.format(nome, idade,ensino)) <br />
continuar = int(input('Deseja continuar? \nDigite 1 para Sim \nDigite 2 para Não \n:')) <br />
while(continuar == 1): <br />
    nome = (input('Nome da criança:')) <br />
    idade = int(input('Idade:')) <br />
    if idade <= 5: <br />
        ensino = 'educação infantil' <br />
        print('O(A) aluno(a) {} possui {} ano(s) e está no {}'.format(nome, idade, ensino)) <br />
    if 6 <= idade and idade <= 10: <br />
        ensino = 'ensino fundamental |' <br />
        print('O(A) aluno(a) {} possui {} ano(s) e está no {}'.format(nome, idade, ensino))
    if 11 <= idade and idade <= 14:
        ensino = 'ensino fundamental ||'
        print('O(A) aluno(a) {} possui {} ano(s) e está no {}'.format(nome, idade, ensino))
    if idade >= 15:
        ensino = 'ensino médio'
        print('O(A) aluno(a) {} possui {} ano(s) e está no {}.'.format(nome, idade, ensino))
    continuar = int(input('Deseja continuar? \nDigite 1 para Sim \nDigite 2 para Não \n:'))

