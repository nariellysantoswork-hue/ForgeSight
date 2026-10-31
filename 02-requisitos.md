# ENG-02 — Engenharia de requisitos

**Projeto:** ForgeSight / Lon Forge  \n**Área:** ENGENHARIA DE SOFTWARE  \n**Versão:** 1.0 (proposta de planejamento)  \n**Status:** aguardando revisão e validação técnica

Requisitos rastreáveis, histórias de usuário e critérios objetivos de aceite.

## Requisitos funcionais — versão inicial

- RF-001 | O visitante pode acessar a home e identificar marca e proposta de valor.
- RF-002 | O visitante pode navegar pelas seis coleções institucionais.
- RF-003 | O visitante pode consultar uma lista de produtos com informações essenciais.
- RF-004 | O visitante pode abrir uma página de detalhe de produto.
- RF-005 | Cada produto publicado indica seu formato, público, descrição, versão e canal de acesso quando aplicável.
- RF-006 | O visitante pode acessar informações institucionais e um canal de contato funcional.
- RF-007 | A navegação deve permanecer operável em largura móvel e desktop.
- RF-008 | As páginas devem apresentar título, descrição e estrutura semântica coerentes.

## Requisitos não funcionais

- RNF-001 | Acessibilidade: meta WCAG 2.2 nível AA, a confirmar por testes manuais e automatizados.
- RNF-002 | Desempenho: otimizar imagens, fontes e carregamento; medir antes de estabelecer limites definitivos.
- RNF-003 | Segurança: sem credenciais ou segredos no repositório; formulários só após análise de privacidade.
- RNF-004 | Manutenibilidade: componentes e estilos padronizados, nomes consistentes e revisão por pull request.
- RNF-005 | Compatibilidade: comportamento testado em navegadores modernos e tamanhos de tela representativos.
- RNF-006 | Conteúdo: não apresentar como disponível um produto sem registro editorial aprovado.

## Histórias de usuário e aceite

- HU-01 | Como visitante, quero escolher uma coleção para encontrar conteúdos da minha área de interesse. ACEITE: todas as seis coleções possuem entrada visível e destinos válidos.
- HU-02 | Como interessado, quero comparar informações básicas de um produto. ACEITE: título, formato, resumo e disponibilidade legíveis.
- HU-03 | Como visitante móvel, quero navegar sem ampliar a página. ACEITE: layout sem rolagem horizontal indevida e alvos de interação apropriados.
- HU-04 | Como gestora, quero atualizar conteúdos por arquivo versionado. ACEITE: mudança identificável por commit e revisão.

## Rastreabilidade e controle

- Associar cada RF ou RNF a uma tela WEB, arquivo de código e caso de teste VAL.
- Mudanças de requisito devem registrar motivação, impacto, responsável e versão no histórico do GitHub.
- Prioridade inicial: Must — RF-001 a RF-008; Should — filtro de catálogo; Could — favoritos locais; Won't agora — autenticação e pagamentos próprios.

## Critérios de prontidão

- Cada requisito deve ser testável, ter origem em necessidade identificada e evitar frases vagas como 'site moderno'.
- Dependências e dúvidas devem gerar issue própria antes do início de implementação.

## Referências e rastreabilidade

- Documentação institucional Lon Forge, v3.0 (2026).
- Manual de Identidade Visual e Comunicação Lon Forge (2026).
- Base de pesquisas da marca, Google Sheets (não auditada nesta etapa).
- [Projeto GitHub](https://github.com/new) — publicar após a criação do repositório ForgeSight.

**Nota de governança:** este documento especifica uma proposta; testes, métricas e implementações só serão considerados concluídos mediante evidência verificável.
