# 🛡️ Analytics Cyber Security — Gestão de Vulnerabilidades

### Case | Engenharia de Analytics Jr. — Cyber Security

Este projeto foi desenvolvido a partir de um desafio prático para uma oportunidade de **Engenharia de Analytics em Cyber Security**.

O objetivo do case foi transformar dados brutos de ativos e vulnerabilidades em informações relevantes para apoiar a liderança na compreensão da exposição ao risco e na definição de prioridades de atuação.

Mais do que construir um dashboard, a proposta foi estruturar uma análise capaz de responder às principais perguntas do negócio:

- Qual é o nível atual de exposição ao risco?
- Quais ativos demandam maior atenção?
- Onde os esforços de correção devem ser priorizados?
- O processo atual de tratamento das vulnerabilidades está sendo efetivo?

---

## 🎯 Objetivo da análise

A partir das bases disponibilizadas, busquei construir uma visão que permitisse sair do dado operacional e chegar a uma leitura mais executiva do cenário.

O trabalho foi estruturado em quatro frentes:

**1. Qualidade dos dados**  
Identificação e tratamento de inconsistências capazes de impactar os resultados.

**2. Construção de indicadores**  
Definição das métricas mais relevantes para acompanhamento da exposição e do processo de correção.

**3. Análise e geração de insights**  
Busca por padrões, riscos, desvios e oportunidades de melhoria.

**4. Comunicação executiva**  
Transformação dos resultados em uma visão objetiva e de fácil interpretação para apoiar a tomada de decisão.

---

## 🔎 Qualificação dos dados

Antes da construção dos indicadores, as bases foram analisadas com foco em problemas semelhantes aos encontrados em ambientes corporativos reais.

Foram avaliados pontos como:

- valores ausentes;
- registros inconsistentes;
- divergências de nomenclatura;
- datas inválidas ou incoerentes;
- relacionamento entre ativos e vulnerabilidades;
- duplicidades;
- padronização de severidade, status e ambiente;
- possíveis impactos dos problemas de qualidade nos indicadores.

Quando necessário, foram adotadas regras de tratamento e premissas para evitar que inconsistências da base distorcessem a análise.

A preocupação principal foi não apenas corrigir os dados, mas entender **como cada problema poderia afetar uma decisão de negócio**.

---

## 📊 Visão executiva

Após a qualificação das bases, foram definidos indicadores para representar tanto a exposição atual quanto a efetividade do processo de tratamento das vulnerabilidades.

Entre as análises realizadas estão:

- volume total de vulnerabilidades;
- vulnerabilidades por severidade;
- vulnerabilidades críticas ainda expostas;
- distribuição por ambiente;
- distribuição por status;
- ativos com maior concentração de vulnerabilidades;
- evolução das vulnerabilidades ao longo do período;
- tempo de correção;
- idade das vulnerabilidades ainda abertas;
- efetividade da correção por severidade;
- comportamento do processo entre diferentes ambientes.

O objetivo foi evitar uma visão baseada apenas em volume e direcionar a análise para **risco, prioridade e efetividade**.

---

## 🧠 Perguntas que orientaram a análise

Durante o desenvolvimento, procurei avaliar principalmente:

> **Vulnerabilidades críticas estão sendo tratadas com maior prioridade?**

> **Ativos em produção recebem tratamento diferente dos demais ambientes?**

> **Existem vulnerabilidades críticas permanecendo abertas por períodos elevados?**

> **Quais ativos concentram maior exposição?**

> **O processo de tratamento demonstra sinais de priorização baseada em risco?**

> **Os indicadores atuais seriam suficientes para orientar uma decisão gerencial?**

Essas perguntas ajudaram a separar informações apenas interessantes daquelas com potencial de influenciar uma decisão.

---

## 💡 Abordagem analítica

A análise foi construída buscando conectar três dimensões:

### Exposição

Entender **onde o risco está concentrado** e qual é a dimensão atual do problema.

### Efetividade

Avaliar se o processo de tratamento está conseguindo responder de forma adequada às vulnerabilidades identificadas.

### Priorização

Identificar onde existem sinais de que criticidade, ambiente ou tempo de exposição deveriam influenciar mais fortemente a ordem de atuação.

---

## 📈 Dashboard executivo

Como camada final de comunicação, foi desenvolvido um painel interativo para simular como os principais indicadores poderiam ser acompanhados pela gestão ao longo dos próximos meses.

O dashboard permite explorar os dados por diferentes dimensões e aprofundar análises sem perder a visão executiva do cenário.

Entre os recursos estão:

- KPIs executivos;
- filtros interativos;
- análises por severidade, ambiente e status;
- evolução temporal;
- visualização dos ativos com maior exposição;
- detalhamento dos valores através dos gráficos;
- expansão das visualizações para análises específicas.

O uso de HTML no projeto teve como objetivo **prototipar a experiência de acompanhamento gerencial dos indicadores**, servindo como uma camada de visualização da análise.

---

## 🛠️ Tecnologias e conceitos aplicados

### Análise de dados

- Python
- Pandas
- tratamento e validação de dados
- análise exploratória
- criação e avaliação de indicadores

### Analytics

- qualidade de dados;
- relacionamento entre bases;
- regras de negócio;
- métricas de Cyber Security;
- gestão de vulnerabilidades;
- análise de tendências;
- priorização baseada em risco.

### Visualização

- HTML
- CSS
- JavaScript
- construção de dashboard executivo
- GitHub Pages

A tecnologia utilizada para apresentação foi apenas uma das etapas da solução. O foco principal do projeto está na **estruturação do problema, análise dos dados e transformação dos resultados em informações acionáveis**.

---

## 🌐 Dashboard

O painel desenvolvido para o case pode ser acessado abaixo:

**Dashboard online:**  
`https://johnerik63.github.io/Painel-Executivo-de-Vulnerabilidades/`

---

## 🚀 Sobre o case

Este projeto foi desenvolvido para demonstrar minha abordagem diante de um problema de **Analytics aplicado à Cyber Security**.

A proposta foi partir de dados brutos e estruturar uma solução que envolvesse:

**dados → qualidade → métricas → análise → insights → priorização → decisão**

Busquei construir uma visão que pudesse ser utilizada tanto por uma pessoa analista para investigação quanto por uma liderança que precisa compreender rapidamente os principais riscos e decidir onde concentrar esforços.

---

## 📌 Próximos passos

Em um cenário produtivo, a evolução natural dessa solução envolveria:

- automatização da ingestão e atualização das bases;
- construção de pipelines ETL/ELT;
- armazenamento dos dados tratados em uma camada analítica;
- definição formal das regras e métricas de negócio;
- controles de qualidade de dados;
- histórico dos indicadores;
- monitoramento automatizado;
- integração com ferramentas corporativas de BI;
- evolução das métricas de risco e Cyber Security.

Essa estrutura permitiria transformar o protótipo em um **produto analítico recorrente**, com atualização automatizada e acompanhamento contínuo da postura de segurança.

---

## ⚠️ Disclaimer

Este projeto foi desenvolvido exclusivamente como **atividade prática de processo seletivo e demonstração de conhecimento**.

Os dados utilizados fazem parte do contexto proposto no desafio e **não representam informações internas, reais ou confidenciais do Itaú Unibanco**.

Este repositório não representa uma ferramenta oficial do Itaú.

---

## 👩‍💻 Autor

**John Silva**

Projeto desenvolvido com foco na interseção entre:

**Dados • Analytics • Cyber Security • Visualização • Tomada de decisão**
