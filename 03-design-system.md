# WEB-03 — Design System e responsividade

**Projeto:** ForgeSight / Lon Forge  \n**Área:** WEB DESIGN  \n**Versão:** 1.0 (proposta de planejamento)  \n**Status:** aguardando revisão e validação técnica

Tokens aprovados, componentes de interface e princípios responsivos.

## Kit oficial da marca

- Cores principais: #6A00FF, #8B3DFF e amarelo #F5C400; apoio #FFD952, branco #FFFFFF, fundo #0B0A14, #14102A, #1E1A3A, #29254A, lilás #A07CFF.
- Funções tipográficas do manual: Orbitron (títulos), Montserrat (destaques) e Inter (corpo de texto). Fontes de produção devem ser obtidas de fontes licenciadas.
- Mascote: manter rosto, capuz roxo, olhos, gravata amarela e luvas; usar apenas arte original aprovada; evitar HDR e contraste adicional.

## Tokens de interface

- Cor de fundo institucional: #0B0A14; cards de apoio: #14102A; roxo de ação: #6A00FF; foco/realce: amarelo #F5C400; texto principal: #FFFFFF em fundos escuros.
- Espaçamentos propostos: base 8 px, escala 8/16/24/32/48/64; raios 8/12/16 px; componentes ajustados a contraste e conteúdo.
- Largura de leitura e grade adaptativas conforme tamanho da tela; testar textos reais antes de congelar os tokens.

## Componentes e variantes

- Botão: primário, secundário, desabilitado, carregando, hover e foco; nunca comunicar estado apenas por cor.
- Card: coleção/produto, com imagem opcional, título, descrição, etiqueta de formato e ação.
- Menu: desktop horizontal e mobile expansível; indicação de localização atual, foco visível e tecla Esc quando aplicável.
- Formulário: somente quando escopo e privacidade forem definidos; rótulos externos e mensagem de erro clara.

## Responsividade e acessibilidade

- Reorganizar layout, não apenas encolher; evitar textos sobre neon intenso e áreas de alta complexidade visual.
- Definir tamanhos mínimos dos alvos, contraste de texto, navegação por teclado e descrições alternativas onde necessárias.
- Usar critérios WCAG 2.2 AA como objetivo de projeto; avaliação prática obrigatória.

## Governança do sistema

- Prototipar componentes no Figma e registrar propriedades/nomenclatura antes de converter para CSS.
- Não redesenhar o monograma oficial nem gerar versões não aprovadas por IA; preservar arquivos mestres.
- Registrar qualquer diferença entre especificação e implementação como issue e decisão técnica.

## Referências e rastreabilidade

- Documentação institucional Lon Forge, v3.0 (2026).
- Manual de Identidade Visual e Comunicação Lon Forge (2026).
- Base de pesquisas da marca, Google Sheets (não auditada nesta etapa).
- [Projeto GitHub](https://github.com/new) — publicar após a criação do repositório ForgeSight.

**Nota de governança:** este documento especifica uma proposta; testes, métricas e implementações só serão considerados concluídos mediante evidência verificável.
