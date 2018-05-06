# Projeto Integrador - Exercício 07

### Layla Comparin

1) Em comentários, explique o que cada comando faz:


```python
5 + 5   # retorna o valor 10 da soma 5 mais 5
8 - 6   # retorna o valor 2 da subtracao de 8 menos 6
12 * 5  # retorna o valor 60 da multiplicacao de 12 vezes 5
4**2    # retorna o valor 16 do calculo de 4 elevado ao quadrado
27**(1/3)   # retorna o valor 3 da raíz cúbica de 27
27 / 3  # retorna o valor 9 da divisao de 27 por 3
27 // 4     # retorna o valor 6 (quociente inteiro) da divisão de 27 por 4
27 % 4      # retorna o valor 3 (resto) da divisão de 27 por 4


print('Este exercício é muito legal!')  # printa na tela Este exercício é muito legal!
x = 7   # atribui o valor 7 ao objeto x
print('O exercício ' + str(x) + ' é muito fácil!')  # printa na tela O exercício 7 é muito fácil!, convertendo o 7 da variável x para string
x, y = 5, 6     # atribui 5 ao x e 6 ao y
print(x, y) # printa na tela os valores de x e y, separados por um espaço
print('Aprendi na escola que o {} vem antes do {}'.format(x, y))    # printa na tela Aprendi na escola que o 5 vem antes do 6

meuNome = 'Neylson Crepalde'    # define o objeto meuNome como Neylson Crepalde
print(meuNome[:8])  # retorna as letras do meuNome do início até a posicao 7 (começando do 0)
print(meuNome[8:])  # retorna as letras do meuNome da posicao 8 até o final

galera = ['Neylson', 'Edésio', 'Layla', 'Gerson', 'Iago','Ester', 'Juliany', 'Marcos', 'Patrick', 
          'Bia', 'Fabiano', 'Larissa', 'Sávio', 'Túlio', 'Vanessa', 'Numiá', 'Adelvan', 'Nelson', 
          'Warley', 'Vladimir'] # cria uma lista com todos esses nomes
          
galera[1]   # retorna a 2º posicao da lista (Neylson)
galera[0]   # retorna a 1º posicao da lista (Edésio)
galera[:5]  # retorna as 5 primeiras posicoes da lista
galera[10:] # retorna da 11º posicao até o final desta lista
galera[6:15]    # retorna da 7º posicao até a 15º posicao da lista
```

2) Crie três listas. A primeira deve conter o nome de 5 amigos de infância. A segunda deve conter o nome e 5 animais de estimação. A terceira deve conter três pratos que você adora comer (use a criatividade). Exiba o conteúdo das listas.

```python    
childhoodFriend = ['Beatriz', 'Rebeca', 'Stephanny', 'Igor', 'Matheus']
pet = ['Pastora','Lavínia', 'Pretinha', 'Fiona', 'Maya']
food = ['Batata Frita', 'Figado Acebolado', 'Esfiha', 'Pipoca', 'Pavê de Morango']

print(childhoodFriend, pet, food)
```
# Neylson, aqui você pediu três pratos, mas na questão 5 você pede pra trazer do 2 até o 4. Como não existia o 4 eu criei uma lista com 5, senão dá erro no Python. :)

3) Printe o nome do terceiro amigo da lista. 

```python     
print(childhoodFriend[2])
```

4) Bole uma frase bonitinha para chamar um bicho e insira nesse frase o nome do último bicho de estimação. Printe a frase na tela.

```python     
print(f'Vem cá menininha da mamãe, vem cá {pet[4]}!')
```

5) Exiba na tela uma frase perguntando o que você quer comer no jantar essa noite e dê três opções: o segundo, terceiro e quarto pratos. (dica, use os comandos print e .format)

```python     
print(f'Qual dos pratos abaixo você quer comer? \n \
1){food[1]} \n \
2){food[2]} \n \
3){food[3]}')
```

6) Crie um objeto chamado `nomeCompleto` e atribua a ele o seu nome completo como uma string.

```python 
nomeCompleto = 'Layla Suellen Vilela Santos Comparin'
```

7) Usando apenas slices (subsettings de um dado de texto) exiba apenas seu primeiro nome, apenas seu nome do meio e apenas seu sobrenome, um por vez.

```python 
print(nomeCompleto[:5])
print(nomeCompleto[6:13])
print(nomeCompleto[14:])
```

8) Crie um dicionário com dados sobre a sua casa. Pense em dados que seriam interessantes de serem usados numa pesquisa de verdade - quantidade de moradores, bairro de localização, nomes das pessoas que moram, idade, cor, sexo, tipo de moradia (casa ou apartamento) e mais quatro campos. Use a criatividade!!! Lembre-se de que num dicionário, os valores podem ser qualquer tipo de dado (string, int, float, listas, dicionários, etc.) e podem também ser de qualquer tamanho.

```python 
casa = {'Quantidade de Moradores': 3,
        'Bairro': 'Santo Antônio',
        'Nomes': ['Layla', 'Marília', 'Thanara'],
        'Idades': [24, 67, 45],
        'Cor': ['Branco(a)', 'Preto(a)', 'Branco(a)'],
        'Sexo': ['Feminino'],
        'Tipo de Moradia': ['Casa'],
        'Estado Civil': ['Solteiro(a)', 'Viúvo(a)', 'Solteiro(a)'],
        'Altura': [1.57, 1.65, 1.62],
        'Quantidade de Filhos': [0, 2, 0],
        'Trabalha Atualmente': [True, False, True]}
```

9) Exiba apenas as chaves do dicionário. Exiba apenas os valores do dicionário.

```python 
casa.keys()
casa.values()
```

10) Exiba apenas o nome da segunda pessoa que mora na sua casa.

```python 
casa['Nomes'][1]
```

11) Escolha ais duas informações relevantes e exiba no console.

```python 
casa['Trabalha Atualmente']
casa['Estado Civil']
```
