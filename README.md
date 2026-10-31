# Ponto — Encurtador de URLs e Analytics

Protótipo para criar aliases curtos, organizar links e acompanhar cliques dentro da demonstração local.

## Recursos

- Criação de links com alias personalizado ou gerado automaticamente.
- Validação de URLs `http` e `https`.
- Busca por alias ou nome e ordenação por data, popularidade ou nome.
- Cópia do link curto.
- Contagem de cliques e gráfico ilustrativo.
- Persistência local usando `localStorage`.

## Como executar

1. Baixe `encurtador-analytics.html`.
2. Abra o arquivo em um navegador atualizado.
3. Informe um endereço completo, como `https://exemplo.com/pagina`, e escolha um alias opcional.
4. Clique em um link curto listado para registrar um clique e redirecionar ao destino.

Não há instalação de dependências nem etapa de build.

## Tecnologias

- HTML
- CSS
- JavaScript
- `localStorage` e Clipboard API do navegador

## Como funciona a demonstração

Os links são registrados no armazenamento local do navegador e usam o próprio arquivo HTML como endereço-base. O clique é contado antes do redirecionamento. Os dados de origem e o gráfico inicial são ilustrativos.

## Limitações

- Os links não são encurtados por um domínio público nem funcionam para outras pessoas sem hospedagem e backend.
- Os cliques não são coletados em um servidor e não representam analytics reais.
- Cada navegador mantém sua própria lista local.
- A classificação por período é apenas demonstrativa.

## Próximas melhorias

- Criar uma API com armazenamento persistente e redirecionamento público.
- Adicionar autenticação, expiração e edição de links.
- Registrar data, dispositivo, país e origem de cada clique com controles de privacidade.
- Criar relatórios de período com filtros reais.
