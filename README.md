# Jogo do Número Secreto

Este é um projeto desenvolvido como parte do curso da Oracle Next Education, com o objetivo de treinar lógica de programação utilizando JavaScript, HTML e CSS. O jogo consiste em adivinhar um número secreto dentro de um intervalo definido.

## 🚀 Funcionalidades

O jogo gera um número aleatório e desafia o usuário a adivinhá-lo.

O sistema informa se o chute do usuário é maior ou menor que o número secreto.

O jogo conta a quantidade de tentativas até a resposta correta.

O botão de reiniciar jogo permite iniciar uma nova rodada.

Utiliza a Web Speech API para leitura das mensagens na tela (quando suportado pelo navegador).

## 🛠 Tecnologias Utilizadas

HTML: Estrutura da página web.

CSS: Estilização e layout da interface.

JavaScript: Lógica do jogo e interatividade.

## 📜 Como Funciona

O jogo inicia exibindo uma mensagem pedindo ao usuário que escolha um número dentro de um limite predefinido.

O usuário digita um número e clica no botão para verificar se acertou.

Se o chute for incorreto, o jogo dá dicas sobre se o número secreto é maior ou menor.

Quando o usuário acerta, uma mensagem de sucesso é exibida junto com a quantidade de tentativas utilizadas.

O botão "Reiniciar" permite jogar novamente com um novo número secreto.

## 🔧 Estrutura do Código

### Funções principais

`gerarNumeroAleatorio()`: Gera um número secreto evitando repetições até esgotar todas as opções.

`verificarChute()`: Compara o chute do usuário com o número secreto e exibe mensagens.

`exibirTextoNaTela(tag, texto)`: Atualiza o texto na tela e, se possível, usa a API de voz para leitura.

`limparCampo()`: Limpa o campo de entrada do usuário após cada tentativa.

`reiniciarJogo()`: Reinicia o jogo gerando um novo número secreto e resetando tentativas.

## 🎮 Como Jogar

Abra o arquivo index.html em um navegador.

Digite um número dentro do intervalo especificado.

Clique no botão "Chutar".

Leia as dicas até acertar o número.

Clique em "Reiniciar Jogo" para jogar novamente.
