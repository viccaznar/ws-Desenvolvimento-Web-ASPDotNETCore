# 🔘 Adicionar um Botão para Alternância de Tema

## 📌 Objetivo
- Criar um **botão interativo** que permite alternar entre os **temas claro e escuro** 🌗
- Usar **HTML para estrutura**, **CSS para estilos** e **JavaScript para interatividade** 🎨⚡

## 🏗️ Passo 1: Adicionar o Botão no HTML
- Abrir `index.html` no Visual Studio Code 📂
- Adicionar um `<button>` dentro de um `<div>` após `</ul>`:

```html
   ...
        <ul>
        <li class="list">Add visual styles</li>
        <li class="list">Add light and dark themes</li>
        <li>Enable switching the theme</li>
        </ul>
        <div>
        <button class="btn">Dark</button>
        </div>
        <script src="app.js"></script>
    ...
```
- Salvar o arquivo (Ctrl+S ou Command+S) 💾

## 🎨 Passo 2: Estilizar o Botão com CSS
- Abrir main.css 📂
- Criar uma regra para .btn com cores diferentes dos temas:

    ```css
        .btn {
            position: absolute;
            top: 20px;
            left: 250px;
            height: 50px;
            width: 50px;
            border-radius: 50%;
            border: none;
            color: var(--btnFontColor);
            background-color: var(--btnBg);
        }
    ```
- Salvar o arquivo (Ctrl+S ou Command+S) 💾

## 🌗 Passo 3: Definir Estilos para os Temas Claro e Escuro
- Adicionar variáveis de cor específicas para o botão
    ```css
    .light-theme {
        --bg: var(--green);
        --fontColor: var(--black);
        --btnBg: var(--black);
        --btnFontColor: var(--white);
    }

    .dark-theme {
        --bg: var(--black);
        --fontColor: var(--green);
        --btnBg: var(--white);
        --btnFontColor: var(--black);
    }
    ```
- Salvar o arquivo (Ctrl+S ou Command+S) 💾

## 🎭 Exemplo Lúdico: O Interruptor das Estações 🌞❄️
Imagine que você tem uma cabana mágica no alto das montanhas. Dentro da cabana, há um interruptor secreto que permite alternar entre verão e inverno instantaneamente!
- O Visual da Cabana (index.html) – O espaço onde tudo acontece.
- O Botão Mágico (<button> no HTML) – O interruptor que troca entre os climas.
- Os Ajustes Climáticos (CSS) – Definem as cores e atmosfera de cada estação.

Assim como na cabana mágica, o botão HTML permite que os usuários alternem entre diferentes experiências visuais no site! 🚀
