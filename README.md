# Sorteio BCR

Sistema de sorteio integrado com a API VTracker para monitoramento de ocorrências.

## Como usar

### Instalação

```bash
npm install
```

### Executar

```bash
npm start
```

O servidor estará disponível em `http://localhost:3000`

## Funcionalidades

1. **Autenticação por chave**: A aplicação solicita uma chave de acesso (API key) que será usada nas requisições à API VTracker
2. **Seleção de período**: Escolha a data/hora de início e fim para buscar as ocorrências (padrão: dia atual das 00:00:00 às 23:59:00)
3. **Busca de ocorrências**: Ao clicar em "Sortear", a aplicação busca todas as ocorrências do monitoramento ID 894 no período selecionado
4. **Visualização de resultados**: Mostra a quantidade de pessoas/ocorrências encontradas e uma tabela detalhada com os dados
5. **Trocar chave**: Permite alterar a chave de acesso a qualquer momento

## Estrutura do projeto

```
sorteioBCR/
├── server.js           # Servidor Express
├── public/
│   └── index.html     # Interface do usuário
├── package.json
└── README.md
```

