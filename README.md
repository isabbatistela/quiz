Algoritmo "QUIZ"
// Disciplina   : [Lógica de Programação]
// Autor(a)    : Isabela Batistela Melo
// Data atual  : 06/09/2022
Var
Resposta: Caractere
Pontos,acertos,erros: Inteiro
pergunta : vetor [1..10] de caractere
respostas: vetor [1..30] de caractere
correta  : vetor [1..10] de caractere

Inicio
Escreval ("*****QUIZ*****")
Escreval ("Questão 1: Quando surgiram os computadores pessoais?")
Escreval ("A) 1840")
Escreval ("B) 1980")
Escreval ("C) 1960")
Escreval ("Digite a opção correta")
Leia (resposta)
Se (resposta= "b") então
 Escreval ("RESPOSTA CORRETA")
 pontos <-(pontos+10)
 acertos <- (acertos+1)
Senão
 Escreval ("TENTE NOVAMENTE")
 Escreval ("Digite a opção correta")
 Leia (resposta)
 Se (resposta="b") então
 Escreval ("RESPOSTA CORRETA")
 pontos <-(pontos+5)
 acertos <- (acertos+1)
 Senão
 Escreval ("RESPOSTA INCORRETA")
 erros <- (erros+1)
 fimse
fimse
Escreval ("Questão 2: Quais são os operadores matemáticos?")
Escreval ("A) Soma, Subtração, Multiplicação, divisão e resto da divisão")
Escreval ("B) Maior, Menor, Maior Igual, Menor Igual e Diferente")
Escreval ("C) Soma, Maior, Maior Igual e Diferente")
Escreval ("Digite a opção correta")
Leia (resposta)
Se (resposta="a") então
Escreval ("RESPOSTA CORRETA")
Pontos <- (pontos+10)
acertos <-(acertos+1)
Senão
 Escreval ("TENTE NOVAMENTE")
 Escreval ("Digite a Opção Correta")
 Leia (resposta)
 Se (resposta="a") então
 Escreval ("RESPOSTA CORRETA")
 pontos <- (pontos+5)
 acertos <-(acertos+1)
 Senão
 Escreval ("RESPOSTA INCORRETA")
 erros <-(erros+1)
 fimse
fimse
Escreval ("Questão 3: O que é uma variável?")
Escreval ("A) São operadores relacionais")
Escreval ("B) São operadores matemáticos")
Escreval ("C) Uma estrutura que armazena dados escolhidos.")
Escreval ("Digite a opção correta")
Leia (resposta)
Se (resposta="c") então
Escreval ("RESPOSTA CORRETA")
Pontos <- (pontos+10)
acertos <- (acertos+1)
Senão
 Escreval ("TENTE NOVAMENTE")
 Escreval ("Digite a opção correta")
 Leia (resposta)
 Se (resposta="c") então
 Escreval ("RESPOSTA CORRETA")
 pontos <-(pontos+5)
 acertos <-(acertos+1)
 Senão
 Escreval ("RESPOSTA INCORRETA")
 erros<-(erros+1)
 fimse
fimse
Escreval ("Questão 4: O que é um algoritmo?")
Escreval ("A) É a solução de um problema")
Escreval ("B) É um conjunto de instruções para se chegar a um determinado objetivo")
Escreval ("C) São ações para o computador executar")
Escreval ("Digite a opção correta")
Leia (resposta)
Se (resposta ="b") então
Escreval ("RESPOSTA CORRETA")
Pontos <- (pontos+10)
acertos <- (acertos+1)
Senão
 Escreval ("TENTE NOVAMENTE")
 Escreval ("Digite a opção correta")
 Leia (resposta)
 Se (resposta ="b") então
 Escreval ("RESPOSTA CORRETA")
 pontos <-(pontos+5)
 acertos <-(acertos+1)
 Senão
 Escreval ("RESPOSTA INCORRETA")
 erros<-(erros+1)
 fimse
fimse
Escreval ("Questão 5: O que é um pseudocódigo?")
Escreval ("A) Uma sequência de passos para atingir determinado objetivo.")
Escreval ("B) Maneira rigoroso de pensar")
Escreval ("C) Uma forma genérica de escrever o algoritmo, utilizando uma linguagem simples.")
Escreval ("Digite a opção correta")
Leia (resposta)
Se (resposta ="c") então
Escreval ("RESPOSTA CORRETA")
Pontos <- (pontos+10)
acertos <-(acertos+1)
Senão
 Escreval ("TENTE NOVAMENTE")
 Escreval ("Digite a opção correta")
 Leia (Resposta)
 Se (resposta="c") então
 Escreval ("RESPOSTA CORRETA")
 pontos <-(pontos+5)
 acertos<-(acertos+1)
 Senão
 Escreval ("RESPOSTA INCORRETA")
 erros<-(erros+1)
 fimse
