# ForgeSight — Lon Forge

**Planejamento de Produto, Engenharia de Software e Web Design**  
Versão 1.0 — documentação técnica inicial.

> Repositório local preparado para publicação. A criação remota no GitHub requer acesso à conta ou envio manual dos arquivos.

## Produto inicial
Site institucional e catálogo de produtos digitais da Lon Forge, marca multitemática de Educação, Tecnologia, Negócios, Ideias & Relações, Carreira e Recursos Digitais.

**Escopo MVP:** navegação institucional, coleções, informações de produtos aprovados, contatos, responsividade, SEO básico e acessibilidade. Login, pagamentos próprios e plataforma educacional completa ficam fora do escopo inicial.

## Documentação

- [Plano Mestre](docs/visao-geral/00-plano-mestre.md)
- [ENG-01 Escopo e MVP](docs/engenharia/01-escopo-mvp.md)
- [ENG-02 Requisitos](docs/engenharia/02-requisitos.md)
- [ENG-03 Arquitetura](docs/engenharia/03-arquitetura.md)
- [ENG-04 Dados e integrações](docs/engenharia/04-dados-integracoes.md)
- [ENG-05 Especificação técnica](docs/engenharia/05-especificacao-tecnica.md)
- [WEB-01 Arquitetura da informação](docs/web-design/01-arquitetura-informacao.md)
- [WEB-02 Fluxos e wireframes](docs/web-design/02-fluxos-wireframes.md)
- [WEB-03 Design System](docs/web-design/03-design-system.md)
- [WEB-04 Protótipo](docs/web-design/04-prototipo.md)
- [VAL-01 Validação](docs/validacao/01-usabilidade-acessibilidade.md)

Os PDFs correspondentes estão em [`pdfs/`](pdfs/). Os arquivos `.md` são editáveis e adequados à revisão pelo GitHub.

## Fontes e identidade

- Referência institucional: *Lon Forge — Documentação Institucional, Estratégica e Metodológica*, v3.0, 2026.
- Referência visual: *Lon Forge — Manual de Identidade Visual e Comunicação*, 2026.
- [Planilha central de Marketing](https://docs.google.com/spreadsheets/d/1rmEED5aF9o9780pwALSBzl8_hqTMOBYOmM9KEEgTUcI/edit)

**Cores oficiais:** `#6A00FF`, `#8B3DFF`, `#F5C400`, `#FFD952`, `#FFFFFF`, `#0B0A14`, `#14102A`, `#1E1A3A`, `#29254A`, `#A07CFF`.  
**Fontes de marca indicadas no manual:** Orbitron (títulos), Montserrat (destaques), Inter (texto). Nos PDFs utilizou-se Lato embutida como substituta editorial quando as três famílias não estavam disponíveis no ambiente; os arquivos web continuam configurados para as fontes oficiais com fallback.  
**Imagem de capa:** recorte inalterado de arte do próprio manual visual; não substitui arquivo mestre do logotipo ou mascote.

## Execução da demonstração

O `index.html` é uma **estrutura demonstrativa inicial**, sem catálogo final ou vendas ativas. Abra no navegador ou use Live Server no VS Code. Os links de coleção funcionam como âncoras; textos e produtos finais dependem de aprovação editorial.

## Processo de colaboração

`Issue → Branch → Pull Request → Revisão → Teste → Commit/Deploy`. Não versionar dados pessoais, senhas ou segredos.

## Estados

Os documentos especificam propostas de planejamento. Não declaram testes de usabilidade, métricas ou integração operacional como já concluídos.
