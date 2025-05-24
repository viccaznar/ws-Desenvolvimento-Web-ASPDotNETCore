# 🏗️ Editar o Corpo do HTML

## 📌 O que é o `<body>`?
- Contém o conteúdo visível da página 🖥️
- Exibe **textos, listas, imagens e interatividade** 🌐

## 📝 Estrutura Básica do `<body>`
1. **Título Principal (`<h1>`)** – Define o cabeçalho da página ✨
2. **Parágrafo (`<p>`)** – Adiciona um bloco de texto explicativo 📖
3. **Lista Não Ordenada (`<ul>`)** – Cria uma lista de elementos 📌
4. **Itens de Lista (`<li>`)** – Adiciona pontos dentro da lista 🏷️

```html
        <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Simple website</title>
        <link rel="stylesheet" href="main.css">
    </head>
    <body>
        <h1>Task List</h1>
        <p id="msg">Current tasks:</p>
        <ul>
        <li class="list">Add visual styles</li>
        <li class="list">Add light and dark themes</li>
        <li>Enable switching the theme</li>
        </ul>
    </body>
    </html>
```

## 🎨 IDs e Classes
- **ID** (`id="exemplo"`) → Aplica estilos a um elemento específico 🎨
- **Classe** (`class="exemplo"`) → Aplica estilos a vários elementos 🔄

## 💾 Salvar Alterações
- **Windows**: `Ctrl+S`
- **Mac**: `Command+S` 💾

---

# 🎭 Exemplo Lúdico: O Show de Talentos 🎤🎬

Imagine que você está organizando um grande **Show de Talentos** e precisa estruturar a apresentação dos participantes:

1. **Nome do Evento (`<h1>`)** – O título do cartaz que anuncia o espetáculo.
2. **Descrição (`<p>`)** – Um pequeno texto apresentando o evento para o público.
3. **Lista de Atrações (`<ul>`)** – Os diferentes talentos que irão se apresentar.
4. **Nomes dos Participantes (`<li>`)** – Cada artista listado como um item do show.

Além disso, para destacar um talento especial, você pode usar um **ID exclusivo** para estilizar apenas esse nome. E se quiser um visual padronizado para todos os artistas, a melhor opção é uma **Classe**!

Assim como um evento bem estruturado, **o HTML organiza o conteúdo para que os visitantes tenham uma experiência clara e envolvente**! 🚀🎤