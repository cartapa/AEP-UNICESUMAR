Algoritmo "semnome"
// Disciplina   : [Linguagem e Lógica de Programação]
// Professor   : Antonio Carlos Nicolodi 
// Descrição   : Aqui você descreve o que o programa faz! (função)
// Autor(a)    : Nome do(a) aluno(a)
// Data atual  : 19/11/2020
Var


// TELA DE REGISTRO

opcao : inteiro  //Para gerir as escolhas
loguin: caractere   // loguin do úsuario
loguin_u: caracter //validação do úsuario
senha: caractere  //senha do úsuario
c_senha : caractere //para confirmar a senha
cont : inteiro

nome : vetor [1..5] de caractere
n : inteiro // contar o vetor





//TELA DE LOGUIN

procedimento start ()
inicio
limpatela
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - AEP     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|             MY OCEAN                |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       | Digite seu Úsuario  |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("=======================================")
leia(loguin_u)
cont <-0
enquanto (loguin_U <> loguin) faca
limpatela
cont <- cont +1
usuario_invalido ()
leia(loguin_u)
se cont > 5 entao
escreval ("VOCE ERROU 5x SEU ÚSUARIO POR MOTIVOS DE SEGURANÇA O JOGO IRA FECHAR KK")
fimalgoritmo
fimse

fimenquanto



limpatela
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - AEP     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|             MY OCEAN                |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       | Digite sua Senha    |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("=======================================")
Leia(c_senha)
cont <-0
enquanto (c_senha <> senha) faca
limpatela
cont <- cont + 1
senha_invalida ()
leia(c_senha)
se cont > 5 entao
escreval ("VOCE ERROU 5x SUA SENHA POR MOTIVOS DE SEGURANÇA O JOGO IRA FECHAR KK")
fimalgoritmo
fimse
fimenquanto
fimprocedimento





//TELA DE REGISTRO
procedimento cadastro ()
inicio

limpatela
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - AEP     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|             MY OCEAN                |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       | Digite Novo Úsuario |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("=======================================")
leia(loguin)
limpatela

