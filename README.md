# Riff Empire — Preview jogável

Este repositório recebe somente versões exportadas para navegador do jogo Riff Empire.

O código-fonte, cenas editáveis, dados, testes e arte de produção ficam no repositório privado [alexpenezzicontact-web/-riff-empire](https://github.com/alexpenezzicontact-web/-riff-empire).

## Estado atual

A fundação mecânica está implementada e validada por testes headless: carreira solo ou banda, limite de integrantes, treino, ensaio, composição, gravação, negociação e execução de shows, consequências persistentes e salvamento.

O primeiro export Web ainda não foi publicado. A página pública mostra o estado de preparação até que um artefato Godot Web seja gerado. Nenhum placeholder é apresentado como se fosse o jogo.

## Como o build será publicado

1. o workflow `Export Web test build` do repositório privado gera `build/web`;
2. o artefato é validado;
3. a versão estável é copiada para este repositório;
4. o GitHub Pages serve o conteúdo de `index.html`.

A arte modular será conectada depois, sem alterar o cérebro do jogo.
