# 🔗 Vincular ao JavaScript

## 📌 Onde Colocar o Código JavaScript?
- Pode ser **diretamente no HTML**, mas o ideal é um **arquivo separado** 📂
- Permite **reutilização** em várias páginas sem repetir código 🔄

## 🏗️ Como Vincular um Arquivo JavaScript Externo?
1. **Criar um arquivo separado (`app.js`)** 🖥️
2. **Abrir `index.html` no Visual Studio Code** 📂
3. **Localizar `</body>` e inserir a tag `<script>` antes dele** 🎯
   - Digite `script:src` e pressione **Enter**
   - Modifique para carregar `app.js` corretamente:
     ```html
        ...
        <ul>
        <li class="list">Add visual styles</li>
        <li class="list">Add light and dark themes</li>
        <li>Enable switching the theme</li>
        </ul>
        <script src="app.js"></script>
        ...
     ```
4. **Verificar a localização**:
   - O `<script>` deve estar **após o elemento `</ul>`**
   - Colocar o `<script>` no **final do `<body>`** garante que o conteúdo carregue primeiro 📜

---

# 🎭 Exemplo Lúdico: O Maestro Digital 🎼🎻

Imagine que você é um **maestro** regendo uma orquestra. Para garantir uma **apresentação perfeita**, você precisa que todos os músicos estejam prontos antes de iniciar a sinfonia:

1. **Os Instrumentos (`index.html`)** – Cada página HTML define os elementos visuais do palco.
2. **A Partitura (`app.js`)** – O código JavaScript contém as instruções para sincronizar os músicos.
3. **O Maestro (`<script> no final do `<body>`)** – Garante que todos os instrumentos estejam afinados antes de começar a regência.

Assim como na orquestra, **o JavaScript permite coordenar interações e tornar o site dinâmico e harmônico!** 🎶🚀