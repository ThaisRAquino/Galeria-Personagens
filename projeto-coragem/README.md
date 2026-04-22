# Galeria de Personagens - Rick and Morty

Aplicação web que consome a [Rick and Morty API](https://rickandmortyapi.com/) para exibir uma galeria interativa de personagens da série.

## Funcionalidades

- Listagem de personagens em cards com imagem, nome, status, espécie e origem
- Busca de personagens por nome em tempo real (via campo de texto ou tecla Enter)
- Indicador de carregamento (spinner) durante as requisições
- Mensagem de erro amigável em caso de falha na API
- Layout responsivo para desktop e mobile

## Tecnologias

- HTML5
- CSS3 (Grid, Flexbox, animações)
- JavaScript (Fetch API, manipulação de DOM)
- [Rick and Morty API](https://rickandmortyapi.com/api/character) — API pública e gratuita

## Estrutura do Projeto

```
galeria-personagens-/
└── projeto-coragem/
    ├── index.html   # Estrutura da página
    ├── styles.css   # Estilização e responsividade
    └── script.js    # Lógica de consumo da API e renderização dos cards
```

## Como Executar

1. Clone o repositório ou baixe os arquivos
2. Abra o arquivo `projeto-coragem/index.html` diretamente no navegador

Não é necessário instalar dependências ou rodar um servidor — o projeto roda 100% no lado do cliente.

## API Utilizada

**Rick and Morty API** — `https://rickandmortyapi.com/api/character`

Cada card exibe:
| Campo | Descrição |
|-------|-----------|
| Imagem | Foto do personagem |
| Nome | Nome completo |
| Status | Vivo, Morto ou Desconhecido |
| Espécie | Espécie do personagem |
| Origem | Planeta/local de origem |

## Projeto Acadêmico

Desenvolvido como projeto de estudo sobre consumo de APIs públicas com JavaScript puro.
