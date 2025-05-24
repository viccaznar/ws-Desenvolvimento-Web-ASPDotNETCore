# 🎯 Adicionar um Manipulador de Eventos

## 📌 O Que é um Manipulador de Eventos?
- Um manipulador de eventos **executa funções JavaScript** quando um **evento ocorre** ⚡
- No caso de um botão, o **evento "click"** é usado para **ativar uma ação** 🖱️
- Permite **modificar a página dinamicamente** com interatividade 🔄

## 🏗️ Como Implementar no JavaScript?
- Criar uma referência para o botão (`app.js`) 📂
- 
   ```javascript
    const switcher = document.querySelector('.btn');
   ```

- Adicionar um manipulador de eventos para o clique 🖱️

    ```javascript
    switcher.addEventListener('click', function() {
        document.body.classList.toggle('light-theme');
        document.body.classList.toggle('dark-theme');
    });
    ```

- Atualizar o rótulo do botão conforme o tema aplicado:
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
    });
    ```
## 🚀 Benefícios do Evento click
- Alternância automática de temas claro/escuro 🌗
- Evita código repetitivo, tornando mais eficiente 🔧
- Melhora a experiência do usuário ao permitir interação dinâmica 🖥️
  
## 🎭 Exemplo Lúdico: O Espelho Encantado 🔮
Imagine que você tem um espelho mágico, capaz de trocar sua aparência com um único toque. Mas para ativar o feitiço, você precisa de um botão encantado!- O Espelho (index.html) – Reflete sua imagem, mas pode mudar com magia.
- O Botão de Transformação (JavaScript) – Sempre que pressionado, alterna entre duas versões visuais.
- O Feitiço (toggle()) – Define qual aparência será exibida conforme o clique.
  
Assim como no espelho encantado, o manipulador de eventos permite que a página da Web alterne entre diferentes estilos com facilidade! 🚀✨

