
<h1 align="center"> 
	maxApp
</h1>

# Tabela de conteúdos
<!--ts-->
   * [Proposta e descrição](#proposta-e-descrição)
   * [Solução](#solução)
   * [Componentes e Funcionalidades](#componentes-e-funcionalidades)
   * [Como utilizar](#como-utilizar)
		* [Visualização dos dados do cliente](#visualização-dos-dados-do-cliente)
		* [Visualização do histórico de pedidos](#visualização-do-histórico-de-pedidos)
		* [Visualização das legendas do histórico de pedidos](#visualização-das-legendas-do-histórico-de-pedidos)
		* [Visualização dos alvarás](#visualização-dos-alvarás)
   * [Demonstrações](#demonstrações)
      * [Splash Screen](#splash-screen)
      * [Tela principal](#tela-principal)
      * [Tela dados do cliente](#tela-dados-do-cliente)
      * [Tela histórico de pedidos](#tela-histórico-de-pedidos)
      * [Caixa de legendas](#caixa-de-legendas)
      * [Tela de alvarás](#tela-de-alvarás)
   * [Arquitetura](#arquitetura)
	   * [Atual](#atual)
	   * [Desejável](#desejável)
<!--te-->

## Proposta e descrição
Este é um [desafio proposto pela MaximaTech](https://github.com/lucasrmoro/Android/blob/master/README_CHALLENGE.md) com o intuito de testar os conhecimentos do desafiante em Android. O Aplicativo conta com várias telas, dentre elas estão uma para listar os dados do cliente, outra para listar o histórico de pedidos e por fim a lista de alvarás

## Solução
Desenvolver o design e as funcionalidades do aplicativo utilizando Kotlin, Retrofit, MVVM Architecture, Jetpack Components.

## Componentes e Funcionalidades

|                Componentes e Funcionalidade                     |  Já implementado(a) |
| --------------------------------------------------------------- | :-----------------: |
| Splash Screen                                                   |         ✔️           |
| Menu principal com botôes funcionais                            |         ✔️           |
| Botão para verificar status do cliente                          |         ✔️           |
| Bottom Navigation View Funcional                                |         ✔️           |
| Tela histórico de pedidos com legendas                          |         ✔️           |
| Seta para voltar para tela anterior                             |         ✔️           |
| Campo de pesquisa na tela de hist. de pedidos                   |         ❌          |

## Como utilizar

### Visualização dos dados do cliente
Para visualizar os dados do cliente, pressione o primeiro botão da tela principal denominado "Clientes".
&nbsp;
### Visualização do histórico de pedidos
Para visualizar o histórico de pedidos, pressione o segundo botão da tela principal denominado "Pedidos".
&nbsp;
### Visualização das legendas do histórico de pedidos
Para visualizar o as legendas do histórico de pedidos, dentro da tela de histórico de pedidos pressione o botão pontilhado no canto superior direito e pressione "Legendas".
&nbsp;
### Visualização dos alvarás
Para visualizar os alvarás, antes você precisará pressionar um dos botões citados acima e navegar pela barra de tarefas inferior do aplicativo, sendo o últímo botão a direita, denominado "Alvarás".
&nbsp;

## Demonstrações

### Splash Screen:

<img src="https://github.com/lucasrmoro/Android/blob/master/img/splash-screen.jpeg" width="250" height="500" />

### Tela principal:

<img src="https://github.com/lucasrmoro/Android/blob/master/img/tela-principal.jpeg" width="250" height="500" /> 

### Tela dados do cliente:

<img src="https://github.com/lucasrmoro/Android/blob/master/img/tela-dados-do-cliente.gif" width="250" height="500" /> 

### Tela histórico de pedidos:

<img src="https://github.com/lucasrmoro/Android/blob/master/img/tela-hist%C3%B3rico-de-pedidos.gif" width="250" height="500" /> 

### Caixa de legendas:

<img src="https://github.com/lucasrmoro/Android/blob/master/img/caixa-legendas.jpeg" width="250" height="500" /> 

### Tela de alvarás:

<img src="https://github.com/lucasrmoro/Android/blob/master/img/tela-alvar%C3%A1s.jpeg" width="250" height="500" /> 

## Arquitetura

### Atual:

<img src="https://github.com/lucasrmoro/Android/blob/master/img/currently-architecture.png" width="600" height="500" /> 

### Desejável:

<img src="https://github.com/lucasrmoro/Android/blob/master/img/final-architecture.png" width="600" height="500" /> 
