# ENG-05 — Especificação para desenvolvimento

**Projeto:** ForgeSight / Lon Forge  \n**Área:** ENGENHARIA DE SOFTWARE  \n**Versão:** 1.0 (proposta de planejamento)  \n**Status:** aguardando revisão e validação técnica

Contrato de implementação, qualidade e passagem para front-end.

## Estrutura inicial do código

- index.html: entrada principal; assets/css/style.css: tokens e estilos; assets/js/script.js: interações progressivas; assets/images/: recursos otimizados.
- docs/: documentação de engenharia, web design, validação e marketing; pdfs/: versões de leitura; .github/workflows/: verificações automatizadas.
- A estrutura evolui conforme a arquitetura real, sem criar pastas vazias desnecessárias.

## Padrões de implementação

- HTML: semântica correta, headings hierárquicos, links com destinos reais, labels e descrições acessíveis.
- CSS: tokens de marca, unidades fluidas, layouts com flex/grid, estados de foco e breakpoints baseados no conteúdo.
- JS: eventos pequenos, tratamento de estados, ausência de dependências desnecessárias e funcionamento básico sem JS quando viável.

## Processo Git e colaboração

- Criar issues pequenas para cada RF; desenvolver em branch nomeada (ex.: feat/catalogo-colecoes); abrir pull request com resumo e checklist.
- Usar commits descritivos e revisão de alterações. Nunca incluir senhas, arquivos sensíveis ou artes sem autorização.
- Registrar decisões arquiteturais relevantes em Markdown com identificação ADR.

## Estratégia de testes

- Testes exploratórios e de navegação em desktop/mobile; validação de teclado, foco, headings e links.
- Verificar erros de console, responsividade, peso das imagens e resultados de Lighthouse, sem considerar sua pontuação como substituto de teste humano.
- Quando surgirem funções de negócio, escrever testes automatizados específicos; avaliar Playwright na evolução.

## Definição de pronto — DoD

- RF aceito, conteúdo revisado, visual compatível com brand kit, acessibilidade essencial verificada e nenhum erro crítico conhecido.
- PR documentado, teste registrado, link funcional e implantação validada no ambiente apropriado.
- Pendências não bloqueadoras registradas com prioridade explícita.

## Entrega entre áreas

- O Web Design entrega tokens, componentes, estados e protótipos; Engenharia entrega requisitos, dados e critérios de aceite; Front-end implementa os dois conjuntos sem reinterpretar regras de marca.
- Cada tela implementada aponta para RFs, especificação WEB e casos VAL correspondentes.

## Referências e rastreabilidade

- Documentação institucional Lon Forge, v3.0 (2026).
- Manual de Identidade Visual e Comunicação Lon Forge (2026).
- Base de pesquisas da marca, Google Sheets (não auditada nesta etapa).
- [Projeto GitHub](https://github.com/new) — publicar após a criação do repositório ForgeSight.

**Nota de governança:** este documento especifica uma proposta; testes, métricas e implementações só serão considerados concluídos mediante evidência verificável.
