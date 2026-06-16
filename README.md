# Custom Radio Button - Choose Your Course

Um componente de formulário interativo, limpo e totalmente responsivo focado na estilização avançada de botões de seleção (Radio Buttons) utilizando exclusivamente HTML5 e CSS3. O projeto substitui o design padrão dos seletores nativos por linhas de listagem integradas (*custom list items*), proporcionando uma experiência de escolha muito mais fluida e agradável para plataformas de ensino ou checkout.

## Tecnologias Utilizadas

* HTML5: Estruturação semântica do formulário utilizando elementos de input de tipo rádio (`<input type="radio">`) e etiquetas vinculadas (`<label>`).
* CSS3: Ocultação estilizada dos seletores padrão, gerenciamento de estados visuais, bordas suavizadas e sombras projetadas.
* Flexbox: Alinhamento horizontal dos elementos dentro de cada opção de curso (seletor, título e preço) e centralização absoluta do card na tela.

## Funcionalidades e Técnicas Aplicadas

* Customização Avançada de Inputs: Uso do seletor de estado irmão (`input:checked + label`) para alterar completamente o design do bloco e do círculo seletor no momento em que o curso é escolhido.
* Organização em Linhas de Opção: Cada alternativa (HTML & CSS, JavaScript, PHP & MySQL) é estruturada como um bloco retangular cinza suave com cantos arredondados, que distribui o nome do curso e o valor anual ($100, $120 e $150) de forma simétrica nas extremidades.
* Microinterações de Seleção: Design refinado dos círculos seletores por meio de pseudo-elementos (`::before` e `::after`), criando um efeito concêntrico tátil quando ativados.
* Layout Fluido com Fundo em Gradiente: O card principal branco é destacado tridimensionalmente por meio de `box-shadow` sobre um plano de fundo com gradiente linear suave entre tons de ciano e azul.

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone 
