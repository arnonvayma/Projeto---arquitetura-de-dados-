Arquitetura de Dados aplicada à análise pluviométrica, fluviométrica e registros oficiais — Estado de São Paulo

📘 Descrição do Projeto

Este projeto investiga se a chuva é realmente o principal fator responsável pelos desastres hidrológicos ocorridos no estado de São Paulo. Embora seja comum associar enchentes, alagamentos e deslizamentos diretamente à precipitação, estudos recentes e bases oficiais revelam que essa relação é mais complexa.

A análise combina dados de:

Pluviometria e fluviometria (SAISP/USP)

Registros de desastres (Atlas Digital de Desastres no Brasil)

Séries temporais e correlações estatísticas

Utilizando técnicas de ciência de dados, modelagem e visualização, o projeto busca compreender como diferentes variáveis hidrológicas e urbanas interagem e influenciam a ocorrência desses eventos.

🎯 Objetivo do Estudo

O objetivo central é verificar se a precipitação é realmente o fator determinante para desastres hidrológicos nos municípios paulistas — com foco especial na bacia do rio Atibaia.

A pergunta norteadora é:

“A chuva isoladamente explica a ocorrência de desastres hidrológicos?”

🧪 Metodologia
🔍 1. Coleta de Dados

Atlas Digital de Desastres no Brasil

SAISP/USP – Sistema de Alerta a Inundações de São Paulo

🧼 2. Tratamento e Processamento

Executado em Python (Jupyter Notebook):

limpeza e padronização dos datasets

unificação e organização cronológica

criação de indicadores (médias mensais, agregações)

modelagem básica de séries temporais

📊 3. Análises e Visualização

gráficos comparativos PLU × FLU × Desastres

tabelas de médias, picos e variação sazonal

análise de correlação

dashboard executivo no Power BI

🌧️ Dados analisados

Média mensal de pluviometria (PLU)

Média mensal de fluviometria (FLU)

Quantidade de desastres por município

📈 Principais Resultados

A investigação mostrou que, no município de Valinhos, a chuva não é o principal fator responsável pelos desastres hidrológicos.

Fatores urbanos apresentaram impacto significativamente maior, como:

impermeabilização do solo

urbanização acelerada

infraestrutura de drenagem insuficiente

ocupação de áreas suscetíveis a risco

Além disso:

A correlação entre chuva e desastres foi baixa.

A variabilidade do nível do rio não respondeu proporcionalmente ao aumento de precipitação.

Eventos críticos ocorreram mesmo em meses com baixa chuva.

Esses aspectos reforçam que o problema é multifatorial — e não puramente meteorológico.

🧭 Conclusão

O estudo conclui que:

A chuva é apenas um dos fatores que contribuem para desastres hidrológicos — e frequentemente não é o mais decisivo em ambientes urbanos.

Para análises mais robustas e modelos preditivos eficazes, recomenda-se integrar:

variáveis meteorológicas

indicadores de urbanização

dados socioeconômicos

informações geoespaciais

características da drenagem urbana

A pesquisa também destaca a importância de políticas públicas focadas em:

planejamento territorial

drenagem eficiente

gestão de risco

ocupação controlada em áreas vulneráveis
