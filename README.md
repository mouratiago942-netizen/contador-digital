# contador-digital
Contador Interativo
Esse é um projeto bem massa que fiz para treinar a base do desenvolvimento web: a interação entre o layout e a lógica. É um contador simples, mas que me ajudou a entender como o JavaScript "escuta" ou que o usuário faz na tela e responde na hora.

O que o projeto faz?
A ideia é bem direta: você tem uma viseira central e dois botões.

Clique no "+" , o número sobe.

Clique no "-" , o número desce.

Tudo acontece em tempo real, sem precisar atualizar a página.

Tecnologias que usei:

HTML5: Montei a estrutura básica, usando mainpara organizar o conteúdo e spanpara exibir o valor.
CSS3: Aqui eu foquei em deixar o visual limpo. Usei o Flexbox para deixar tudo centralizado (vertical e horizontal), trabalhei com bordas arredondadas e um fundo verde que dá um contraste legal com os botões azuis.
JavaScript: É o cérebro do projeto. Criei funções para:
Capturar ou clicar nos botões.
Pegar o valor atual, conversor de texto para número ( parseInt) e fazer a conta.
Devolver o novo valor para o HTML usando innerHTML.
