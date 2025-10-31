# Sorteio BCR

Sistema de sorteio integrado com a API VTracker para monitoramento de ocorrências.

## Como usar

Basta abrir o arquivo `index.html` em seu navegador ou acessar via GitHub Pages.

## Funcionalidades

1. **Autenticação por chave**: A aplicação solicita uma chave de acesso (API key) que será usada nas requisições à API VTracker
2. **Seleção de período**: Escolha a data/hora de início e fim para buscar as ocorrências (padrão: dia atual das 00:00:00 às 23:59:00)
3. **Filtro automático**: Remove automaticamente ocorrências onde o publicador seja "bcranapolis"
4. **Sorteio aleatório**: Ao clicar em "Sortear", a aplicação sorteia aleatoriamente um vencedor entre as ocorrências válidas
5. **Visualização do vencedor**: Mostra o vencedor em destaque com thumbnail, nome (link) e data
6. **Modal fullscreen**: Clique no thumbnail para ver a imagem em tela cheia
7. **Tabela de participantes**: Lista todos os participantes elegíveis com nome (link) e data
8. **Trocar chave**: Permite alterar a chave de acesso a qualquer momento

## Estrutura do projeto

```
sorteioBCR/
├── index.html     # Página principal (estática)
└── README.md
```

