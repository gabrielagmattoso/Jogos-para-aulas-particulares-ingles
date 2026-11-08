# School Race

## Sobre o jogo

O School Race é uma corrida entre dois alunos. Em cada rodada aparece a imagem de um objeto escolar e, logo abaixo, uma frase curta em Present Continuous. O aluno da vez lê a frase em voz alta e o professor decide se acertou. Cada acerto faz o corredor avançar uma casa na pista, e vence quem chegar primeiro à linha de chegada.

O jogo foi pensado para alunos de nível inicial (B0): não há perguntas abertas para responder, apenas frases curtas, com imagens que ajudam a entender o sentido.

## Objetivo da aula

Praticar a leitura e a pronúncia de frases em Present Continuous ligadas ao vocabulário escolar, em um formato competitivo e divertido, com participação oral dos dois alunos.

## Conteúdo trabalhado

- Present Continuous (**am** + verbo com **-ing**) com ações da escola.
- Vocabulário escolar: notebook, pencil, schoolbook, desk, football, snack, pencil case, science, math, teachers, sports.
- Leitura em voz alta e pronúncia.

As frases seguem os slides da aula:

| Imagem | Frase |
|---|---|
| caderno | I am **writing** in my notebook. |
| lápis | I am **writing** with a pencil. |
| livros da escola | I am **reading** my schoolbook. |
| carteira | I am **sitting** at the desk. |
| bola | I am **playing** football. |
| sanduíche | I am **eating** snack at school. |
| estojo | I am **opening** my pencil case. |
| livros de Science e Math | I am **studying** science and math. |
| menino com a mão na orelha | I am **listening** to teachers. |
| materiais de esporte | I am **doing** sports and exercise. |

## Como funciona

1. O professor abre o jogo no navegador, escreve o nome dos dois alunos e clica em **Começar**.
2. Aparece a imagem e a frase. O aluno da vez lê a frase em voz alta.
3. O professor clica em **✓ Acertou** (o corredor avança uma casa) ou **✗ Errou**.
4. Se o aluno errar, o outro aluno pode roubar a casa repetindo a mesma frase.
5. Os alunos se revezam para começar cada rodada.
6. Quem chega primeiro à linha de chegada (5 casas) vence, mas a corrida só é decidida depois que os dois já tiveram a vez de começar. Se ainda houver empate, o jogo continua com novas rodadas até alguém ficar na frente.

O professor controla todos os cliques; os alunos participam falando.

## Tecnologias utilizadas

O jogo foi desenvolvido em um único arquivo HTML, utilizando:

- **HTML5:** estrutura da página e da pista de corrida (SVG).
- **CSS3:** layout, responsividade, modo escuro e animações da corrida.
- **JavaScript puro (Vanilla JavaScript):** sorteio das frases, revezamento dos alunos, regras de pontuação e roubo, movimento dos corredores e fim de jogo.

Não foram utilizadas bibliotecas ou frameworks. As imagens dos objetos vêm dos slides da aula e estão embutidas no próprio arquivo. A única dependência externa é a fonte *Baloo 2*, do Google Fonts; sem internet, o jogo usa uma fonte padrão do sistema.

## Arquivos

- `index.html`: código completo do jogo, com HTML, CSS, JavaScript e imagens no mesmo arquivo.

## Como executar

Baixe ou abra o arquivo `index.html` em um navegador atualizado. Não é necessário instalar nada.

