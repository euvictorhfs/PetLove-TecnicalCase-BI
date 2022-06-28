# PetLove - Case Área BI
## VAGAS: Engenharia de Dados, Ciência de Dados, Análise de Dados
### Desafio
Seu desafio é participar da equipe de Assinatura, serviço onde o dono do animal programa a entrega de um conjunto de itens dentro de um período customizado, recebendo descontos e brindes exclusivos para assinantes. 
### Problema
A equipe de assinaturas tem como objetivo reduzir a perda de assinantes. O conceito de “Churn” refere-se a perda de qualquer usuário que assinou o serviço de assinatura da Petlove e o cancelou em algum momento após a contratação. Ao analisar os dados dos últimos meses, apesar de todas as melhorias de usabilidade da plataforma, o churn vem aumentando. Aqui está o gráfico para exemplificar:

Seu trabalho será apresentar um resultado final com DOIS pontos principais:
* Quais são os Aprendizados da sua análise dos dados;
* E o que sugere como Próximos Passos.
### Sugestão de ferramentas
* Notebooks Python / Jupyter / SQL ⇒ quando o código é necessário;
* ~~PowerPoint / Apresentações Google~~ / Power BI (ou qualquer ferramenta de visualização) ⇒ apresentar os resultados para a equipe externa (Um Jupyter com bom markdown salvo em HTML sem exibir as células de códigos está ok também);
* GitHub ⇒ como um repositório para armazenar os códigos e alguma - pequena - documentação.
### Descrição das colunas
| Column | Description |
| ------ | ----------- |
| id | Identificação do cliente |
| created_at | Data de criação da assinatura |
| updated_at | Data da última modificação da assinatura |
| deleted_at | Data de cancelamento da assinatura |
| name_hash | Nome do usuário (criptografado) |
| email_hash | Email (criptografado) |
| address_hash | Endereço (criptografado) |
| birth_date | Data de aniversário do cliente |
| status | Status da assinatura |
| version | Versão da assinatura |
| city | Cidade do cliente |
| state | Estado do cliente |
| neighborhood | Bairro do cliente |
| last_date_purchase | Data do último pedido que ocorreu pela assinatura |
| average_ticket | Média de gasto por pedido |
| items_quantity | Média de itens na assinatura |
| all_revenue | Total de receita realizado pelo cliente |
| all_orders | Total de pedidos realizado pelo cliente |
| recency | Tempo desde a última compra do cliente |
| marketing_source | Canal de marketing que converteu a assinatura |
### Entrega final
* **Códigos:** seja em python / notebook ou SQL, para entender como gráficos e insights foram calculados;
* **Documentação técnica:** de preferência um README simples em markdown, para explicar a lógica do código em mais detalhes;
* **Apresentação final:** pode ser em formato PDF ou PPTX, com todos os insights para solucionar este caso.
### Critérios de avaliação
1. Explicação / retórica: quão fácil é para você explicar os conceitos?
2. Após a apresentação, os insights foram explícitos e os resultados da análise claros?
3. Qualidade do seu código: avalie o desempenho e facilidade de leitura / compreensão do conteúdo.
Algumas referências para nós são: para práticas recomendadas de código (gerais) (https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882), para o próprio python (https://google.github.io/styleguide/pyguide.html) e para o próprio SQL (https://about.gitlab.com/handbook/business-ops/data-team/platform/sql-style-guide/);
Documentação: o material possui documentação clara da lógica de cálculos?
Existe um README adequado para explicar a análise ou os resultados finais?
Lembre-se de que a documentação TÉCNICA torna seu código fácil de ser entendido, reproduzido e mantido.
Visualização: quão claros são os gráficos e quão explícitos são os eixos?
Quão simples são as ideias e quão fácil é comunicar os principais insights para a equipe de negócios?
A avaliação do projeto considera o nível da capacidade analítica, funcional e técnica.
A qualidade dos código criado, o valor de negócio do resultado da análise, assim como a apresentação dos resultados.
Próximas etapas: as ações sugeridas são úteis?
Eles resolvem os problemas de negócios da equipe de assinatura?
As próximas etapas estão claras para todos durante a apresentação?
### Importante
Nenhum modelo estatístico de previsão de churn será avaliado.
Fique à vontade para produzir e entregar outros resultados, MAS SUA PRIORIDADE é a análise e o material final para a equipe de negócio / produto.
