---
title: "🏛️ CestaGov — Inteligência de Preços Públicos & Conformidade IN 65"
description: "SaaS GovTech/B2B para automação do mapa de preços de referência e expurgo estatístico de outliers sob a Lei 14.133/2021 e IN 65/2021."
tags:
  - saas
  - validacao
  - govtech
  - b2b
  - b2g
---

# 🏛️ CestaGov — Gerador de Pesquisa de Preços & Blindagem Jurídica

> **Status Atual**: Validação & Pré-MVP (Concierge)  
> **Prioridade**: Alta  
> **Modelo de Negócio**: B2B SaaS (Consultorias de Licitação) & B2G Direto (Dispensa Art. 75, II)  
> **Complexidade de Execução**: Média-Alta (Engenharia de Dados + Estatística Aplicada + Direito Administrativo)  
> **Ticket Médio Estimado**: B2B: R$ 490,00 a R$ 790,00/mês | B2G: R$ 8.400,00 a R$ 12.000,00/ano (empenho único)

---

## 🎯 1. Visão Geral & Proposta de Valor

### O Problema Real
A fase preparatória das contratações públicas no Brasil enfrenta um estrangulamento crônico na elaboração da **pesquisa de preços de mercado**, exigida pelo **Art. 23 da Lei Federal nº 14.133/2021 (Nova Lei de Licitações e Contratos - NLLC)** e normatizada pela **Instrução Normativa SEGES/ME nº 65/2021**:

1. **Gargalo Operacional Crítico**: Um município de médio porte realiza entre 150 e 400 contratações e dispensas por ano. Processos de materiais de consumo, expediente, merenda ou saúde contêm facilmente de 50 a 150 itens. Com a exigência regulamentar de no mínimo 3 cotações válidas por item, a equipe de compras precisa minerar, conferir e calcular entre 150 e 450 preços por certame.
2. **Caos dos Dados Públicos**: O Portal Nacional de Contratações Públicas (PNCP) agrega milhões de registros, mas sofre com descrições heterogêneas, erros de cadastro no CatMat/CatSer, unidades de medida discrepantes (ex: caixa com 50 vs. unidade avulsa) e distorções por frete regional embutido.
3. **Pânico do Tribunal de Contas (TCE/TCU)**: O Art. 6º, § 4º da IN 65/2021 determina que preços "inexequíveis ou excessivamente elevados" sejam expurgados. Servidores municipais utilizam planilhas básicas de Excel e realizam expurgos "no olhômetro", sem fundamentação matemática. Isso atrai apontamentos do Controle Interno e Tribunais de Contas, resultando em Tomadas de Contas Especiais (TCE) e responsabilização solidária por "erro grosseiro" no CPF do servidor (Art. 28 da LINDB).
4. **Dilema de Mercado**: Preços de referência artificialmente inflados geram risco de sobrepreço; preços excessivamente baixos provocam licitações **desertas ou fracassadas**, paralisando o fornecimento de serviços essenciais à população.

---

### A Solução
O **CestaGov** é uma plataforma analítica que automatiza de ponta a ponta a formação do Mapa Comparativo de Preços de Referência:

- **Ingestão Oficial Automatizada**: Consumo direto da API do PNCP, Compras.gov.br e painéis estaduais homologados dos últimos 12 meses.
- **Motor Estatístico de Saneamento**: Aplicação automatizada de algoritmos de saneamento (Intervalo Interquartil - IQR, Coeficiente de Variação e Desvio Padrão) para expurgo transparente de outliers.
- **Filtro de Inteligência Geográfica**: Algoritmo de aderência regional que prioriza compras do mesmo estado ou microrregião, prevenindo glosas de órgãos de controle por distorção de frete.
- **Laudo Técnico Auditável (1-Click PDF)**: Emissão de relatório oficial em PDF com memória de cálculo detalhada, identificação dos órgãos contratantes, CNPJs dos vencedores, links diretos de empenhos/atas no PNCP e fundamentação jurídica pré-formatada para anexação imediata aos autos do processo administrativo.

---

### Proposta Única de Valor (UVP)
> *"Reduza de 15 dias para 3 minutos a elaboração do Mapa de Preços de Referência da Lei 14.133/2021, com expurgo estatístico automatizado e blindagem jurídica completa perante o Tribunal de Contas."*

