![Yu-Gi-Oh Deck Master Banner](https://copilot.microsoft.com/th/id/BCO.174f388e-9f71-466d-aa87-e6e0aa2466a2.png)

Yu-Gi-Oh! Deck Master 🎴

📌 Sobre o projeto
Este projeto foi desenvolvido como parte da atividade A2 - Projeto consumindo API.
O objetivo é criar uma página web em HTML, JavaScript e Tailwind CSS que consome a API pública YGOProDeck para pesquisar cartas de Yu-Gi-Oh.

O diferencial é que o usuário pode buscar cartas usando nomes em português do Brasil, que são traduzidos para os nomes oficiais em inglês antes da consulta na API.

🚀 Funcionalidades
Busca de cartas em português (ex: "Mago Negro").

Tradução automática para o nome oficial em inglês.

Consumo da API YGOProDeck via fetch.

Exibição responsiva das cartas com Tailwind CSS.

Informações exibidas:

Nome da carta (PT e EN)

Tipo

Descrição

Imagem oficial

🛠️ Tecnologias utilizadas
HTML5

JavaScript (ES6+)

Tailwind CSS

Fetch API

YGOProDeck API

📂 Estrutura do projeto
Código
/
├── index.html        # Página principal
└── README.md         # Documentação


📖 Como executar
Clone este repositório:

bash
git clone https://github.com/danielneyo/yu-gi-oh-deck-master.git
Abra o arquivo index.html no navegador.

Digite o nome da carta em português e clique em Invocar.

Veja os detalhes da carta renderizados na tela. 

🔗 Demo
Veja o projeto rodando em: Yu-Gi-Oh! Deck Master (danielneyo.github.io in Bing)


📜 Exemplos de cartas suportadas
Mago Negro → Dark Magician

Dragão Branco de Olhos Azuis → Blue-Eyes White Dragon

Dragão Negro de Olhos Vermelhos → Red-Eyes Black Dragon

Exodia, o Proibido → Exodia the Forbidden One

Slifer, o Dragão Celeste → Slifer the Sky Dragon

📌 Limitações
A API retorna apenas nomes oficiais em inglês, por isso foi criado um mapa de tradução para suportar nomes em português.

Apenas cartas adicionadas ao dicionário de tradução podem ser buscadas em português.

É possível expandir o dicionário para incluir mais cartas.

🤝 Contribuição
Quer ajudar a expandir o projeto?

Adicione novas traduções PT → EN no objeto traducaoCartas.

Melhore o design com Tailwind.

Crie novas funcionalidades (filtros, decks personalizados, etc.).

📄 Licença
Este projeto é de uso educacional e não possui fins comerciais.
Yu-Gi-Oh! é uma marca registrada da Konami. Este projeto utiliza dados públicos apenas para fins de estudo.
