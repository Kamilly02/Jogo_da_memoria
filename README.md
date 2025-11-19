🧠 ##Jogo da Memória

Um projeto simples e divertido desenvolvido com HTML, CSS e JavaScript, onde o usuário testa sua memória encontrando pares de cartas iguais. As cartas são geradas dinamicamente, embaralhadas e possuem toda a lógica do jogo controlada via JavaScript.

🚀 Funcionalidades

🔄 Geração dinâmica das cartas
As cartas são criadas automaticamente via JavaScript.

🎴 Embaralhamento aleatório
Os ícones são duplicados e embaralhados usando lógica de array.

🔁 Efeito de virar carta
Animação visual controlada por classes CSS.

✔️ Verificação de pares
O jogo identifica se as cartas são iguais ou não.

⏳ Reset automático de cartas erradas
Caso o par esteja errado, as cartas viram de volta após um pequeno atraso.

🧩 Estado do jogo controlado no JavaScript
Variáveis como firstCard, secondCard, lockBoard, etc., garantem que a lógica funcione corretamente.

🧱 Estrutura do Projeto
HTML

- Estrutura simples com um contêiner principal.

- Um título para o jogo.

- Um game board onde as cartas são inseridas dinamicamente.

CSS

- Centraliza o jogo na tela.

- Estiliza o tabuleiro e as cartas.

- Diferencia cartas viradas e cartas corretas com estilos diferentes.

- Usa efeitos visuais para tornar o jogo mais agradável.

- JavaScript

- Responsável por toda a mecânica do jogo:

- Criação do array de ícones

- Duplicação e embaralhamento

- Renderização dinâmica das cartas

- Eventos de clique

- Lógica de comparação

- Bloqueio da jogada enquanto verifica o par

- Reset automático do board

🧠 Como Funciona a Lógica

- O JavaScript cria uma lista de ícones.

- Os ícones são duplicados para formar pares.

- A lista é embaralhada.

- Cada carta é criada e adicionada ao tabuleiro.

- Quando o jogador clica:

- A carta vira.

- Se for a primeira carta, só registra.

- Se for a segunda, compara com a primeira.

- Se forem iguais → ficam viradas e marcadas como combinadas.

- Se forem diferentes → voltam a ficar viradas após um breve intervalo.

🖥️ Como Rodar o Projeto

Baixe ou clone este repositório.

Abra o arquivo index.html no seu navegador.

Jogar! 🎉

📌 Melhorias Futuras

- Contador de jogadas

- Timer

- Tela de vitória

- Temas de cartas diferentes
