# Show do Blingão - Como Jogar

Bem-vindo ao Show do Blingão! Teste seus conhecimentos sobre o sistema Bling e veja se você consegue chegar ao prêmio de R$ 1 milhão!

### 🧠 Escolha seus Assuntos

Na tela inicial, você pode personalizar sua partida! Escolha um ou mais dos quatro temas disponíveis para focar nas áreas que você mais domina ou quer testar. Se você se sentir confiante, selecione todos e jogue o modo completo!

### 🏆 Ranking dos Melhores

Acha que foi bem? Confira a tela de Ranking! Lá você pode ver os 5 melhores jogadores para cada um dos assuntos e também um ranking "Geral" para quem joga com todos os temas. A pontuação só é salva no ranking de um assunto específico se você jogar apenas com ele selecionado, ou no ranking "Geral" se jogar com todos os temas.

### 💡 Use suas Ajudas

Cada jogador tem duas ajudas disponíveis por partida, use-as com sabedoria!

* **Pular:** Não sabe a resposta? Use esta ajuda para pular a pergunta sem perder o prêmio acumulado.
* **Eliminar 2:** Está em dúvida entre as alternativas? Use esta ajuda para eliminar duas das respostas incorretas, aumentando suas chances de acertar.

### 💾 Salve sua Pontuação

Se sua pontuação for alta o suficiente para entrar no Top 5 de uma categoria, você terá a opção de salvar seu nome no ranking no final do jogo. O ranking é salvo diretamente no seu navegador.

---

# Histórico de Versões

## Versão 2.0 - 10/08/2025

Esta versão representa uma grande atualização, focando na personalização da experiência do jogador e na modernização da arquitetura do jogo.

### Novas Funcionalidades

* **Seleção de Assuntos:** Adicionada uma seção na tela inicial onde os jogadores podem escolher um ou mais temas para as perguntas do jogo ("Módulo Outros", "Módulo Integrações", "Módulo Fiscal", "Atendimento").
* **Ranking por Assunto:** A tela de ranking foi completamente redesenhada com abas, permitindo visualizar os 5 melhores jogadores para cada assunto individualmente, além de um ranking "Geral" para quem joga com todos os temas selecionados.
* **ID da Pergunta:** O ID de cada pergunta agora é exibido no canto superior esquerdo da tela de jogo para facilitar a identificação e o reporte de possíveis erros.

### Melhorias e Mudanças

* **Banco de Dados de Perguntas:** A base de 500 perguntas foi migrada do código-fonte para o Firestore, tornando o carregamento mais rápido e a manutenção mais fácil.
* **Ranking Local:** O sistema de ranking foi simplificado, removendo a dependência do Firestore e passando a salvar os recordes apenas no histórico do navegador (`localStorage`).
* **Interface do Usuário (UI):** Foram feitos diversos ajustes de layout na tela inicial para melhor organização e na tela do jogo para garantir o alinhamento correto dos elementos em diferentes resoluções.
* **Carregamento Otimizado:** A mensagem "Perguntas carregadas" foi removida para uma experiência mais limpa, e a mensagem de status agora só aparece se houver algum erro no carregamento.

## Versão 1.0 - (Data da Criação Inicial)

Versão inicial do jogo, estabelecendo a base da jogabilidade.

* **Criação do Jogo:** Lógica principal do "Show do Milhão" implementada.
* **Estrutura de Prêmios:** Definidos os 15 níveis de prêmios, com valores seguros.
* **Ajudas:** Implementadas as opções "Pular Pergunta" e "Eliminar 2 Alternativas".
* **Banco de Perguntas Interno:** As perguntas e respostas estavam contidas diretamente no arquivo HTML.
* **Ranking Simples:** Sistema de ranking básico que salvava a pontuação no navegador.
