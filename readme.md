## Jogo de Adivinhação JS

**Descrição:**

Este é um divertido jogo JavaScript onde os usuários tentam adivinhar um número secreto gerado aleatoriamente entre 1 e 1000 (inclusive). O jogo fornece feedback, indicando se o palpite está mais alto ou mais baixo que o número secreto, e controla o número de tentativas.

**Tecnologias Usadas:**

* **HTML:** Fornece a estrutura básica da página web.
* **CSS:** Estiliza os elementos visuais da página, criando uma interface atraente.
* **JavaScript:** Implementa a lógica principal do jogo, incluindo a geração do número secreto, o tratamento da entrada do usuário, o fornecimento de feedback e o controle das tentativas.

**Executando o Jogo:**

1. **Clonar ou Baixar o Repositório:**
    - Use o Git para clonar o repositório localmente:
     ```bash
     git clone [https://github.com/](https://github.com/)<seu-nome-de-usuario>/js-guessing-game.git
     ```
   - Alternativamente, baixe o arquivo ZIP do GitHub e extraia-o para o local desejado.

2. **Abrir o Arquivo HTML:**
   - Abra `index.html` em um navegador web (por exemplo, Chrome, Firefox, Edge).

**Como o Jogo Funciona:**

1. **Mensagem de Boas-Vindas:**
   - Ao abrir a página, uma caixa de alerta dá as boas-vindas ao jogo.

2. **Geração de Números Secretos:**
   - O JavaScript gera um número inteiro aleatório entre 1 e 1000 (inclusive). Este número é armazenado como o número secreto.

3. **Entrada do Usuário:**
   - Caixas de prompt aparecem, pedindo para você adivinhar um número entre 1 e 1000.

4. **Avaliação do Palpite:**
   - O JavaScript compara seu palpite com o número secreto.
     - Se o palpite estiver correto, o jogo o parabeniza e exibe o número de tentativas feitas.
     - Se o palpite estiver incorreto, o jogo fornece uma dica, indicando se o número secreto é maior ou menor que o seu palpite.

5. **Loop do Jogo (while loop):**
   - O jogo continua enquanto seu palpite não coincidir com o número secreto.
   - O número de tentativas é rastreado e exibido na mensagem final.

**Customização:**

Você pode modificar os seguintes aspectos do jogo no código JavaScript (`app.js`):

- `numeroMaximo`: Alterar o número secreto máximo possível.
- Textos de mensagens e feedback do jogo: Personalize as mensagens exibidas ao usuário.

**Observações Adicionais:**

Esta é uma implementação básica que pode ser aprimorada com recursos como:

- Validação de entrada para garantir que os usuários insiram números válidos dentro do intervalo especificado.
- Representação visual do jogo usando HTML e CSS (considere incorporar os estilos CSS existentes).
- Níveis de dificuldade com variações ajustáveis para o intervalo do número secreto.
- Rastreamento de pontuação alta.

Espero que este README.md aprimorado forneça uma visão geral clara e informativa do seu jogo de adivinhação JavaScript!
