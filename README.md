<h1 align="center">
    <img src="./src/assets/logo.svg" width="30px">
    <br/>Pomodoro Timer
</h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/CrisnaldoSantos/pomodoro-timer?color=00B37E"/>
  <a href="https://www.crisnaldocarvalho.com.br">
    <img alt="Made by Crisnaldo" src="https://img.shields.io/badge/made%20by-Crisnaldo Carvalho-00B37E">
  </a>
  <img src="https://img.shields.io/github/languages/top/CrisnaldoSantos/pomodoro-timer?color=00B37E">
  <img src="https://img.shields.io/github/package-json/v/CrisnaldoSantos/pomodoro-timer/master?color=00B37E">
</p>

## Descrição:

Aplicação front-end desenvolvida durante a especialização Ignite. Ela tem por objetivo implementar a técnica de pomodoro, que de forma bastante resumida, consiste em administrar o tempo empregado nas tarafes de forma que em um intervalo de tempo emprega-se concentração máxima, seguido de períodos de relaxamento, visando o aumento da produtividade.

Nessa aplicação além do temporizador foi desenvolvido uma página de histórico para validar a empregabilidade da técnica. Por se tratar de uma aplicação que funciona totalmente no lado do cliente, as informações são armazenadas no localStorage, sendo recuperadas de forma natural durante uma atualização de página.

A troca de informações entre as páginas ocorre de forma centralizada por contextos, e executada por reducers com o auxílio da biblioteca immer, que provém acesso direto e implementa a imutabilidade.

Foi criado um workflows de CI/CD no repositório, e hospedado a aplicação no firebase, a mesma pode ser acessada através do link abaixo:

https://pomodoro-timer-1364f.web.app/

## Executando Localmente

Node 18.x

Dentro do diretório execute os comandos abaixo

```
npm install
```

```
npm run dev
```

## Screenshots

<p align="center">
    <img src=".github/assets/inicial.png" width="700px">
</p>

<p align="center">
    <img src=".github/assets/andamento.png" width="700px">
</p>

<p align="center">
    <img src=".github/assets/historico.png" width="700px">
</p>
