# 🌑 Adicionar um Tema Escuro ao Site

## 🏗️ Preparação para Alternância de Temas
- Criar uma estrutura para **habilitar a troca entre temas claro e escuro** 🔄
- Definir variáveis globais no CSS para facilitar a manutenção do código 🎨

## 🚀 Como Implementar o Tema Escuro?
1. **Definir constantes no início do arquivo CSS (`main.css`)** 🏗️
   - Usar o seletor `:root` para configurar **variáveis globais** 🌍
  
     ```css
    :root {
        --green: #00FF00;
        --white: #FFFFFF;
        --black: #000000;
    }
     ```

2. **Atualizar o seletor de temas** (`light-theme` e `dark-theme`) 🌗
   - No final do CSS, substituir a regra `light-theme` e adicionar `dark-theme`:
  
     ```css
    .light-theme {
        --bg: var(--green);
        --fontColor: var(--black);
    }
    .dark-theme {
        --bg: var(--black);
        --fontColor: var(--green);
    }
     ```

3. **Modificar o seletor `<body>`** para aplicar o novo tema 🌑
   - O `<body>` herda estilos definidos no tema ativo:
  
     ```css
    body {
        background: var(--bg);
        color: var(--fontColor);
        font-family: helvetica;
     }
     ```

4. **Remover regras desnecessárias** (`#msg` e `ul`) 🧹
   - Isso garante que todos os elementos herdem os estilos corretamente

## 🔄 Alternando Entre Temas
- **Editar manualmente** a classe no `<body>` dentro do `index.html`:
  - Trocar de `light-theme` para `dark-theme` 🔄
- **Salvar (`Ctrl+S` ou `Command+S`)** e **recarregar a página (`F5` ou `Ctrl+R`)** 💾

## Código Completo

```css
:root {
  --green: #00FF00;
  --white: #FFFFFF;
  --black: #000000;
}

body {
  background: var(--bg);
  color: var(--fontColor);
  font-family: helvetica;
}

li {
  list-style: circle;
}

.list {
  list-style: square;
}

.light-theme {
  --bg: var(--green);
  --fontColor: var(--black);
}

.dark-theme {
  --bg: var(--black);
  --fontColor: var(--green);
}
```

---

# 🎭 Exemplo Lúdico: O Cinema Interativo 🎬🌗

Imagine que você está projetando um **cinema interativo** onde os espectadores podem escolher a iluminação da sala:

1. **Modo Luz do Dia (`light-theme`)** – A sala está bem iluminada, ideal para leitura do programa antes do filme.
2. **Modo Sessão Noturna (`dark-theme`)** – As luzes se apagam e a tela se destaca, criando uma atmosfera envolvente.
3. **O Interruptor Secreto (`CSS e HTML`)** – Com um único clique, o ambiente do cinema se transforma instantaneamente.

Assim como no cinema, **o CSS permite que os usuários alternem entre diferentes experiências visuais no site!** 🚀🎬