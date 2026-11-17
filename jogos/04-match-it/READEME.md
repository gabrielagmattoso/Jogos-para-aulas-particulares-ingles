# Match It!

## Sobre o jogo

O Match It! é um jogo de associação entre dois alunos, jogado em turnos alternados. Em cada rodada aparece o desenho de uma cena e, ao lado, três frases em Present Continuous. O aluno da vez olha o desenho e fala qual frase combina com ele; o professor clica na frase que o aluno disse e dá (ou não) o ponto.

Depois das rodadas, o jogo termina com uma rodada de **True or False**: aparece um desenho e uma frase, e o aluno diz se a frase combina com o desenho ou não.

O jogo foi pensado para alunos de nível inicial (B0): as frases são curtas, sempre com uma imagem grande que ajuda a entender o sentido, e o aluno só precisa falar — não há nada para digitar.

## Objetivo da aula

Fazer o aluno associar a frase em inglês à imagem correta, ouvindo e falando em voz alta, em um formato competitivo em que os dois alunos participam e se revezam.

## Conteúdo trabalhado

- Present Continuous (**is / are** + verbo com **-ing**).
- Vocabulário de animais e partes do corpo.
- Vocabulário de profissões.
- Compreensão de frase por imagem e produção oral curta.
- Estruturas de comparação e reação: **True / False**, **I think it's...**.

### Frases do tema "Animals & Body Parts"

| Imagem | Frase |
|---|---|
| cachorro e gato com fones | The dog and cat **are listening** to music. |
| tigre correndo | The tiger **is running**. |
| pássaro e morcego voando | The bird and the bat **are flying**. |
| menino lavando as mãos | The boy **is washing** his hands. |
| urso lavando as patas | The bear **is washing** its paws. |
| pato comendo pão | The duck **is eating** with its beak. |
| Superman voando | Superman **is flying**. |

### Frases do tema "Professions"

| Imagem | Frase |
|---|---|
| cozinheiro | The chef **is cooking** pizza. |
| médica com um paciente | The doctor **is helping** a boy. |
| astronauta na Lua | The astronaut **is jumping** on the moon. |
| veterinária com um tigre | The vet **is helping** a tiger. |
| professora com um livro | The teacher **is reading** a book. |
| engenheiro com uma planta de casa | The engineer **is drawing** a house. |
| piloto | The pilot **is flying** a plane. |
| dançarina | The dancer **is dancing**. |
| fazendeiro | The farmer **is working** on the farm. |
| músico com violão | The musician **is playing** the guitar. |

## Como funciona

1. O professor abre o jogo no navegador, escreve o nome dos dois alunos, escolhe o **Timer** (Off, 10s, 15s ou 20s) e clica em um dos temas: **Animals & Body Parts** ou **Professions**.
2. Cada aluno tem **5 rodadas**, e as vezes se alternam: rodada 1 é do Aluno 1, rodada 2 do Aluno 2, e assim por diante.
3. Aparece o desenho e três frases (A, B e C). O aluno da vez fala qual frase combina com o desenho.
4. O professor clica na frase que o aluno disse:
   - **acertou:** a frase fica verde e o aluno ganha **1 ponto**;
   - **errou:** a frase fica vermelha e abre a chance de **roubo**.
5. **🔥 Steal (roubo):** quando o aluno erra ou o tempo acaba, a outra criança pode responder e ficar com o ponto.
6. **⏰ Cronômetro:** quando o tempo da vez acaba, a rodada vai direto para o roubo.
7. **✔ True or False:** no final, são **4 frases** sobre os desenhos (2 verdadeiras e 2 falsas). Cada acerto vale **1 ponto**.
8. No fim aparece o **🏆 vencedor**, com o placar somando as rodadas e a rodada de verdadeiro ou falso.

O professor controla todos os cliques; os alunos participam falando.

### Atalhos de teclado

| Tecla | Ação |
|---|---|
| **A**, **B**, **C** | Escolhe a frase correspondente |
| **T** / **F** | Marca True ou False |
| **Enter** ou **Espaço** | Avança para a próxima rodada |

## Tecnologias utilizadas

O jogo foi desenvolvido em um único arquivo HTML, utilizando:

- **HTML5:** estrutura das telas (menu, rodada, roubo, verdadeiro ou falso e tela final).
- **CSS3:** layout, cores dos dois alunos, barra do cronômetro e animações de acerto e erro.
- **JavaScript puro (Vanilla JavaScript):** embaralhamento das cartas, sorteio das opções, turnos alternados, cronômetro, regra de roubo, rodada de verdadeiro ou falso e placar final.
- **Web Speech API:** botão **🔊 Listen**, que fala a frase em inglês pelo próprio navegador.

Não foram utilizadas bibliotecas ou frameworks. As 17 ilustrações estão embutidas no próprio arquivo. A única dependência externa são as fontes *Fredoka* e *Nunito*, do Google Fonts; sem internet, o jogo usa uma fonte padrão do sistema.

## Arquivos

- `index.html`: código completo do jogo, com HTML, CSS, JavaScript e imagens no mesmo arquivo.

## Como executar

Baixe ou abra o arquivo `index.html` em um navegador atualizado. Não é necessário instalar nada.