Diferenciais competitivos frente às ferramentas legadas (Banco de Preços, BLL, etc.):
- **Foco em Usabilidade e Agilidade**: Interface limpa e intuitiva, eliminando semanas de treinamento técnico.
- **Preço Acessível para Pequenos e Médios Atores**: Modelo comercial flexível que viabiliza o acesso por consultorias privadas e municípios do interior.
- **Motor de Expurgo Documentado**: O sistema redige a justificativa metodológica do expurgo estatístico em estrita conformidade com a jurisprudência consolidada do TCU e da IN 65/2021.

---

## 👥 2. Público-Alvo & ICP (Perfil de Cliente Ideal)

O CestaGov adota uma estratégia de duplo ICP, iniciando a tração por clientes privados (B2B) para financiar e acelerar a entrada institucional (B2G):

### ICP 1: Consultorias de Licitação & Escritórios de Direito Administrativo (B2B — Alvo Primário)
* **Perfil Demográfico**: Empresas de assessoria técnica a prefeituras e câmaras municipais, escritórios jurídicos e consultores de contratações públicas. Atendem de 3 a 25 municípios cada.
* **Decisor**: Sócio-fundador, advogado associado ou diretor operacional de compras.
* **Dor Latente**: Sobrecarga da equipe técnica; gargalo de tempo na fase interna das licitações; margem de lucro comprimida pelo custo em horas-homem de digitação e pesquisa manual em dezenas de processos simultâneos.
* **Gatilhos de Compra**:
  - Capacidade de instruir o dobro de processos por mês com a mesma equipe.
  - Entregar laudos periciais de preços que garantem aprovação imediata nas Procuradorias e Controles Internos municipais.
  - Decisão ágil de assinatura via cartão corporativo ou PIX (sem burocracia de processo público).

### ICP 2: Municípios Pequenos e Médios — 15k a 100k habitantes (B2G — Alvo Secundário)
* **Perfil Demográfico**: Prefeituras, Câmaras Municipais, Autarquias de Saneamento e Consórcios Intermunicipais.
* **Usuário Final**: Pregoeiro, Agente de Contratação, Equipe de Apoio e Servidores do Setor de Compras/Almoxarifado.
* **Decisor de Compra**: Secretário Municipal de Administração, Secretário de Finanças ou Prefeito.
* **Dor Latente**: Medo de apontamentos do TCE no CPF; processos de dispensa eletrônica parados por falta de 3 cotações válidas; softwares tradicionais de mercado com custo anual incompatível com o orçamento municipal.
* **Gatilhos de Compra**:
  - Exigência de conformidade mandatória com a Lei 14.133/2021.
  - Apontamento do Controle Interno ou recomendação de auditoria do Tribunal de Contas Estadual.
  - Viabilidade de contratação direta rápida via Dispensa de Licitação (Art. 75, II).

### Onde Encontrá-los em Massa
* **Eventos Setoriais**: Congressos Nacionais de Licitações (IBAN, Negócios Públicos, Zênite, ConLicitação), encontros estaduais de prefeituras (APM, FAMURS, AMM, etc.).
* **Canais Digitais**:
  - Grupos de WhatsApp e Telegram focados na "Nova Lei de Licitações" e "Pregoeiros do Brasil".
  - Prospecção direta no LinkedIn (*Sócio/Consultor em Licitações*, *Pregoeiro*, *Agente de Contratação*, *Secretário de Administração*).
  - Diários Oficiais dos Municípios (mapeamento de quais consultorias privadas venceram licitações de apoio técnico no estado).

---

## 💰 3. Modelo Financeiro & Unit Economics

