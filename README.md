# Adivinhe o Número

Jogo de adivinhação feito no Scratch como primeiro projeto prático de programação. O computador escolhe um número secreto entre 1 e 10, e o jogador tenta descobri-lo fazendo palpites. A cada erro, o jogo indica se o palpite foi baixo demais ou alto demais.

## Objetivo

Praticar os fundamentos da programação, como variáveis, condições, operadores de comparação e repetições, em um projeto simples e completo.

## Como jogar

1. Clique na **bandeira verde** para começar.
2. Leia a pergunta, digite um palpite e confirme.
3. O jogo responde "Muito baixo" (o palpite é menor que o número secreto) ou "Muito alto" (o palpite é maior).
4. Repita até acertar. Ao acertar, aparece a mensagem "Você acertou! A resposta era" seguida do número secreto.
5. Para jogar de novo, clique na **bandeira verde**.

## Tecnologias

- Scratch 3.0, linguagem de programação visual por blocos
- HTML, CSS e JavaScript apenas na amostra visual, que não faz parte do jogo

## Conceitos aplicados

- **Variáveis:** `alvo` guarda o número secreto. Ao começar, o bloco "ocultar variável" esconde o valor na tela.
- **Operadores aleatórios:** "escolher número aleatório de 1 a 10" sorteia o número secreto.
- **Condições:** o bloco "se ... senão" escolhe entre a dica "Muito baixo" e a dica "Muito alto".
- **Operadores de comparação:** `=` verifica se o palpite é igual ao número secreto, e `<` verifica se o palpite é menor.
- **Repetições:** o bloco "repetir até que" mantém o jogo pedindo palpites até o acerto.
- **Eventos:** "quando bandeira verde clicada" inicia o jogo. Clicar nela de novo reinicia a partida.
- **Juntar:** o bloco "juntar" monta a mensagem final com o número secreto.
- **Esperar:** "esperar 1 segundo" pausa antes de pedir o próximo palpite.

## Amostra visual

A pasta `amostra/` contém uma página (`amostra/index.html`) que mostra o script do projeto com as mesmas peças e a mesma ordem. Ela executa o script passo a passo, destacando o bloco que está rodando, e traz um quebra-cabeça em que você monta o script clicando nas peças na ordem certa.

A amostra serve para visualizar a ideia e estudar o funcionamento. O projeto oficial é o arquivo `adivinhe-o-numero.sb3`. Para ver a amostra, baixe a pasta e abra `amostra/index.html` em qualquer navegador.

## Estrutura do repositório

- `adivinhe-o-numero.sb3`: projeto Scratch editável, compatível com o Scratch 3.0 oficial.
- `amostra/index.html`: amostra visual do script, com execução passo a passo e quebra-cabeça.
- `imagens/`: arte usada no projeto, em SVG, com o fundo do palco (`fundo-palco.svg`) e o personagem (`personagem.svg`).
- `README.md`: apresentação e documentação do projeto.

## Como abrir o projeto

1. Acesse o editor do Scratch em https://scratch.mit.edu/projects/editor/
2. Clique em **Arquivo > Carregar do seu computador**.
3. Selecione o arquivo `adivinhe-o-numero.sb3`.

## Como o código está organizado

O projeto tem um único script, no personagem "Jogo". Ele começa quando a bandeira verde é clicada: sorteia o número secreto, esconde a variável e faz a primeira pergunta. Depois, repete a comparação entre o palpite e o número secreto, mostrando a dica adequada e pedindo um novo palpite até o acerto. Por fim, exibe a mensagem de vitória.

## Créditos

Projeto desenvolvido como exercício prático do curso [CS50's Introduction to Programming with Scratch](https://pll.harvard.edu/course/cs50s-introduction-programming-scratch), da Universidade Harvard.
