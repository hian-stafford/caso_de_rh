# Análise de Casos de Recursos Humanos

## Descrição do Projeto
Este projeto tem como objetivo analisar um conjunto de dados contendo informações detalhadas sobre os funcionários de uma empresa, incluindo sua formação educacional, histórico profissional, dados demográficos e fatores relacionados ao emprego. O conjunto de dados foi anonimizado para garantir a privacidade dos colaboradores, ao mesmo tempo que oferece insights valiosos sobre a força de trabalho.

O dataset pode ser utilizado para diversas análises relacionadas à área de Recursos Humanos, como:
- **Retenção de funcionários**
- **Estrutura salarial**
- **Estudos de diversidade e inclusão**
- **Análise de padrões de afastamento**

## Estrutura dos Dados
O conjunto de dados contém as seguintes colunas:

1. **Educação**: Qualificação acadêmica dos funcionários (grau, instituição e área de estudo).
2. **Ano de ingresso**: Ano em que o funcionário ingressou na empresa, indicando o tempo de serviço.
3. **Cidade**: Localização dos funcionários.
4. **Nível de pagamento**: Categorização salarial dos funcionários.
5. **Idade**: Idade dos funcionários, relevante para análises demográficas.
6. **Gênero**: Identidade de gênero dos funcionários, promovendo análises de diversidade.
7. **Ever Benched**: Indica se o funcionário já esteve temporariamente sem trabalho atribuído.
8. **Experiência no domínio atual**: Tempo de experiência do funcionário na sua área de atuação.
9. **Sair ou não**: Indica se o funcionário saiu da empresa (coluna de destino para análises preditivas).

## Principais Questões de Pesquisa e Insights

1. **Qual é a distribuição das qualificações educacionais entre os funcionários?**  
   *A maior frequência observada é a de Bacharelado.*

2. **Como o tempo de serviço (ano de ingresso) varia nas diferentes cidades?**  
   *O tempo de serviço é maior em Bangalore.*

3. **Existe uma relação entre o nível de pagamento e a experiência no domínio atual?**  
   *O valor-p (0.926) é maior que o nível de significância padrão (0.05), indicando que não há uma associação significativa entre o nível de pagamento e a experiência no domínio atual.*

4. **Qual é a distribuição de gênero na força de trabalho?**  
   *A força de trabalho é composta por 63,5% de homens e 36,5% de mulheres.*

5. **Existem padrões de comportamento de afastamento entre os funcionários?**  
   *A faixa etária entre 24 e 28 anos recebe bons salários, mas também é a que mais sofre desligamentos.*

6. **Existe diferença entre o nível de escolaridade em relação à idade e ao nível de pagamento?**  
   *Com base no valor-p extremamente baixo, podemos concluir que há uma associação significativa entre nível de escolaridade e nível de pagamento.*

## Resumo Geral
A análise do conjunto de dados de RH revelou padrões interessantes na força de trabalho. A maioria dos funcionários possui formação em Bacharelado, e os funcionários em Bangalore tendem a ter um tempo de serviço mais longo. Não foi identificada uma relação significativa entre experiência no domínio atual e nível de pagamento. A distribuição de gênero é desigual, com uma maioria masculina. A faixa etária entre 24 e 28 anos apresenta uma alta taxa de demissão, possivelmente devido a altos salários. Além disso, foi confirmada uma forte associação entre nível de escolaridade e nível de pagamento.

Esses insights são fundamentais para orientar estratégias de gestão de pessoas, retenção de talentos e políticas de inclusão e diversidade dentro da empresa.

## Como Usar Este Conjunto de Dados
Pesquisadores, analistas de dados e profissionais de RH podem utilizar este dataset para:
- Construir modelos preditivos para prever a retenção de funcionários.
- Analisar tendências de diversidade e inclusão.
- Explorar padrões salariais e suas relações com experiência e formação.
- Identificar fatores de risco associados a demissões e turnover.