| Indicador / Linha | Estimativa | Detalhe / Racional |
| :--- | :--- | :--- |
| **Custo Inicial de Validação (MVP)** | R$ 2.500,00 | Desenvolvimento de scripts locais, domínio .gov.br ou .com.br, template UI (Shadcn/Tailwind), infraestrutura inicial (Supabase + Render/Vercel) e verba de prospecção fria. |
| **Custo de Operação / Unidade** | R$ 28,50 / mês | Custo por organização ativa: processamento de consultas na API do PNCP, cluster PostgreSQL/Redis gerenciado, geração de PDFs via microserviço headless (Gotenberg/Typst) e envio transacional. |
| **Preço de Venda / Mensalidade** | **B2B**: R$ 490,00 a R$ 790,00/mês<br>**B2G**: R$ 8.400,00 a R$ 12.000,00/ano | **B2B**: Cobrança recorrente via cartão/boleto com relatórios ilimitados para múltiplos municípios clientes.<br>**B2G**: Contrato anual fechado faturado em parcela única ou semestral via empenho. |
| **Margem Bruta Alvo** | 92% | Modelo puramente digital de software em nuvem sem suporte presencial obrigatório e baixo consumo de banda. |
| **CAC Alvo (Custo por Cliente)** | **B2B**: R$ 350,00<br>**B2G**: R$ 1.500,00 | **B2B**: Prospecção outbound consultiva e cold messaging altamente direcionado.<br>**B2G**: Apresentações online qualificadas e fornecimento prévio da minuta técnica de contratação por dispensa. |
| **LTV Estimado (Tempo de Vida)** | **B2B**: R$ 14.700,00<br>**B2G**: R$ 36.000,00 | **B2B**: Retenção média estimada de 24 a 30 meses (churn < 3% em ferramentas operacionais de uso diário).<br>**B2G**: Contratos de dispensa/inexigibilidade renováveis anualmente por até 5 ou 10 anos (Art. 106 e 107 da Lei 14.133/2021). |

---

## 🛠️ 4. Arquitetura Operacional ou Tecnológica

```
+-------------------------------------------------------------------------+
|                  Camada de Apresentação (Next.js 14)                   |
|  - Dashboard de Cotações          - Painel de Filtros (CatMat/Região)  |
|  - Interface Human-in-the-Loop    - Visualizador & Exportador de PDF   |
+------------------------------------+------------------------------------+
                                     |
                                     v
+-------------------------------------------------------------------------+
|             Backend & Motor Estatístico (FastAPI / Python)             |
|  - Ingestão & Normalização         - Motor de Expurgo (IQR & CV)        |
|  - Gerador de Laudos (Gotenberg)  - Autenticação & Multi-tenant        |
+-------------------+--------------------------------+--------------------+
                    |                                |
                    v                                v
+------------------------------------+   +--------------------------------+
|      PostgreSQL 16 + pgvector      |   |        Redis 7 (Cache)         |
|  - Histórico de Cotações           |   |  - Cache de Consultas PNCP     |
|  - Similaridade Semântica de Itens |   |  - Filas de Processamento      |
+------------------------------------+   +---------------+----------------+
                                                         |
                                                         v
                                         +--------------------------------+
                                         |      API Externa do PNCP       |
                                         |  (pncp.gov.br/api/consulta)    |
                                         +--------------------------------+
```

### Camada de Apresentação / Frontend
* **Stack**: Next.js 14 (App Router), React 18, TypeScript, Tailwind CSS, Shadcn UI / Radix UI, Lucide Icons.
* **Componentes Principais**:
  - *Autocomplete Inteligente*: Busca preditiva de itens com classificação CatMat/CatSer e busca textual em linguagem natural.
  - *Grid Dinâmica de Propostas*: Tabela de fontes encontradas com flags automáticas (Item Homologado, Alerta de Frete, Suspeita de Inexequibilidade).
  - *Módulo Estatístico Visual*: Exibição gráfica dos limites de corte ($Q_1 - 1.5 \times IQR$ e $Q_3 + 1.5 \times IQR$), demonstrando claramente quais valores foram expurgados e por qual motivo.
  - *Painel Human-in-the-Loop*: Permite ao pregoeiro incluir ou desconsiderar propostas manualmente, exigindo registro de justificativa textual para auditoria.

### Backend, APIs & Banco de Dados
* **Engine Core**: Python (FastAPI) para pipeline estatístico e orquestração de dados assíncrona.
* **Banco de Dados Principal**: PostgreSQL 16 com extensão `pgvector` para busca por similaridade semântica em especificações técnicas de editais.
* **Camada de Cache**: Redis 7 com estratégia de cache de consultas externas do PNCP (TTL de 24h), mitigando rate limits e garantindo tempo de resposta sub-segundo.
* **Motor Estatístico**: Implementação robusta dos critérios da IN 65/2021:
  - *Expurgo por IQR (Boxplot)*: Descarte de preços fora do intervalo $[Q_1 - 1.5 \times IQR, Q_3 + 1.5 \times IQR]$.
  - *Análise de Dispersão*: Cálculo do Coeficiente de Variação ($CV = \frac{\sigma}{\mu} \times 100$). Se $CV > 25\%$, o sistema recomenda automaticamente o uso da mediana em vez da média, conforme jurisprudência do TCU (Acórdão 2.637/2015-Plenário).

