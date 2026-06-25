```markdown
# Conversor de Moedas

## Descrição

Aplicação web desenvolvida em HTML, JavaScript e Tailwind CSS que consome uma API pública para realizar conversões entre moedas em tempo real.

## Funcionalidades

- Conversão de moedas
- Consulta de cotação atual
- Inversão de moedas
- Histórico de conversões
- Armazenamento local usando Local Storage
- Exibição da última atualização da cotação
- Tratamento de erros
- Interface responsiva

## Tecnologias Utilizadas

- HTML5
- JavaScript (ES6)
- Tailwind CSS
- Fetch API

## API Utilizada

Exchange Rate API

https://open.er-api.com/v6/latest/USD

A API foi escolhida por ser gratuita, pública e não exigir autenticação.

## Decisões Técnicas

### Fetch API

Foi utilizada para realizar requisições assíncronas à API de câmbio.

### Tailwind CSS

Escolhido por permitir uma estilização rápida, moderna e responsiva sem necessidade de arquivos CSS adicionais.

### Local Storage

Utilizado para armazenar o histórico de conversões no navegador do usuário.

## Limitações

- Dependência da disponibilidade da API externa.
- Necessidade de conexão com a internet.
- Quantidade limitada de moedas cadastradas na interface.

## Melhorias Futuras

- Adicionar mais moedas.
- Criar gráficos de variação cambial.
- Permitir atualização automática das cotações.
- Exportar histórico em PDF ou CSV.

## Como Executar

1. Baixe os arquivos.
2. Abra o arquivo `index.html` em qualquer navegador moderno.
3. Informe o valor.
4. Escolha as moedas.
5. Clique em Converter.
```
