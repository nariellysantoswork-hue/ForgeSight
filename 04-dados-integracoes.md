# ENG-04 — Dados, catálogo e integrações

**Projeto:** ForgeSight / Lon Forge  \n**Área:** ENGENHARIA DE SOFTWARE  \n**Versão:** 1.0 (proposta de planejamento)  \n**Status:** aguardando revisão e validação técnica

Modelo de conteúdo do catálogo e fronteiras de integração da primeira versão.

## Modelo conceitual

- Coleção: identificador, nome, slug, resumo, ordem e status editorial.
- Produto: código, título, slug, coleção, formato, descrição, público, versão, capa, estado de publicação e URL oficial quando existente.
- Recurso visual: arquivo, texto alternativo, autoria/licença e versão aprovada.
- Referência: documento de origem e data de revisão, para rastrear afirmações e decisões editoriais.

## Regras de negócio

- RN-01 | Produto não publicado não deve aparecer como disponível para compra.
- RN-02 | Produtos pertencem a uma coleção principal, com possibilidade futura de categorias secundárias.
- RN-03 | URL externa deve apontar para um canal oficial válido e ser verificada antes da publicação.
- RN-04 | Campos obrigatórios de produto: código, título, coleção, formato, resumo e status.
- RN-05 | Imagem deve possuir direitos de uso compatíveis e texto alternativo quando informativa.

## Persistência e estrutura inicial

- No MVP, dados editoriais podem permanecer em HTML ou JSON versionado. Não há banco de dados obrigatório.
- A futura entidade Cliente/Usuário não faz parte do modelo operacional do MVP; exigirá estudo separado de autenticação, consentimento, retenção e segurança.
- Usar identificadores administrativos compatíveis com a documentação institucional, como LF-TEC-001 (apenas exemplo de padrão).

## Integrações: agora e depois

- Agora: links externos oficiais para produtos e canais de comunicação, sem integração financeira ou armazenamento de leads.
- Depois: analytics, catálogo gerenciável, pagamentos, autenticação e dashboard, mediante requisitos, aprovações e contratos de serviço.
- Separar ambiente de teste e produção quando houver endpoints e segredos reais.

## Exemplo de objeto de produto

- { code: 'LF-TEC-001', title: 'Exemplo de produto', collection: 'tecnologia', format: 'ebook', status: 'draft' }
- O objeto é ilustrativo, não comprova a existência ou publicação do produto; nomes e URLs finais dependem do catálogo aprovado.

## Critérios de aceite

- Catálogo exibido apenas com registros aprovados; consistência entre coleção e produto; sem URLs de demonstração tratadas como links reais.
- Condição de expansão documentada antes de escolher banco de dados ou API.

## Referências e rastreabilidade

- Documentação institucional Lon Forge, v3.0 (2026).
- Manual de Identidade Visual e Comunicação Lon Forge (2026).
- Base de pesquisas da marca, Google Sheets (não auditada nesta etapa).
- [Projeto GitHub](https://github.com/new) — publicar após a criação do repositório ForgeSight.

**Nota de governança:** este documento especifica uma proposta; testes, métricas e implementações só serão considerados concluídos mediante evidência verificável.