### Integrações Chave
* **API do PNCP**: Coleta de contratações homologadas, atas de registro de preços e editais oficiais dos últimos 12 meses.
* **Gotenberg**: Microserviço em container para compilação de laudos em PDF institucional (A4 padronizado, paginação jurídica, carimbo temporal, hash SHA-256 e QR Code público de autenticidade).
* **Asaas / Stripe**: Gateway de cobrança para o modelo B2B SaaS (cartão de crédito e PIX com emissão automatizada de NFS-e).
* **WhatsApp API (Evolution API)**: Notificações em tempo real ao pregoeiro sobre conclusão de pesquisas em lote.

### Fluxo Operacional Passo a Passo
1. **Entrada do Objeto**: O usuário digita o item (ex: *"Resma de papel A4 75g/m² branca"*) ou faz upload de planilha de itens.
2. **Varredura Estruturada**: O sistema consulta o Redis. Em caso de cache miss, dispara requisições concorrentes na API do PNCP filtrando atas e contratações homologadas dos últimos 365 dias.
3. **Peneira Geográfica**: O algoritmo seleciona cotações prioritariamente do mesmo município, microrregião e estado. Se a amostra for inferior a 3 registros válidos, expande a busca regionalmente e, em seguida, nacionalmente, gerando justificativa automática no laudo.
4. **Sanitização Estatística**: As unidades de fornecimento são normalizadas. O motor estatístico expurga os valores discrepantes e calcula: Mediana, Média Saneada e Menor Preço.
5. **Revisão Assistida**: O pregoeiro confere as cotações na tela, desmarca eventuais marcas incompatíveis e clica em *"Homologar Cesta"*.
6. **Compilação do Laudo**: O sistema gera o PDF oficial do Mapa de Preços de Referência, com memória de cálculo, links diretos no PNCP e despacho de encerramento pronto para assinatura digital.

---

## 📣 5. Estratégia de Go-to-Market (GTM) & Vendas

### Canais de Aquisição Iniciais
1. **Outbound Consultivo para Assessorias de Licitação (B2B)**:
   - Prospecção direta no LinkedIn e contato via WhatsApp institucional de sócios de consultorias.
   - Demonstração prática resolvendo um processo real que a consultoria esteja instruindo na semana.
2. **Marketing de Conteúdo Técnico de Autoridade**:
   - Artigos técnicos assinados por Iury (Engenheiro da Computação + Gestor Público) abordando a aplicação prática da IN 65/2021 e jurisprudência dos Tribunais de Contas.
   - Distribuição de planilhas e modelos de despachos gratuitos como iscas para captura de leads qualificados.

### Ideias de Ângulos de Anúncios / Criativos

#### Ângulo 1: Focado no Medo do Tribunal de Contas (Aversão à Perda / Compliance)
> **Gancho**: *"Você ainda expurga preços de licitação no 'olhômetro' do Excel? Cuidado com o Art. 28 da LINDB."*  
> **Desenvolvimento**: *"Os Tribunais de Contas estão cobrando rigor matemático na aplicação do Art. 23 da Nova Lei de Licitações. Montar uma cesta sem memória de cálculo do expurgo estatístico pode colocar seu CPF direto na mira de uma Tomada de Contas Especial. Conheça o CestaGov: gere laudos de preços de referência blindados contra auditorias em 3 minutos."*  
> **CTA**: *"Faça um teste gratuito com um processo real da sua mesa hoje mesmo."*

#### Ângulo 2: Focado na Eficiência Operacional da Consultoria (Margem de Lucro / Tempo)
> **Gancho**: *"Sua consultoria perde 3 dias úteis apenas caçando atas para cotar 50 itens de uma compra?"*  
> **Desenvolvimento**: *"Enquanto sua equipe gasta dezenas de horas ligando para fornecedores que não respondem e garimpando o PNCP na mão, seus concorrentes estão despachando processos de compras no mesmo dia. O CestaGov varre o PNCP, elimina outliers e entrega o Mapa de Preços pronto para protocolo com um clique."*  
> **CTA**: *"Veja uma demonstração de 5 minutos com seus próprios itens."*

### Oferta de Entrada
* **Estratégia "Cavalo de Troia" para os primeiros 10 clientes pagantes (B2B)**:
  - Onboarding 1-a-1 com o fundador: a consultoria envia os itens de um processo real travado e recebe o laudo técnico pronto gratuitamente.
  - Oferecimento de 14 dias de acesso completo sem compromisso. Ao comprovar a economia de horas de trabalho, conversão no plano anual com 20% de desconto (R$ 390,00/mês).
