# VAL-01 — Validação, usabilidade e acessibilidade

**Projeto:** ForgeSight / Lon Forge  \n**Área:** VALIDAÇÃO CONJUNTA  \n**Versão:** 1.0 (proposta de planejamento)  \n**Status:** aguardando revisão e validação técnica

Plano de testes de experiência, qualidade técnica e preparo da entrega.

## Escopo da validação

- Verificar que requisitos funcionais, arquitetura de informação e interfaces correspondem entre si.
- Combinar inspeção heurística, testes com usuário quando possível, navegação por teclado e verificações técnicas automatizadas.
- Registrar evidências e limitações de cada teste; resultado não é aprovado antes da execução.

## Casos de teste prioritários

- CT-001 | Abrir home e reconhecer propósito/CTA; esperado: proposta clara e links válidos.
- CT-002 | Navegar pelas seis coleções; esperado: nomes e destinos coerentes.
- CT-003 | Ler detalhe de produto; esperado: formato, resumo, público e status identificáveis.
- CT-004 | Testar menu mobile e teclado; esperado: ordem lógica, foco visível e retorno previsível.
- CT-005 | Revisar links e política de privacidade; esperado: nenhum link crítico quebrado.

## Acessibilidade — critérios de inspeção

- Estrutura de headings, idioma do documento, textos alternativos, rótulos e contraste testado.
- Uso apenas por teclado, foco visível, ordem de leitura, sem armadilhas e alvos adequados.
- Navegação responsiva inclusive com zoom; verificar que a interface não perde conteúdo ou operação.
- Meta WCAG 2.2 AA, sujeita à revisão manual; ferramenta automática não determina conformidade integral.

## Qualidade e desempenho

- Verificar console, recursos ausentes, layout em dimensões móveis e desktop e carregamento de imagens.
- Medir Lighthouse/Core Web Vitals quando houver ambiente publicado; não inventar pontuações nem indicadores.
- Revisar metadados de SEO, URLs canônicas se aplicáveis, headings e rastreabilidade de conteúdo.

## Registro de evidências

- Cada execução registra data, ambiente, dispositivo/navegador, passos, resultado, captura e Issue vinculada.
- Severidade sugerida: crítica (bloqueia uso), alta (compromete fluxo), média (prejudica), baixa (ajuste editorial).

## Critério de liberação

- Nenhuma falha crítica aberta; cenários prioritários aprovados ou risco formalmente aceito.
- Design revisado com o kit oficial; arquivos publicados conforme escopo; documentação atualizada e controle de versão registrado.

## Referências e rastreabilidade

- Documentação institucional Lon Forge, v3.0 (2026).
- Manual de Identidade Visual e Comunicação Lon Forge (2026).
- Base de pesquisas da marca, Google Sheets (não auditada nesta etapa).
- [Projeto GitHub](https://github.com/new) — publicar após a criação do repositório ForgeSight.

**Nota de governança:** este documento especifica uma proposta; testes, métricas e implementações só serão considerados concluídos mediante evidência verificável.
