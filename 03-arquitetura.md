# ENG-03 — Arquitetura e decisões técnicas

**Projeto:** ForgeSight / Lon Forge  \n**Área:** ENGENHARIA DE SOFTWARE  \n**Versão:** 1.0 (proposta de planejamento)  \n**Status:** aguardando revisão e validação técnica

Arquitetura simples, escalável por decisão e sem complexidade prematura.

## Princípio de arquitetura

- Adotar arquitetura estática-first para a primeira entrega: HTML semântico, CSS organizado e JavaScript progressivo. Isso permite aprender os fundamentos antes de elevar a complexidade.
- O servidor distribui arquivos públicos; a renderização inicial não requer API, autenticação ou banco de dados.
- Vite/React/Next.js só entram se houver necessidade comprovada de catálogo dinâmico, roteamento complexo ou painel editorial.

## Fluxo técnico

- Conteúdo aprovado → arquivos versionados → verificação automatizada → revisão → hospedagem estática → navegador do usuário.
- Git registra alterações locais; GitHub hospeda o repositório; ambiente de desenvolvimento pode ser VS Code local ou Codespaces; deploy depende do provedor selecionado.

## Estrutura lógica

- Camada conteúdo: dados e textos revisados, imagens autorizadas e metadados das coleções.
- Camada apresentação: HTML de páginas, CSS por tokens/componentes e JS para menu e interações progressivas.
- Camada publicação: build estático opcional, verificação de links, hospedagem e cache conforme provedor.

## Registros de decisão — ADR

- ADR-001 | Usar HTML, CSS e JavaScript sem framework no MVP para garantir compreensão e pequena complexidade operacional.
- ADR-002 | Manter dados de catálogo versionados e sem informações sensíveis; avaliar JSON apenas se o volume exigir.
- ADR-003 | Não implementar compra ou login próprios na fase inicial.
- ADR-004 | Tratar a biblioteca visual aprovada como única fonte dos tokens de marca.

## Segurança e governança

- Publicar apenas material autorizado; não armazenar chaves, tokens ou dados pessoais no repositório.
- Habilitar proteção de branch, revisão e CI quando o repositório estiver hospedado.
- Registrar limitações do provedor de hospedagem conforme finalidade comercial real.

## Evolução técnica

- Quando houver necessidade real: migrar UI para componentes; adotar testes de integração; definir autenticação e LGPD antes de dados pessoais.
- Escolha de tecnologia sempre vinculada a requisito, custo, esforço e risco de manutenção.

## Referências e rastreabilidade

- Documentação institucional Lon Forge, v3.0 (2026).
- Manual de Identidade Visual e Comunicação Lon Forge (2026).
- Base de pesquisas da marca, Google Sheets (não auditada nesta etapa).
- [Projeto GitHub](https://github.com/new) — publicar após a criação do repositório ForgeSight.

**Nota de governança:** este documento especifica uma proposta; testes, métricas e implementações só serão considerados concluídos mediante evidência verificável.