* **Para Prefeituras (B2G)**:
  - Fornecimento da minuta completa de Termo de Referência e estudo técnico preliminar para contratação direta por **Dispensa de Licitação (Art. 75, inciso II da Lei 14.133/2021)**, com demonstração de vantajusidade econômica frente ao custo de ferramentas legadas.

---

## ⚠️ 6. Riscos, Desafios & Mitigações

### 1. Risco de Glosa por Desconsideração da Realidade Geográfica
* **Descrição**: Tribunais de Contas Estaduais (TCE-SP, TCE-MG, TCE-PR) frequentemente rejeitam cestas de preços baseadas apenas em compras de estados distantes, alegando distorção de frete e custos regionais.
* **Mitigação**: O algoritmo adota hierarquia geográfica estrita (Município -> Microrregião -> Estado -> Região -> Brasil). Quando for estritamente necessário utilizar dados de outros estados por insuficiência de amostra, o sistema insere automaticamente no laudo a justificativa jurídica fundamentada no Art. 6º, § 3º da IN 65/2021.

### 2. Risco de Instabilidade e Rate Limit na API do PNCP
* **Descrição**: A API pública do PNCP pode apresentar instabilidades temporárias, variações de layout de resposta ou lentidão em horários de pico.
* **Mitigação**: Arquitetura resiliente com Redis cache de 24h e sincronização assíncrona periódica de contratações locais em PostgreSQL. Se a API pública oscilar, o usuário continua realizando pesquisas instantâneas na base de dados já tratada e indexada no sistema.

### 3. Risco de Inadimplência e Calote Político em Contratos B2G
* **Descrição**: Prefeituras em anos eleitorais ou trocas de gestão podem suspender empenhos ou cancelar restos a pagar de serviços contínuos de TI.
* **Mitigação**: 
  1. Base de sustentação de receita centrada no B2B privado (consultorias pagando no cartão/PIX), eliminando dependência do caixa municipal.
  2. No B2G, exigência de contrato anual com empenho global prévio e cláusula resolutiva de suspensão automática do sistema após 30 dias de inadimplência (Art. 137, § 2º, IV da Lei 14.133/2021).

---

## 🗺️ 7. Roadmap de Execução & Checklist de Próximos Passos

### Fase 1 — Validação em Campo & Concierge MVP (Dias 1 a 15)
- [ ] Mapear 15 consultorias de licitação e 10 pregoeiros municipais no LinkedIn e WhatsApp.
- [ ] Desenvolver script local em Python para consumo da API do PNCP e cálculo de IQR / Desvio Padrão / Mediana.
- [ ] Elaborar manualmente 3 laudos técnicos de processos reais em andamento.
- [ ] Realizar 5 entrevistas baseadas no método "The Mom Test" para validar a percepção de valor e insegurança com o TCE.
- [ ] Testar a disposição a pagar apresentando a proposta comercial de piloto.

### Fase 2 — Construção do MVP Funcional (Dias 16 a 45)
- [ ] Configurar repositório e infraestrutura básica (Next.js 14 + FastAPI + PostgreSQL no Supabase).
- [ ] Implementar autenticação e controle multi-tenant de acessos.
- [ ] Integrar motor de busca à API do PNCP com cache Redis e normalização de medidas.
- [ ] Criar interface de saneamento de dados com gráficos de dispersão e conferência assistida.
- [ ] Desenvolver gerador de laudos em PDF institucional com QR Code de autenticidade.
- [ ] Integrar checkout Asaas/Stripe para planos recorrentes B2B.

### Fase 3 — Lançamento & Primeiras Vendas (Dias 46 a 60)
- [ ] Liberar acesso Beta para os 5 primeiros participantes da validação.
- [ ] Executar cadência outbound diária (20 contatos qualificados/dia via LinkedIn e cold messaging para consultorias).
- [ ] Distribuir o "Kit de Contratação Direta da IN 65" (Minuta de TR e Justificativa de Dispensa Art. 75, II).
- [ ] Fechar os primeiros 10 clientes pagantes no modelo B2B (MRR de ~R$ 4.900,00).
- [ ] Iniciar a tramitação de 2 processos de contratação direta por dispensa em municípios parceiros.