escreval("=======================================")
escreval("|      Creat for UNICESUMAR - AEP     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|             MY OCEAN                |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       | Digite Nova Senha   |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("=======================================")
leia(senha)
limpatela

escreval("=======================================")
escreval("|      Creat for UNICESUMAR - AEP     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|             MY OCEAN                |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       | Cofirme sua Senha   |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("=======================================")
leia(c_senha)
cont <- 0
             enquanto (senha <> c_senha) faca
             cont<-cont + 1
             limpatela
             senha_invalida ()
             leia(c_senha)
             se cont > 5 entao
             escreval ("VOCE ERROU 5x SUA SENHA POR MOTIVOS DE SEGURANÇA O JOGO IRA FECHAR KK")
                fimalgoritmo
            fimse
            fimenquanto

limpatela
escreval("========================================")
escreval("|      Creat for UNICESUMAR - AEP      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|               MY OCEAN               |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|           CADASTRO CONCLUIDO         |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|      Press any key to continue       |")
escreval("========================================")
leia(validador)
limpatela
fimprocedimento

//TELA FIM DE JOGO
procedimento fim_jogo ()
inicio
limpatela
      fala<-"======================================="
      dialogo (fala)
      fala<-"|                                     |"
      dialogo (fala)
      fala<-"|            FIM DE JOGO              |"
      dialogo (fala)
      fala<-"|                                     |"
      dialogo (fala)
      fala<-"======================================="
      dialogo (fala)
      fimalgoritmo
fimprocedimento



//TELA INICIO ERRO
procedimento erro_menu_um ()
inicio
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - AEP     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|             MY OCEAN                |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       |      Úsuario        |       |")
escreval("|       -----------------------       |")
escreval("|       |       Senha         |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|          1 - Login                  |")
escreval("|          2 - Registre-se            |")
escreval("|          3 - SAIR                   |")
escreval("|                                     |")
escreval("|   OPÇÃO INVALIDA TENTE NOVAMENTE    |")
escreval("=======================================")
fimprocedimento

//TELA INICIO 2

procedimento erro_menu_dois ()
inicio
limpatela
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - AEP     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|             MY OCEAN                |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       |      Úsuario        |       |")
escreval("|       -----------------------       |")
escreval("|       |       Senha         |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|          1 - Criar nova conta       |")
escreval("|          2 - Esqueci a Senha        |")
escreval("|          3 - SAIR                   |")
escreval("|                                     |")
escreval("|   OPÇÃO INVALIDA TENTE NOVAMENTE    |")
escreval("=======================================")
fimprocedimento

//TELA DE INICIO 3


procedimento erro_menu_tres ()
inicio
limpatela
escreval("======================================")
escreval("|      Creat for UNICESUMAR - AEP    |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|       ----------------------       |")
escreval("|       | ****** MENU ****** |       |")
escreval("|       ----------------------       |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|             MY OCEAN               |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|       ----------------------       |")
escreval("|       | 1 - NOVO JOGO      |       |")
escreval("|        ---------------------       |")
escreval("|       | 2 - SCORE          |       |")
escreval("|       ----------------------       |")
escreval("|       | 3 - SAIR           |       |")
escreval("|       ----------------------       |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|  OPÇÃO INVALIDA TENTE NOVAMENTE    |")
escreval("======================================")
fimprocedimento

//erro pergunta

procedimento erro_pergunta
inicio
limpatela
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - AEP     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|        Qual Assunto você está       |")
escreval("|           mais interessado?         |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       | 1 - Peixes ?        |       |")
escreval("|       -----------------------       |")
escreval("|       | 2 - Poluição ?      |       |")
escreval("|       -----------------------       |")
escreval("|       | 3 - Mamíferos ?     |       |")
escreval("|       -----------------------       |")
escreval("|       | 4 - Menu            |       |")
escreval("|       -----------------------       |")
escreval("|       | 5 - SAIR            |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("=======================================")
fimprocedimento


//erro pergunta dois
procedimento erro_pergunta_dois
inicio
limpatela
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - APS     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       Você escolheu PEIXES!         |")
escreval("|       Qual o nome dado para o       |")
escreval("|       Famoso Peixe NEMO ?           |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       | 1 - Carpa    ?      |       |")
escreval("|       -----------------------       |")
escreval("|       | 2 - Peixe Palhaço ? |       |")
escreval("|       -----------------------       |")
escreval("|       | 3 - Salmão ?        |       |")
escreval("|       -----------------------       |")
escreval("|       | 4 - Dourado ?       |       |")
escreval("|       -----------------------       |")
escreval("|       | 5 - Dori ?          |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("=======================================")
fimprocedimento





// TELA DE SENHA INCORRETA
procedimento senha_invalida ()
inicio
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - AEP     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|             MY OCEAN                |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       |   SENHA INCORRETA   |       |")
escreval("|       |   DIGITE NOVAMENTE  |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("=======================================")
fimprocedimento

//TELA DE USUARIO INCORRETO

procedimento usuario_invalido ()
inicio
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - AEP     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|             MY OCEAN                |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       |   ÚSUARIO INCORRETO |       |")
escreval("|       |   DIGITE NOVAMENTE  |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("=======================================")


fimprocedimento


//CHAMADAS COM EFEITO

//CHAMADA DE MENU

procedimento conta ()
inicio
se (opcao = 1) ou (opcao = 2) ou (opcao = 3) entao
escolha (opcao)
caso 1
start ()
escreval("INICIA O JOGO")
caso 2
escreval ("AQUI ERA PRA FAZER NEGOCIOS COM VETORES MAS NÂO TENHO A MINIMA IDEIA DE COMO FAZER PARA ASSOCIAR UMA POSIÇÃO DE UM VETOR EM OUTRO MAIS DE UM REGISTRO NO MESMO PROGRAMA")
fimalgoritmo
caso 3
fim_jogo ()
fimescolha
fimse
fimprocedimento

fala:caractere  //variavel para chamada de efeito de fala


//procedimento de dialogo em timer

procedimento dialogo (fala: caractere)
var
x, cont: inteiro
space: caractere

inicio

escreval
timer (350)
timer (0)
cont <- compr(fala)
para x de 1 ate cont faca
space <-copia(fala,x,1)
timer(0)
escreva(space)
 fimpara
fimprocedimento


//PROCEDIMENTO DO GAME

pontuacao : inteiro
idade : inteiro
validador : caractere


procedimento menu_inicial ()
inicio
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - AEP     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|             MY OCEAN                |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       |      Úsuario        |       |")
escreval("|       -----------------------       |")
escreval("|       |       Senha         |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|          1 - Login                  |")
escreval("|          2 - Registre-se            |")
escreval("|          3 - SAIR                   |")
escreval("|                                     |")
escreval("|                                     |")
escreval("=======================================")
opcao <- 0
leia (opcao)
enquanto (opcao <> 1) e (opcao <> 2) e (opcao <> 3) faca
           limpatela
           erro_menu_um ()
           leia(opcao)
           fimenquanto
fimprocedimento






procedimento menu()
inicio
limpatela
escreval("======================================")
escreval("|      Creat for UNICESUMAR - AEP    |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|       ----------------------       |")
escreval("|       | ****** MENU ****** |       |")
escreval("|       ----------------------       |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|             MY OCEAN               |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|       ----------------------       |")
escreval("|       | 1 - NOVO JOGO      |       |")
escreval("|        ---------------------       |")
escreval("|       | 2 - SCORE          |       |")
escreval("|       ----------------------       |")
escreval("|       | 3 - SAIR           |       |")
escreval("|       ----------------------       |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|                                    |")
escreval("|                                    |")
escreval("======================================")
opcao <-0
leia(opcao)
enquanto (opcao <> 1) e (opcao <> 2 ) e (opcao <> 3) faca
limpatela
erro_menu_tres
leia(opcao)
fimenquanto

fimprocedimento


procedimento score ()
inicio

escreval("=======================================")
escreval("|      Creat for UNICESUMAR - APS     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                SCORE                |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|-------------------------------------|")
escreval("| 1 -                                 |")
escreval("|-------------------------------------|")
escreval("| 2 -                                 |")
escreval("|-------------------------------------|")
escreval("| 3 -                                 |")
escreval("|-------------------------------------|")
escreval("| 4 -                                 |")
escreval("|-------------------------------------|")
escreval("| 5 -                                 |")
escreval("|-------------------------------------|")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|      Pressione qualquer tecla       |")
escreval("|        para voltar ao menu          |")
escreval("|                                     |")
escreval("=======================================")
leia(validador)

fimprocedimento


 //TELA DE IDADE
 
 procedimento dados_iniciais ()
 inicio
limpatela
escreval("========================================")
escreval("|      Creat for UNICESUMAR - AEP      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|               MY OCEAN               |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("| Os conteúdos mostrados e o nível das |")
escreval("|  perguntas se basearão em sua faixa  |")
escreval("|            faixa etária              |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|        QUAL SEU NOME AMIGO   ?       |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|      Press any key to continue       |")
escreval("========================================")
n <-0
leia(nome[n+1])


limpatela
escreval("========================================")
escreval("|      Creat for UNICESUMAR - AEP      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|               MY OCEAN               |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("| Os conteúdos mostrados e o nível das |")
escreval("|  perguntas se basearão em sua faixa  |")
escreval("|            faixa etária              |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|           QUAL A SUA IDADE ?         |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("========================================")
leia(idade)

fimprocedimento

 
//PERGUNTA UM

procedimento pergunta ()
inicio
limpatela
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - AEP     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|        Qual Assunto você está       |")
escreval("|           mais interessado?         |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       | 1 - Peixes ?        |       |")
escreval("|       -----------------------       |")
escreval("|       | 2 - Poluição ?      |       |")
escreval("|       -----------------------       |")
escreval("|       | 3 - Mamíferos ?     |       |")
escreval("|       -----------------------       |")
escreval("|       | 4 - SAIR            |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("=======================================")
opcao <-0
leia(opcao)
enquanto (opcao <> 1) e (opcao <> 2) e (opcao <> 3) e (opcao <> 4) e (opcao <>5)faca
           limpatela
           erro_pergunta ()
           leia(opcao)
           fimenquanto
fimprocedimento


//pergunta peixe

procedimento pergunta_peixe ()
inicio
limpatela
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - APS     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       Você escolheu PEIXES!         |")
escreval("|       Qual o nome dado para o       |")
escreval("|       Famoso Peixe NEMO ?           |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       | 1 - Carpa    ?      |       |")
escreval("|       -----------------------       |")
escreval("|       | 2 - Peixe Palhaço ? |       |")
escreval("|       -----------------------       |")
escreval("|       | 3 - Salmão ?        |       |")
escreval("|       -----------------------       |")
escreval("|       | 4 - Dourado ?       |       |")
escreval("|       -----------------------       |")
escreval("|       | 5 - Dori ?          |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("=======================================")
opcao <-0
leia(opcao)
enquanto (opcao <> 1) e (opcao <> 2) e (opcao <> 3) e (opcao <> 4) e (opcao <>5)faca
           limpatela
           erro_pergunta_dois ()
           leia(opcao)
           fimenquanto
fimprocedimento

//pergunta poluicao
procedimento pergunta_poluicao ()
inicio
limpatela
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - AEP     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       Quando vamos a praia          |")
escreval("|       Qual o melhor lugar           |")
escreval("|       para jogar o nosso lixo ?     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       | 1 - Mar    ?        |       |")
escreval("|       -----------------------       |")
escreval("|       | 2 - Areia ?         |       |")
escreval("|       -----------------------       |")
escreval("|       | 3 - Lixeira ?       |       |")
escreval("|       -----------------------       |")
escreval("|       | 4 - Enterrar ?      |       |")
escreval("|       -----------------------       |")
escreval("|       | 5 - Queimar ?       |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("=======================================")
opcao <-0
leia(opcao)
enquanto (opcao <> 1) e (opcao <> 2) e (opcao <> 3) e (opcao <> 4) e (opcao <>5)faca
           limpatela
           erro_pergunta_dois ()
           leia(opcao)
           fimenquanto
fimprocedimento

//resposta certa peixe

procedimento peixe_certo ()
inicio
limpatela
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - APS     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|        PRABÉNS VOCÊ ACERTOU         |")
escreval("|                                     |")
escreval("|          GANHOU + 20 PONTOS         |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|-------------------------------------|")
escreval("|   | Sim o famoso Nemo leva o    |   |")
escreval("|   | nome de peixe palhaço, ele  |   |")
escreval("|   | também é conhecido por      |   |")
escreval("|   | peixe-anêmona porque vivem  |   |")
escreval("|   | entre as anêmonas-do-mar    |   |")
escreval("|   |                             |   |")
escreval("|   | Onde os encontramos ?       |   |")
escreval("|   | Geralmente eles vivem em    |   |")
escreval("|   | partes quentes e rasas dos  |   |")
escreval("|   | Oceanos Índico e Pacífico   |   |")
escreval("|   |                             |   |")
escreval("|   | O problema é que com as     |   |")
escreval("|   | queimadas e a poluição do ar|   |")
escreval("|   | os corais que são a sua casa|   |")
escreval("|   | estão sumindo, e o Nemo logo|   |")
escreval("|   | não vai ter onde morar      |   |")
escreval("|   | por isso é importante cuidar|   |")
escreval("|   | do nosso Planeta =D         |   |")
escreval("|-------------------------------------|")
escreval("|      Press any key to continue      |")
escreval("=======================================")
pontuacao <- pontuacao + 20
leia(validador)
fimprocedimento

procedimento peixe_errado ()
inicio
limpatela
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - APS     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|        QUE PENA VOCÊ ERROU          |")
escreval("|                                     |")
escreval("|          PERDEU  10 PONTOS          |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|-------------------------------------|")
escreval("|   | O famoso Nemo leva o        |   |")
escreval("|   | nome de peixe palhaço, ele  |   |")
escreval("|   | também é conhecido por      |   |")
escreval("|   | peixe-anêmona porque vivem  |   |")
escreval("|   | entre as anêmonas-do-mar    |   |")
escreval("|   |                             |   |")
escreval("|   | Onde os encontramos ?       |   |")
escreval("|   | Geralmente eles vivem em    |   |")
escreval("|   | partes quentes e rasas dos  |   |")
escreval("|   | Oceanos Índico e Pacífico   |   |")
escreval("|   |                             |   |")
escreval("|   | O problema é que com as     |   |")
escreval("|   | queimadas e a poluição do ar|   |")
escreval("|   | os corais que são a sua casa|   |")
escreval("|   | estão sumindo, e o Nemo logo|   |")
escreval("|   | não vai ter onde morar      |   |")
escreval("|   | por isso é importante cuidar|   |")
escreval("|   | do nosso Planeta =D         |   |")
escreval("|-------------------------------------|")
escreval("|      Press any key to continue      |")
escreval("=======================================")
pontuacao <-pontuacao-10
leia(validador)
fimprocedimento

//resposta certa poluicao

procedimento poluicao_certo ()
inicio
limpatela
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - APS     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|        PRABÉNS VOCÊ ACERTOU         |")
escreval("|                                     |")
escreval("|          GANHOU + 20 PONTOS         |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|-------------------------------------|")
escreval("|   | A poluição marinha ocorre   |   |")
escreval("|   |porque tantos os mares quanto|   |")
escreval("|   |osoceanos recebem diariamente|   |")
escreval("|   |em todo o mundo, uma enorme  |   |")
escreval("|   |quantidade de poluentes, como|   |")
escreval("|   |esgoto doméstico, industriais|   |")
escreval("|   |lixo sólido.                 |   |")
escreval("|   |Estima que cerca de 14BILHÕES|   |")
escreval("|   |de toneladas de lixo são     |   |")
escreval("|   |acumuladas todos os anos nos |   |")
escreval("|   |nosso mares...               |   |")
escreval("|   |                             |   |")
escreval("|   |Triste não ?                 |   |")
escreval("|   |                             |   |")
escreval("|   | Por isso devemos cuidar     |   |")
escreval("|   | antes que tudo morra!!      |   |")
escreval("|   | Chute seu pai se ele jogar  |   |")
escreval("|   |lixo nas ruas e mares...  xD |   |")
escreval("|-------------------------------------|")
escreval("|      Press any key to continue      |")
escreval("=======================================")
pontuacao <- pontuacao + 20
leia (validador)

fimprocedimento

//poluicao errado

procedimento poluicao_errado ()
inicio
limpatela
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - APS     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|        QUE PENA VOCÊ ERROU!         |")
escreval("|                                     |")
escreval("|          pERDEU 10 PONTOS           |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|-------------------------------------|")
escreval("|   | A poluição marinha ocorre   |   |")
escreval("|   |porque tantos os mares quanto|   |")
escreval("|   |os oceanos recebem diariamente|   |")
escreval("|   |em todo o mundo, uma enorme  |   |")
escreval("|   |quantidade de poluentes, como|   |")
escreval("|   |esgoto doméstico, industriais|   |")
escreval("|   |lixo sólido.                 |   |")
escreval("|   |Estima que cerca de 14BILHÕES|   |")
escreval("|   |de toneladas de lixo são     |   |")
escreval("|   |acumuladas todos os anos nos |   |")
escreval("|   |nosso mares...               |   |")
escreval("|   |                             |   |")
escreval("|   |Triste não ?                 |   |")
escreval("|   |                             |   |")
escreval("|   | Por isso devemos cuidar     |   |")
escreval("|   | antes que tudo morra!!      |   |")
escreval("|   | Chute seu pai se ele jogar  |   |")
escreval("|   |lixo nas ruas e mares...  xD |   |")
escreval("|-------------------------------------|")
escreval("|      Press any key to continue      |")
escreval("=======================================")
pontuacao <- pontuacao - 10
leia(validador)

fimprocedimento


//pergunta mamiferos


procedimento pergunta_mamiferos ()
inicio

escreval("=======================================")
escreval("|      Creat for UNICESUMAR - APS     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       Quando o maior Mamifero       |")
escreval("|       dos Oceanos ?                 |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       | 1 - Golfinho    ?   |       |")
escreval("|       -----------------------       |")
escreval("|       | 2 - Sereia ?        |       |")
escreval("|       -----------------------       |")
escreval("|       | 3 - Baleia-Azul ?   |       |")
escreval("|       -----------------------       |")
escreval("|       | 4 - Tubarão ?       |       |")
escreval("|       -----------------------       |")
escreval("|       | 5 - Aquaman ?       |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("=======================================")
opcao <-0
leia(opcao)
enquanto (opcao <> 1) e (opcao <> 2) e (opcao <> 3) e (opcao <> 4) e (opcao <>5)faca
           limpatela
           erro_pergunta_dois ()
           leia(opcao)
           fimenquanto
fimprocedimento


procedimento mamiferos_certo ()
inicio
 escreval("=======================================")
escreval("|      Creat for UNICESUMAR - APS     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|        PRABÉNS VOCÊ ACERTOU         |")
escreval("|                                     |")
escreval("|          GANHOU + 20 PONTOS         |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|-------------------------------------|")
escreval("|   | O maior mamífero da TERRA   |   |")
escreval("|   |é a Baleia-Azul, podendo ter |   |")
escreval("|   |33 metros de comprimento e   |   |")
escreval("|   |pesar ate 130 toneladas..    |   |")
escreval("|   |                             |   |")
escreval("|   |Porém as Baleias estão ameaçadas|   |")
escreval("|   |Sua caça vem sendo praticada |   |")
escreval("|   |o que faz com que sua especie|   |")
escreval("|   |corra o risco de estinção..  |   |")
escreval("|   |                             |   |")
escreval("|   |                             |   |")
escreval("|   |                             |   |")
escreval("|   |Triste não ?                 |   |")
escreval("|   |                             |   |")
escreval("|   | Por isso devemos cuidar     |   |")
escreval("|   | antes que tudo morra!!      |   |")
escreval("|   | Chute seu pai se ele caça   |   |")
escreval("|   |Baleias por ai               |   |")
escreval("|-------------------------------------|")
escreval("|      Press any key to continue      |")
escreval("=======================================")
leia(validador)
limpatela
fimprocedimento



procedimento mamiferos_errado ()
inicio
 escreval("=======================================")
escreval("|      Creat for UNICESUMAR - APS     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|        QUE PENA VOCÊ ERROU          |")
escreval("|                                     |")
escreval("|          Perdeu 10   PONTOS         |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|-------------------------------------|")
escreval("|   | O maior mamífero da TERRA   |   |")
escreval("|   |é a Baleia-Azul, podendo ter |   |")
escreval("|   |33 metros de comprimento e   |   |")
escreval("|   |pesar ate 130 toneladas..    |   |")
escreval("|   |                             |   |")
escreval("|   |Porém as Baleias estão ameaçadas|   |")
escreval("|   |Sua caça vem sendo praticada |   |")
escreval("|   |o que faz com que sua especie|   |")
escreval("|   |corra o risco de estinção..  |   |")
escreval("|   |                             |   |")
escreval("|   |                             |   |")
escreval("|   |                             |   |")
escreval("|   |Triste não ?                 |   |")
escreval("|   |                             |   |")
escreval("|   | Por isso devemos cuidar     |   |")
escreval("|   | antes que tudo morra!!      |   |")
escreval("|   | Chute seu pai se ele caça   |   |")
escreval("|   |Baleias por ai               |   |")
escreval("|-------------------------------------|")
escreval("|      Press any key to continue      |")
escreval("=======================================")
leia(validador)
limpatela

fimprocedimento


procedimento jogo ()
inicio
                         se (opcao =1) ou (opcao =2) ou (opcao = 3) ou (opcao =4) ou (opcao = 5) entao
                                escolha (opcao)
                               caso 1
                                      pergunta_peixe ()
                                      se (opcao = 2) entao
                                      peixe_certo()
                                      senao
                                      peixe_errado()
                                      fimse
                                      limpatela
                                      Escreval ("FIM DO JOGO DEMO")
                                      Escreval("JOGO COMPLETO POR 99.90R$ na STEAM")
                                      fimalgoritmo

                               caso 2
                                    pergunta_poluicao ()
                                    se (opcao = 3) entao
                                    poluicao_certo ()
                                    senao
                                    poluicao_errado ()
                                    fimse
                                    limpatela
                                    Escreval ("FIM DO JOGO DEMO")
                                    Escreval("JOGO COMPLETO POR 99.90R$ na STEAM")
                                      fimalgoritmo


                               caso 3
                                     pergunta_mamiferos ()
                                     se (opcao = 3) entao
                                     mamiferos_certo ()
                                     senao
                                     mamiferos_errado ()
                                     fimse
                                     limpatela
                                     Escreval ("FIM DO JOGO DEMO")
                                    Escreval("JOGO COMPLETO POR 99.90R$ na STEAM")
                                      fimalgoritmo




                               caso 4
                                       fim_jogo ()
                                       fimalgoritmo

                                       fimescolha
                                       fimse
fimprocedimento








 //*******************************INICIO DO MENU ********************************************************


Inicio
//iniciar variavel

pontuacao <- 0


//TELA DE INICIO

escreval("========================================")
escreval("|      Creat for UNICESUMAR - AEP      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|              MY OCEAN                |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|                                      |")
escreval("|      Press any key to continue       |")
escreval("========================================")
leia(validador)
limpatela


//TELA DE REGISTRO E LOGIN

menu_inicial ()

//FAZENDO O REGISTRO
   escolha (opcao)
   caso 1
   limpatela
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - AEP     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|             MY OCEAN                |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       | Digite seu Úsuario  |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("=======================================")
leia(loguin_u)
cont <-0
enquanto (loguin <> loguin_u) faca
limpatela
cont <- cont + 1
usuario_invalido ()
leia(loguin_u)
    se cont >= 3 entao


limpatela
escreval("=======================================")
escreval("|      Creat for UNICESUMAR - AEP     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|             MY OCEAN                |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|       -----------------------       |")
escreval("|       |      Úsuario        |       |")
escreval("|       -----------------------       |")
escreval("|       |       Senha         |       |")
escreval("|       -----------------------       |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|                                     |")
escreval("|          1 - Criar nova conta       |")
escreval("|          2 - Esqueci a Senha        |")
escreval("|          3 - SAIR                   |")
escreval("|                                     |")
escreval("|                                     |")
escreval("=======================================")
leia(opcao)
enquanto (opcao <> 1) e (opcao <> 2) e (opcao <> 3) faca
limpatela
erro_menu_dois ()
leia(opcao)
fimenquanto

           escolha (opcao)
           caso 1
           cadastro()
           menu_inicial()
           conta()
           
           caso 2
           cadastro()
           menu_inicial()
           conta()
           
           caso 3

           fim_jogo ()

           fimescolha
           
    

    fimse
fimenquanto



   
           caso 2
           cadastro ()
           menu_inicial()
           conta()

           caso 3
      
           fim_jogo ()

           fimescolha



  //*************************************FIM DO MENU ************************

 //************************JOGO**********************************************
 
   opcao <-0
  menu ()
  
  
  escolha (opcao)
       se (opcao = 1) ou (opcao = 2) ou (opcao = 3) entao

   
   caso 1
   
   
        dados_iniciais () //JOGO
        se (idade < 5) entao
        limpatela
        escreval("=================================")
        escreval("|                               |")
        escreval("|   VOCÊ COM MENOS DE 5 ANOS    |")
        escreval("|          SABE LER ?           |")
        escreval("|                       OK!     |")
        escreval("|    Press any key to continue  |")
        escreval("=================================")
        leia(validador)
        
        limpatela
           opcao <-0
        pergunta ()
        jogo()
        fimse
        
        se (idade > 120) entao
        limpatela
        escreval("=================================")
        escreval("|                               |")
        escreval("|   VOCÊ TEM ",idade," ANOS     |")
        escreval("|          SUA MUMIA            |")
        escreval("|                       OK!     |")
        escreval("|    Press any key to continue  |")
        escreval("=================================")
        leia(validador)
        limpatela
        opcao <-0
        pergunta ()
        jogo()
        fimse
        
        se (idade >=5 ) e (idade <=120) entao
        escreval("=================================")
        escreval("|                               |")
        escreval("|   VOCÊ TEM ",idade," ANOS     |")
        escreval("|          PRONTO PARA O DEMO   |")
        escreval("|                       xD      |")
        escreval("|    Press any key to continue  |")
        escreval("=================================")
        leia(validador)
        limpatela
        opcao <-0
        pergunta ()
        jogo()
        fimse
        
        
        
        
        
        
   


   
        caso 2
        score ()
        menu ()

             escolha(opcao)
                           se (opcao = 1) ou (opcao = 2 ) ou (opcao = 3) entao


              caso 1
              
              dados_iniciais()  //JOGO
                se (idade < 5) entao
        limpatela
        escreval("=================================")
        escreval("|                               |")
        escreval("|   VOCÊ COM MENOS DE 5 ANOS    |")
        escreval("|          SABE LER ?           |")
        escreval("|                       OK!     |")
        escreval("|    Press any key to continue  |")
        escreval("=================================")
        leia(validador)

        limpatela
           opcao <-0
        pergunta ()
        jogo()
        fimse

        se (idade > 120) entao
        limpatela
        escreval("=================================")
        escreval("|                               |")
        escreval("|   VOCÊ TEM ",idade," ANOS     |")
        escreval("|          SUA MUMIA            |")
        escreval("|                       OK!     |")
        escreval("|    Press any key to continue  |")
        escreval("=================================")
        leia(validador)
        limpatela
        opcao <-0
        pergunta ()
        jogo()
        fimse

        se (idade >=5 ) e (idade <=120) entao
        escreval("=================================")
        escreval("|                               |")
        escreval("|   VOCÊ TEM ",idade," ANOS     |")
        escreval("|          PRONTO PARA O DEMO   |")
        escreval("|                       xD      |")
        escreval("|    Press any key to continue  |")
        escreval("=================================")
        leia(validador)
        limpatela
        opcao <-0
        pergunta ()
        jogo()
        fimse

              
             caso 2
             enquanto (opcao = 2) faca
             score ()
             menu ()
             fimenquanto
             menu ()
             se opcao = 1 entao
             
             dados_iniciais() //JOGO
               se (idade < 5) entao
        limpatela
        escreval("=================================")
        escreval("|                               |")
        escreval("|   VOCÊ COM MENOS DE 5 ANOS    |")
        escreval("|          SABE LER ?           |")
        escreval("|                       OK!     |")
        escreval("|    Press any key to continue  |")
        escreval("=================================")
        leia(validador)

        limpatela
           opcao <-0
        pergunta ()
        jogo()
        fimse

        se (idade > 120) entao
        limpatela
        escreval("=================================")
        escreval("|                               |")
        escreval("|   VOCÊ TEM ",idade," ANOS     |")
        escreval("|          SUA MUMIA            |")
        escreval("|                       OK!     |")
        escreval("|    Press any key to continue  |")
        escreval("=================================")
        leia(validador)
        limpatela
        opcao <-0
        pergunta ()
        jogo()
        fimse

        se (idade >=5 ) e (idade <=120) entao
        escreval("=================================")
        escreval("|                               |")
        escreval("|   VOCÊ TEM ",idade," ANOS     |")
        escreval("|          PRONTO PARA O DEMO   |")
        escreval("|                       xD      |")
        escreval("|    Press any key to continue  |")
        escreval("=================================")
        leia(validador)
        limpatela
        opcao <-0
        pergunta ()
        jogo()
        fimse

             
             senao
             fim_jogo ()
             fimse

             
             caso 3
                  fim_jogo ()
                  
                  fimse
             fimescolha
   
   caso 3
     fim_jogo ()
     
     
     fimse
     
     fimescolha









Fimalgoritmo



