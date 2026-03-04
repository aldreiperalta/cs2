# 🎯 CS2 Analytics Hub

Repositório dedicado ao estudo tático, análise de performance e estatísticas detalhadas de jogadores e equipes profissionais de **Counter-Strike 2**.

## 🚀 Guia Rápido de Início
Se você está começando uma nova análise agora, siga estes passos:

1.  **Extração de Dados:** Siga o nosso [Guia de Extração com Go](./analise/Guia%20de%20Extração%20de%20Dados:%20CS2%20Demos%20com%20Go) para transformar suas demos em CSV.
2.  **Padronização:** Utilize o [Modelo de Análise](./analise/modelo%20de%20analise) para documentar seus insights.

## 🗂️ Estrutura do Repositório

O projeto está organizado para facilitar a busca por organizações e pro-players específicos:

* **`/analise`**: Contém ferramentas, scripts (Go/R) e modelos de documentação.
* **`/Equipes`**: (Em breve) Pastas divididas por organizações (ex: FURIA, NaVi).
* **`/Jogadores`**: (Em breve) Subpastas contendo análises individuais e heatmaps.

## 🏷️ Metatags & Filtros

Cada análise possui um cabeçalho (Frontmatter) para padronização:
* **Mapa:** Mirage, Inferno, Nuke, etc.
* **Lado:** TR ou CT.
* **Função:** AWP, Entry Fragger, Lurker, IGL.

## 🛠️ Ferramentas Utilizadas

* **Parser:** [demoinfocs-golang](https://github.com/markus-wa/demoinfocs-golang)
* **Linguagens:** Go (Extração) e R (Análise Estatística).
* **Documentação:** Markdown & RMarkdown.

---
*Mantido por [aldreiperalta](https://github.com/aldreiperalta). Sinta-se à vontade para contribuir!*