fimse
Escreval ("Questão 6: Onde as variáveis ficam armazenadas?")
Escreval ("A) No banco de dados")
Escreval ("B) Na memória RAM do computador")
Escreval ("C) No programa/softaware")
Escreval ("Digite a opção correta")
Leia (resposta)
Se (resposta ="b") então
Escreval ("RESPOSTA CORRETA")
Pontos <- (pontos+10)
acertos<- (acertos+1)
Senão
 Escreval ("TENTE NOVAMENTE")
 Escreval ("Digite a opção correta")
 Leia (resposta)
 Se (resposta="b") então
 Escreval ("RESPOSTA CORRETA")
 Pontos<-(pontos+5)
 Acertos<-(acertos+1)
 Senão
 Escreval ("RESPOSTA INCORRETA")
 erros<-(erros+1)
 fimse
fimse
Escreval ("Questão 7: O que é um hardware?")
Escreval ("A) É uma linguagem de programação")
Escreval ("B) São peças físicas que compõem um computador")
Escreval ("C) É a parte lógica do computador, que faz ele funcionar.")
Escreval ("Digite a opção correta")
Leia (resposta)
Se (resposta ="b") então
Escreval ("RESPOSTA CORRETA")
Pontos <- (pontos+10)
acertos <-(acertos+1)
Senão
 Escreval ("TENTE NOVAMENTE")
 Escreval ("Digite a opção correta")
 Leia (resposta)
 Se (resposta="b") então
 Escreval ("RESPOSTA CORRETA")
 Pontos<-(pontos+5)
 acertos<-(acertos+1)
 Senão
 Escreval ("RESPOSTA INCORRETA")
 erros<-(erros+1)
 fimse
fimse
Escreval ("Questão 8: O que é um software?")
Escreval ("A) São peças físicas do computador")
Escreval ("B) É uma linguagem de programação.")
Escreval ("C) É a parte lógica do computador.")
Escreval ("Digite a opção correta.")
Leia (resposta)
Se (resposta ="c") então
Escreval ("RESPOSTA CORRETA")
Pontos <- (pontos+10)
Acertos <-(acertos+1)
Senão
 Escreval ("TENTE NOVAMENTE")
 Escreval ("Digite a opção correta.")
 Leia (resposta)
 Se (resposta = "c") então
 Escreval ("RESPOSTA CORRETA")
 Pontos <- (pontos+5)
 acertos <-(acertos+1)
 Senão
 Escreval ("RESPOSTA INCORRETA")
 Erros<-(erros+1)
 fimse
fimse
Escreval ("Questão 9: O que é um dispositivo de entrada?")
Escreval ("A) Dispositivo que fornece informação para as operações de um computador.")
Escreval ("B) Fazer login em um site")
Escreval ("C) Modo de inicializar o sistema operacional.")
Escreval ("Digite a opção correta")
Leia (resposta)
Se (resposta = "a") então
Escreval ("RESPOSTA CORRETA")
Pontos <- (pontos+10)
acertos<-(acertos+1)
Senão
 Escreval ("TENTE NOVAMENTE")
 Escreval ("Digite a opção correta")
 Leia (resposta)
 Se (resposta="a") então
 Escreval ("RESPOSTA CORRETA")
 Pontos <-(pontos+5)
 Acertos<-(acertos+1)
 Senão
 Escreval ("RESPOSTA INCORRETA")
 Erros<-(erros+1)
 fimse
fimse
Escreval ("Questão 10: O que é um dispositivo de saída?")
Escreval ("A) Retirar a informação de um site")
Escreval ("B) Retirar o login de um site")
Escreval ("C) Dispositivos que exibem dados e informações processadas pelo computador.")
Escreval ("Digite a opção correta")
Leia (resposta)
Se (resposta = "c") então
Escreval ("RESPOSTA CORRETA")
Pontos <- (pontos+10)
Acertos<-(acertos+1)
Senão
 Escreval ("RESPOSTA INCORRETA")
 Escreval ("Digite a opção correta")
 Leia (resposta)
 Se (resposta = "c") então
 Escreval ("RESPOSTA CORRETA")
 Senão
 Escreval ("RESPOSTA INCORRETA")
 Erros<-(erros+1)
 fimse
fimse
Escreval ("***PLACAR FINAL***")
Escreval ("Você fez", pontos  , "pontos")
Escreval ("Você teve", erros, "erros.")
Escreval ("Você teve", acertos, "acertos.")
se (pontos >= 100) então
escrevaL("Excelente!")
fimse
se (pontos >=75) e (pontos <=99) então
escrevaL("Ótimo!")
fimse
se (pontos >=50) e (pontos <=74) então
escrevaL("Bom!")
fimse
se (pontos >=49) e (pontos <=24) então
escrevaL("Regular!")
fimse
se (pontos <=24) então
escrevaL ("Péssimo!")
fimalgoritmo
