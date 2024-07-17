# destrave-vuejs

Vue.js é um framework progressivo para construção de interfaces de usuário. Diferente de outros frameworks monolíticos, Vue é projetado desde o princípio para ser adotável incrementalmente. A biblioteca principal se concentra apenas na camada de visualização, tornando-a fácil de integrar com outras bibliotecas ou projetos existentes. Além disso, Vue é perfeitamente capaz de alimentar aplicações de página única (SPA) quando usado em combinação com ferramentas modernas e bibliotecas de apoio.

## Principais Características do Vue.js

- **Reatividade Declarativa**: Vue utiliza um sistema de reatividade que rastreia automaticamente as dependências do componente durante a renderização, otimizando o processo de atualização da interface do usuário quando os dados mudam.

- **Componentização**: Com Vue, você pode compor sua interface de usuário a partir de componentes reutilizáveis, cada um encapsulando sua própria estrutura, estilo e lógica.

- **Simplicidade e Flexibilidade**: A API de Vue é projetada para ser fácil de entender e usar, facilitando a aprendizagem para novos desenvolvedores e permitindo a flexibilidade para adaptar-se a diversas necessidades de projeto.

- **Ferramentas e Ecossistema**: Vue possui um ecossistema rico com ferramentas como Vue CLI para scaffolding de projetos, Vue Router para gerenciamento de rotas, e Vuex para gerenciamento de estado centralizado. Além disso, a comunidade ativa garante uma vasta gama de plugins e recursos.

## Exemplo Básico

Aqui está um exemplo básico de um componente Vue:

```html
<!DOCTYPE html>
<html>
<head>
  <title>Vue.js Example</title>
  <script src="https://cdn.jsdelivr.net/npm/vue@2"></script>
</head>
<body>
  <div id="app">
    {{ message }}
  </div>

  <script>
    new Vue({
      el: '#app',
      data: {
        message: 'Hello Vue!'
      }
    });
  </script>
</body>
</html>
```

Este exemplo simples cria uma instância Vue que manipula um elemento DOM com o ID `app`, exibindo uma mensagem reativa que é automaticamente atualizada na interface quando o valor de `message` muda.

## Sobre o projeto
Neste projeto, você entrará em uma tela com alguns links direcionando para os exemplos. Vá analisando o HTML respectivo
de cada página para entender como cada elemento se comporta.

## Run
Clone o repositório
```zsh
$ git clone git@github.com:victorhtl/destrave-vuejs.git
```
e abra o terminal no diretório do projeto e execute
```zsh
$ npm i
$ npm run exercicio
```
Acesse os exemplos pela url: localhost:8080