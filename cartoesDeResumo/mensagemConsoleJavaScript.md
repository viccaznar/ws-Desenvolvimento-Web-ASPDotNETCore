# 🛠️ Mensagem de Console no JavaScript

## 📌 O Que é uma Mensagem de Console?
- Permite exibir mensagens ocultas **no Console do navegador** 🔍
- Útil para **depuração** e verificação de funcionamento do código ⚡
- As mensagens **não aparecem na página da Web**, apenas nas **Ferramentas de Desenvolvedor** 🛠️

## 🚀 Como Adicionar uma Mensagem de Console?
- Abrir `app.js` no Visual Studio Code 📂
- Adicionar `console.log` dentro do manipulador de eventos:

   ```javascript
   'use strict';

    const switcher = document.querySelector('.btn');

    switcher.addEventListener('click', function() {
        document.body.classList.toggle('light-theme');
        document.body.classList.toggle('dark-theme');

        const className = document.body.className;
        if(className == "light-theme") {
            this.textContent = "Dark";
        } else {
            this.textContent = "Light";
        }

        console.log('current class name: ' + className);
    }); 
   ```
   
- Salvar (Ctrl+S ou Command+S) e testar no navegador 💾

## 🏗️ Como Ver as Mensagens no Console?
- Abrir as Ferramentas de Desenvolvedor:
- Clique com o botão direito na página e selecione Inspecionar
- Ou use o atalho F12 ou Ctrl+Shift+I (Windows/Linux) ou Option+Command+I (Mac) 🔍
- Acessar a aba "Console" para visualizar as mensagens registradas 

## 🎭 Exemplo Lúdico: O Diário Secreto do Cientista 🧪📖
Imagine que você é um cientista trabalhando em um experimento inovador. No laboratório, existem anotações invisíveis que só podem ser lidas com um equipamento especial:
- Os Frascos de Experimento (index.html) – São os elementos que precisam de ajustes na análise.
- As Notas Ocultas (console.log) – A cada nova etapa, o cientista registra um comentário secreto que só pode ser visto com instrumentos avançados.
- O Scanner de Descobertas (Console do navegador) – Permite visualizar as mensagens ocultas e entender como cada reação química ocorre.
  
Assim como no diário do cientista, usar mensagens de console em JavaScript ajuda a monitorar o funcionamento do código e resolver problemas com precisão! 🚀🔬