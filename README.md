# hangman_game
# Módulo: [DS-PY-001] - Lógica de Programação (PY)
# Projeto: Hangman (Jogo da forca)
# Professor: Lucas Saito
# Data de entrega: 29/09/2022
# Emails para enviar o projeto:
#	lucas.saitob@gmail.com
#	henriqueassiscordeiro@hotmail.com
#
# Repositorio: https://github.com/lucsaito/DS-PY-01-Logica-de-Programacao
#
# Objetivos:
#	1. Trabalhar com estrutura condicional (if, elif, else)
#	2. Trabalhar com estrutura de repetição (while e for loop)
#	3. Leitura do stdin e impressão no stdout
#	4. Utilizar manipulação(métodos) e slicing de strings
#	5. Utilização de listas
#	6. Utilização da biblioteca `random`: https://docs.python.org/3/library/random.html
#
# Descrição:
#	Estabelecer dentro do código uma lista de palavras(ex: ['arvore', 'banana', 'gato', 'churrasqueira']) para
#	uma delas ser escolhida de forma aleatória por uma função da biblioteca `random`, e estabelecer um número X de tentatitvas
#	para o usuário tentar adivinhar se uma letra(inserida no input() em cada tentativa) faz parte dessa palavra
#	escolhida aleatoriamente da lista.
#	Caso as tentativas do usuário acabem, imprimir uma mensagem informando que as tentativas acabaram e ele perdeu.
#	Caso o usuário adivinhe a palavra inteira, imprimir uma mensagem de vitória.
#
#
#	Ex: Palavra escolhida "Churrasqueira", se o usuário escrever a letra "a" no input(), você deve mostrar
#	da seguinte forma:      _____A______A
#	Se em seguida o usuário digitar a letra "r", teremos que imprimir:	___RRA______RA
#	e assim por diante.
#
