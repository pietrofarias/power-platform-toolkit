# Power Platform Solutions Repository

Repositório público com soluções reutilizáveis para Microsoft Power Platform.

## Objetivo
Centralizar componentes, padrões e utilitários prontos para uso em projetos Power Apps, Power Automate e SharePoint, com foco em:
- Reutilização
- Padronização
- Aceleração de desenvolvimento
- Boas práticas arquiteturais


## Organização

- Cada solução é isolada em sua própria pasta
- Cada solução possui seu próprio README com:
  - Objetivo
  - Estrutura
  - Como usar
- Arquivos são organizados por responsabilidade:
  - `.fx` → lógica Power Fx
  - `.yaml` → componentes copiáveis (Power Apps)
  - `.json` → schemas/flows/configurações

## Tipos de soluções

- Componentes reutilizáveis (UI + lógica)
- Geradores dinâmicos (ODATA, payloads, etc.)
- Schemas padronizados
- Helpers para Power Automate
- Integrações com SharePoint

## Princípios

- Desacoplamento entre UI e lógica
- Estrutura orientada a domínio
- Extensibilidade
- Compatibilidade com SharePoint e APIs REST
- Uso mínimo de dependências externas

## Público-alvo

- Desenvolvedores Power Platform
- Arquitetos de soluções low-code
- Equipas que trabalham com SharePoint + Power Apps

## Contribuição

Sinta-se livre para:
- Sugerir melhorias
- Adaptar as soluções
- Reutilizar em projetos comerciais
