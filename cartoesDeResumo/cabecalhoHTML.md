# 🏗️ Editar o Cabeçalho do HTML

## 📌 O Que é o `<head>`?
- Contém informações sobre o site que não aparecem na página 🌐
- Guarda **metadados** como conjunto de caracteres, scripts e configurações 🔍

## 🎭 Importância do `<title>` 
- Aparece na parte superior da janela do navegador 🏛️
- Usado pelos mecanismos de busca para identificar o site 🔎
- Vamos adicionar um título personalizado! 🖋️

```html
   ...
   <head>
      <meta charset="utf-8">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Simple website</title>
   ...
```

## 🎨 CSS Interno vs Externo
- **CSS Interno**: Escrito dentro do arquivo HTML 🎨
- **CSS Externo**: Arquivo separado (`main.css`) para melhor organização 🏗️
- Permite aplicar estilos a várias páginas sem repetir código 🔄

## 🔧 Como Vincular o CSS Externo?
- Adicionar o código de link
- No **Visual Studio Code**, após `<title>`, digite `link` e pressione **Enter** ⚡:

```html
   <link rel="stylesheet" href="">
```

- Atualizar o href
- Modifique para: `href="main.css"` 📁
- Salvar o Arquivo
- Windows: `Ctrl+S`
- Mac: `Command+S` 💾

---

# 🎭 Exemplo Lúdico: O Espetáculo Virtual 🎬

Imagine que você está organizando um grande show de teatro online. Para que o público tenha a melhor experiência, você precisa de três elementos fundamentais:

1. **O Anúncio do Espetáculo (`<title>`)** – Define o nome da apresentação que aparecerá nas propagandas e na entrada do teatro.
2. **O Roteiro e Cenas (`<head>` e Metadados)** – Contém detalhes essenciais que garantem que os artistas e a iluminação sigam o script corretamente.
3. **Figurino e Cenário (CSS Externo)** – Em vez de desenhar roupas para cada ator individualmente, você cria um **design único e elegante** e aplica a todos.

Com essa organização, seu espetáculo será um sucesso, **assim como uma página HTML bem estruturada**! 🎭🚀