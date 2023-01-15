#Projeto Landing Page
Esta é uma solução para o desafio [Fylo Landing Page](https://www.frontendmentor.io/challenges/fylo-dark-theme-landing-page-5ca5f2d21e82137ec91a50fd) do site [Front End Mentor](https://www.frontendmentor.io/challenges), onde você escontra diversos desafios que vão te ajudar a melhorar na área do Front-End.

## Sumário

- [Resumo](#Resumo)
  - [Desafio](#Desafio)
  - [Screenshot](#screenshot)
  - [Link](#link)
- [Processo](#Processo)
  - [Construido com](#construido-com)
  - [O que eu aprendi](#o-que-eu-aprendi)
- [Autor](#autor)

## Resumo

O desafio é construir a Landing Page Fylo e deixá-la o mais próximo possível do design oferecido. Podendo usar qualquer ferramenta para ajudar a concluir o desafio. O objetivo é desenvolver essa Landing Page em Vue.JS que é o framework em que eu estou me aprofundando no momento.


### Desafio

Como era a minha primeira vez desenvolvendo um projeto próprio em Vue.Js, foi uma experiência pra lá de desafiadora. Meu objetivo era entender mais sobre os componentes, como funcionavam os scopos do css, e entender como todo aquele código VUE seria reproduzido na minha tela. Me dediquei a tornar o projeto o mais fiel possível ao design que recebi e acredito que obti um ótimo resultado.



### Screenshots

<p align="center"> Landing Page </p>
  <div align="center">   <img width="768px" src="./src/assets/gif.gif"></img> </div>

------


### Link: https://landing-page-561dounau-nicolasgabriiel.vercel.app

## Processo

### Construido com

-Vue.JS <br>
-TypeScript <br>
-HTML5 <br>
-CSS3 <br>
-JavaScript <br>

### Principais coisas que aprendi


Usando CSS com escopo de componente

```js
<style scoped></style>
```

Importando a Função de definir um componente (Função própria do VUE)

```js
import { defineComponent } from 'vue';
```

definindo nomes de componente através do defineComponent
```js
export default defineComponent({
  name: 'App',
});
```
Importando Componentes
```js
import LandingPage from './components/Landing-Page.vue'
```

Tornando componentes utilizaveis dentro de outro componente
```js
export default defineComponent({
  name: 'App',
  components: {
    LandingPage
  }
});
```

Utilizando componentes dentro de outro componente
```js
<template>
    <div class="landing-page">
      <Logo/>
      <Chamada/>
      <Blocos/>
      <SegundaChamada/>
      <Comentarios/>
      <Acesso/>
      <Rodape/>
    </div>
  </template>
```


## Autor

-  Site pessoal - [Nicolas Gabriel](https://www.linkedin.com/in/nicolasgabriiel/)

<div  align="center">

### Planejamento de Projeto

- [X] Planejar Projeto
- [X] Organizar os Arquivos iniciais
- [X] Montar Background da Main
- [X] Montar o Componente Cabeçalho 
- [X] Estilizar o Componente Cabeçalho 
- [X] Criar o Componente Chamada
- [x] Montar o Componente Chamada 
- [x] Estilizar o Componente Chamada 
- [x] Criar o Componente Blocos
- [x] Criar Background image no fundo
- [X] Montar o componente blocos
- [x] Estilizar o componente blocos
- [x] Adicionar Fonte
- [X] Criar componente Segunda Chamada
- [x] Montar componente Segunda Chamada
- [x] Estilizar componente Segunda Chamada
- [x] Criar o componente comentarios
- [x] Montar o componente comentarios
- [x] Estilizar o componente comentarios
- [x] Criar componente acesso
- [x] Montar o componente Acesso
- [x] Estilizar o componente Acesso
- [x] Criar Validação docomponente Acesso
- [x] Criar o Footer
- [x] Montar o Footer
- [x] Estilizar o Footer
- [x] Construir Readme
