# 🌗 Adicionar um Tema Claro ao Site

## 🎨 O Que é um Tema Claro?
- Um conjunto de estilos que define **cores mais suaves e brilhantes** 🌞
- Usa **códigos de cor hexadecimais** para personalizar fundo e texto 🎨
- Permite que os usuários **alternem entre diferentes temas** 🔄

## 🛠️ Como Implementar?
1. **Definir estilos no CSS (`main.css`)**:

    ```css
        .light-theme {
            color: #000000;
            background: #00FF00;
        }
    ```

   - `color: #000000;` → Define preto para o texto 🖋️
   - `background-color: #00FF00;` → Define verde para o fundo 🟢
2. **Atualizar o HTML (`index.html`)**:
   - Adicionar `class="light-theme"` ao `<body>` 📄

    ```css
        <body class="light-theme">
    ```
    
3. **Testar no navegador** para visualizar as mudanças 🌐

---

# 🎭 Exemplo Lúdico: A Galeria de Arte Interativa 🎨🏛️

Imagine que você é um **curador de uma galeria de arte**, onde os visitantes podem escolher entre **duas opções de iluminação** para apreciar as pinturas:

1. **Modo Luz do Dia (`light-theme`)** – Usa uma iluminação brilhante que realça as cores vivas das obras.
2. **Modo Noturno (`dark-theme`)** – Cria um ambiente mais aconchegante, destacando os contrastes e sombras.
3. **O Interruptor Mágico (`CSS e HTML`)** – Permite alternar entre os modos para melhorar a experiência dos visitantes.

Assim como na galeria, **permitir que os usuários escolham um tema claro melhora a acessibilidade e torna a experiência mais agradável!** 🚀✨