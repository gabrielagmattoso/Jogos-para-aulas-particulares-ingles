# Monster Battle

## Sobre o jogo

O Monster Battle é uma batalha entre dois alunos, cada um com o seu monstro. Em cada rodada aparece a imagem de um objeto escolar e uma frase curta em Present Continuous, no mesmo estilo dos slides da aula. Os dois alunos veem a frase ao mesmo tempo, e **quem falar primeiro ataca**: o aluno lê a frase em voz alta e imita a ação. O professor avalia e o monstro do aluno ataca o monstro do adversário. Vence quem zerar a vida do outro monstro primeiro.

O jogo foi pensado para alunos de nível inicial (B0): não há perguntas abertas para responder, apenas frases curtas, com imagens e dicas de ação que ajudam a entender o sentido.

## Objetivo da aula

Praticar a leitura, a pronúncia e a compreensão de frases em Present Continuous ligadas ao vocabulário escolar. A imitação da ação mostra que o aluno entendeu o que está dizendo, e a disputa para falar primeiro deixa a atividade rápida e competitiva.

## Conteúdo trabalhado

- Present Continuous (**am** + verbo com **-ing**) com ações da escola.
- Vocabulário escolar: notebook, pencil, schoolbook, desk, football, snack, pencil case, science, math, teachers, sports.
- Leitura em voz alta, pronúncia e compreensão (pela imitação da ação).

As frases seguem os slides da aula:

| Imagem | Frase | Ação para imitar |
|---|---|---|
| caderno | I am **writing** in my **notebook**. | fingir escrever no caderno |
| lápis | I am **writing** with a **pencil**. | segurar um lápis imaginário |
| livros da escola | I am **reading** my **schoolbook**. | abrir um livro e ler |
| carteira | I am **sitting** at the **desk**. | sentar como na carteira |
| bola | I am **playing** **football**. | chutar a bola |
| sanduíche | I am **eating** a **snack** at **school**. | fingir comer um lanche |
| estojo | I am **opening** my **pencil case**. | abrir o estojo |
| livros de Science e Math | I am **studying** **science** and **math**. | fazer cara de quem estuda |
| menino com a mão na orelha | I am **listening** to the **teachers**. | colocar a mão na orelha |
| materiais de esporte | I am **doing** **sports** and **exercise**. | fazer polichinelos |

## Como funciona

1. O professor abre o jogo no navegador, escreve o nome dos dois alunos e cada um escolhe o seu monstro (são 4 opções). Depois, clica em **FIGHT!**
2. Aparecem a imagem, a frase e a dica da ação. Os dois alunos disputam para falar primeiro.
3. O professor clica no botão do aluno que falou primeiro (ou usa as teclas **A** e **L**).
4. O professor avalia a resposta:
   - **✗ Errou:** o monstro do próprio aluno leva um dano fraco (−1 de vida).
   - **📖 Só leu:** ataque fraco, o monstro do adversário perde 1 de vida.
   - **🎭 Leu + imitou:** ataque forte, o monstro do adversário perde 2 de vida.
5. **💥 Super ataque:** depois de 3 acertos seguidos, o próximo ataque vira um super ataque e tira 3 de vida. Quando o outro aluno ataca, a sequência é zerada.
6. Cada monstro começa com **8 de vida**. Quando um monstro chega a zero, aparece o **K.O.!** e uma tela final com o vencedor e o resumo de cada aluno (quantas vezes só leu, leu e imitou, fez super ataques e errou).

O professor controla todos os cliques; os alunos participam falando e imitando.

### Atalhos de teclado

| Tecla | Ação |
|---|---|
| **A** | Aluno 1 falou primeiro |
| **L** | Aluno 2 falou primeiro |
| **1** | Só leu |
| **2** | Leu + imitou |
| **0** | Errou |

## Tecnologias utilizadas

O jogo foi desenvolvido em um único arquivo HTML, utilizando:

- **HTML5:** estrutura das telas (escolha dos monstros, arena de batalha e tela final).
- **CSS3:** layout, arena colorida, cartão da frase no estilo dos slides e animações (ataque, dano, super ataque e K.O.).
- **JavaScript puro (Vanilla JavaScript):** sorteio das frases, disputa de quem fala primeiro, regras de dano e combo, barras de vida e fim de jogo.
- **Web Audio API:** sons de ataque, erro e vitória gerados pelo próprio navegador, com botão de mudo.

Não foram utilizadas bibliotecas ou frameworks. As imagens dos objetos vêm dos slides da aula e as imagens dos monstros estão embutidas no próprio arquivo. As únicas dependências externas são as fontes *Open Sans* e *Bungee*, do Google Fonts; sem internet, o jogo usa uma fonte padrão do sistema.

## Arquivos

- `index.html`: código completo do jogo, com HTML, CSS, JavaScript e imagens no mesmo arquivo.

## Como executar

Baixe ou abra o arquivo `index.html` em um navegador atualizado. Não é necessário instalar nada.

