# 🎨 Seletores no CSS

## 📌 O Que São Seletores?
- **IDs** → Estilizam um único elemento (`#msg`) 🎯
- **Classes** → Aplicam estilos a vários elementos (`.list`) 🔄
- Devem corresponder aos atributos definidos no **HTML** 🏗️

## 🏗️ Como Aplicar Seletores?
1. **Criar uma classe (`.list`)** → Estiliza múltiplos elementos 📂
2. **Criar um ID (`#msg`)** → Estiliza um único elemento 🎭
3. **Adicionar o código CSS no arquivo `main.css`** 🖊️
4. **Salvar o arquivo** (`Ctrl+S` no **Windows** ou `Command+S` no **Mac**) 💾

```css
    li {
        list-style: circle;
    }

    .list {
    list-style: square;
    }

    #msg {
    font-family: monospace;
    }
```

## 🚀 Vantagens dos Seletores
- **Reutilização** → Classes evitam repetição de código 🔄
- **Especificidade** → IDs permitem ajustes pontuais 🎨
- **Organização** → Mantêm o código mais limpo e estruturado 📜

---

# 🎭 Exemplo Lúdico: O Figurino do Espetáculo 👗🎬

Imagine que você está montando um grande espetáculo teatral e precisa definir figurinos para cada personagem:

1. **Os Trajes Coletivos (`.list`)** – Todos os dançarinos usam a mesma roupa temática.
2. **O Figurino do Protagonista (`#msg`)** – O personagem principal tem um traje único e exclusivo.
3. **O Ateliê de Costura (`CSS`)** – Onde todas as roupas são ajustadas conforme o design do espetáculo.

Assim como no figurino do teatro, **os seletores permitem que você personalize sua página com estilos específicos e organizados!** 🚀🎨