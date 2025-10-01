# BETADEV — Site Institucional

Este repositório reúne os arquivos do site estático da BETADEV, empresa especializada em soluções digitais para órgãos públicos. O projeto foi estruturado para destacar portfólio, diferenciais técnicos e canais de contato da empresa em uma única página responsiva.

## Principais recursos
- Layout 100% responsivo com Tailwind CSS via CDN e componentes customizados em `styles.css`.
- Seções de destaque para soluções, diferenciais técnicos, FAQ, time e formulário de contato.
- Elementos de SEO e marketing já configurados (metatags OG/Twitter, JSON-LD e banner de cookies com opt-in).
- Scripts frontend leves para carrosséis, FAQ acessível, consentimento de cookies e ajuste dinâmico de links/ano vigente.
- Conteúdo otimizado para acessibilidade (atalho para conteúdo, navegação por teclado, contraste e foco visível).

## Estrutura do projeto
- `index.html`: página principal com marcação semântica, copy institucional e scripts do site.
- `styles.css`: camada de estilização adicional com variáveis de cor e refinamentos de acessibilidade.
- `assets/`: imagens, ícones e manifest usados no site.

## Como executar localmente
1. Faça o download/clonagem deste diretório.
2. Abra `index.html` diretamente no navegador ou sirva o diretório com qualquer servidor estático (ex.: `npx serve .`).
3. Para editar estilos, ajuste as variáveis de cor em `styles.css` e recarregue a página.

## Personalização recomendada
- Atualize as cores de marca nas variáveis definidas no topo de `styles.css`.
- Substitua o ID do Google Analytics (`G-XXXXXXXXXX`) no script de consentimento em `index.html`.
- Revise textos de provas sociais, depoimentos e lista de cidades atendidas quando houver dados reais.
- Garanta que os links de WhatsApp e informações de contato reflitam os canais oficiais da BETADEV.

## Acessibilidade e SEO
- Padrões WCAG 2.1 AA seguidos com foco inicial acessível e controles navegáveis por teclado.
- Semântica HTML e landmarks (`header`, `main`, `section`, `nav`, `footer`) para leitores de tela.
- Dados estruturados em JSON-LD para Organização, Website, Breadcrumbs e Serviços.
- Banner de consentimento que só carrega scripts analíticos após autorização do usuário.

## Deploy sugerido
- Hospede o site em serviços de arquivos estáticos (Netlify, Vercel, GitHub Pages, Cloudflare Pages).
- Configure HTTPS e domínio customizado (`www.betadev.gov.br` ou equivalente) com redirecionamentos 301.
- Ative cache e compressão (gzip/brotli) no provedor para garantir o desempenho destacado no layout.

Sinta-se à vontade para adaptar o conteúdo conforme o posicionamento e o portfólio da BETADEV evoluírem.
