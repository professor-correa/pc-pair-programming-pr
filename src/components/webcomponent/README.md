# Envio de Rede Social - Web Componente

Este projeto HTML/CSS tem como objetivo criar uma interface simples e elegante onde o usuário pode inserir uma rede social e clicar em um botão para enviá-la. A interface é centralizada na tela e possui um design moderno com gradiente de fundo e tipografia personalizada.

## Estrutura do Código

### HTML

```html
<div class="send">   
    <h1>Envie sua rede social.</h1>
    <input type="text" required>
    <button>Enviar</button>
</div>
```

## Explicação do Código

div class="send"
Container principal do conteúdo da página. Utiliza a classe send para aplicar centralização e espaçamento.

h1
Título principal da interface. Informa ao usuário a ação esperada: "Envie sua rede social."

input type="text" required
Campo de entrada de texto onde o usuário digita a rede social. O atributo required impede envio vazio (embora a lógica de envio ainda não esteja implementada).

button
Botão de envio. Sem funcionalidade JavaScript associada no momento, mas estilizado visualmente.