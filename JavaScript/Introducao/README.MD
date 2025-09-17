# Introdução ao JavaScript

JavaScript é uma **linguagem de programação interpretada** e **multiparadigma**, amplamente utilizada para desenvolvimento web.  
Junto com **HTML** e **CSS**, compõe a base da web moderna:

- **HTML** → estrutura do conteúdo  
- **CSS** → estilo e design  
- **JavaScript** → interatividade e dinamismo  

---

##  O que é JavaScript?
- Criado em 1995 por Brendan Eich.  
- É interpretado diretamente pelo navegador (sem compilação).  
- Padronizado pela **ECMAScript (ES)**.  
- Funciona tanto no **Frontend** quanto no **Backend** (Node.js).  

---

##  Principais Características
- Multiparadigma → suporta programação **imperativa**, **orientada a objetos** e **funcional**.  
- Linguagem **dinâmica** → tipos de variáveis são definidos em tempo de execução.  
- **Portabilidade** → roda em qualquer navegador moderno e também em servidores.  
- Comunidade e ecossistema extremamente ativos.  

---

##  Onde o JavaScript é usado?
- **Frontend (navegador)** → manipulação do DOM, animações, consumo de APIs.  
- **Backend (servidor)** → criação de APIs e sistemas com **Node.js**.  
- **Mobile** → desenvolvimento de apps com **React Native**.  
- **Desktop** → aplicações multiplataforma com **Electron**.  
- **IoT e Games** → suporte em diversas plataformas e engines.  

---

##  Exemplo básico
```javascript
// Exibe uma mensagem no console
console.log("Olá, mundo!");

// Manipulação de variáveis
let nome = "Lucas";
const idade = 19;

console.log(`Meu nome é ${nome} e tenho ${idade} anos.`);

// Função simples
function somar(a, b) {
  return a + b;
}

console.log(somar(5, 10)); // Saída: 15
