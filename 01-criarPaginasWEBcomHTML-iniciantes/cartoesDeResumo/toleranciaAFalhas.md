## 📌 O Que é Tolerância a Falhas?
- Permite exibir uma **mensagem alternativa** caso o **JavaScript esteja desativado** 🚫
- Ajuda a garantir que o site continue funcional para todos os usuários 🌐
- É um exemplo de **degradação normal**, planejando para cenários sem suporte 🔍

## 🏗️ Como Implementar `<noscript>`?
- Abrir `index.html` no Visual Studio Code 📂
- Adicionar o seguinte código após `</script>`:
  
   ```html
    <script src="app.js"></script>
    <noscript>You need to enable JavaScript to view the full site.</noscript>
   ```
   
- Salvar o arquivo (Ctrl+S ou Command+S) 💾
- Testar no navegador ao desativar o JavaScript temporariamente 🔄

## 🚀 Benefícios da Implementação
- Melhora acessibilidade para usuários com JavaScript desativado ✅
- Evita páginas quebradas, garantindo sempre uma mensagem útil 📢
- Ajuda na depuração, permitindo checagem rápida de suporte ao JS 🔧

## 🎭 Exemplo Lúdico: O Castelo das Portas Encantadas 🏰🔮
Imagine que você está em um castelo misterioso, onde algumas portas só se abrem com um feitiço mágico. Mas e se alguém não souber usar magia? Para garantir que todos possam entrar, você adiciona placas de instrução ao lado de cada porta!- A Porta Principal (index.html) – O espaço onde todos devem passar para explorar o castelo.
- A Magia de Abertura (JavaScript) – Permite que as portas se abram automaticamente.
- A Placa de Aviso (<noscript>) – Caso alguém não tenha magia, uma mensagem aparece explicando como proceder.

Assim como no castelo, o HTML e JavaScript precisam de alternativas para garantir que todos os usuários tenham uma experiência fluida! 🚀