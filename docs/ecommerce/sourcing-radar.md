---
title: "SourcingRadar: Inteligência Aduaneira e Arbitragem E-commerce"
description: "Motor algorítmico de garimpo e arbitragem China-Brasil com cálculo tributário exato (Remessa Conforme + ICMS por dentro) e projeção de margem líquida para Mercado Livre e Shopee."
tags:
  - ecommerce
  - validacao
---

# 🚀 SourcingRadar: Inteligência Aduaneira & Arbitragem E-commerce

> **Status Atual**: Validação (Concierge MVP de 72h)  
> **Prioridade**: Alta  
> **Modelo de Negócio**: Híbrido — Clube VIP de Inteligência Executiva (Concierge / Info-Membership) escalando para Micro-SaaS B2B  
> **Complexidade de Execução**: Baixa (Fase Concierge) a Média (Fase SaaS)  
> **Ticket Médio Estimado**: R$ 47,00/mês (Mensal) | R$ 147,00 (Trimestral) | R$ 247,00 (Semestral)  

---

## 🎯 1. Visão Geral & Proposta de Valor

### O Problema Real
Vendedores de marketplaces no Brasil (Mercado Livre e Shopee) enfrentam uma taxa de mortalidade financeira alarmante ao tentar importar produtos da China. Esse problema é sustentado por três dores viscerais:
1. **A Guilhotina Aduaneira do ICMS "Por Dentro"**: Com a entrada em vigor do Remessa Conforme e da Lei nº 14.993/2024 ("Taxa das Blusinhas"), a tributação de importação tornou-se matematicamente traiçoeira. O lojista calcula uma alíquota nominal de 20% (até US$ 50) ou 60% (acima de US$ 50), mas é destruído pelo cálculo do ICMS estadual cobrado "por dentro", que eleva a carga tributária efetiva para **~44% a 51%** abaixo de US$ 50 e **~92% a 105%** acima de US$ 50.
2. **Cegueira de Custos Operacionais Ocultos**: A precificação amadora ignora a mordida composta de comissões de marketplace (12% a 19%), taxas fixas por unidade (R$ 6,00 a R$ 6,50 abaixo de R$ 79), frete reverso obrigatório (arrependimento em 7 dias previsto no CDC) e o imposto Simples Nacional que incide sobre o **faturamento bruto**, resultando em operações com "lucro ilusório" e queima acelerada de caixa.
3. **A Armadilha do Retrovisor do AvantPro e Nubimetrics**: As ferramentas dominantes do mercado mostram o que **já vendeu muito** no Brasil. Quando o produto aparece no topo dessas plataformas, o mercado nacional já está saturado e commoditizado. O lojista compra o lote na China, aguarda 25 a 40 dias de transporte e, ao receber o estoque, encontra centenas de concorrentes queimando o preço de venda abaixo do seu custo de reposição.

### A Solução
O **SourcingRadar** é uma solução de inteligência de abastecimento (*supply-side intelligence*) baseada em um motor proprietário em Python (`aliexpress-finder`). O sistema:
- Realiza raspagens automatizadas e integrações no AliExpress e Alibaba, filtrando fornecedores com alta reputação (nota maior ou igual a 4.7 estrelas) e excluindo anúncios enganosos com filtros semânticos anti-pegadinha (separando acessórios avulsos do produto real).
- Aplica o cálculo tributário exato do desembaraço aduaneiro brasileiro na vírgula (II + dedução de US$ 20 quando aplicável + ICMS por dentro + frete internacional Choice/Direto), apurando o **Landed Cost Real (R$)**.
- Cruza o custo na porta com a precificação mediana nos marketplaces locais (Mercado Livre e Shopee), abatendo comissões, taxas fixas e impostos de faturamento para entregar o **Lucro Líquido Real (R$)** e o **ROI (%)** de cada lote.
- Entrega oportunidades prontas e mastigadas para o lojista, eliminando a paralisia por análise.

### Proposta Única de Valor (UVP)
> *"Enquanto o AvantPro te mostra o que os outros já venderam ontem, o SourcingRadar te entrega o que você compra amanhã na fábrica chinesa com o imposto calculado na vírgula e a margem líquida blindada no bolso."*

---

## 👥 2. Público-Alvo & ICP (Perfil de Cliente Ideal)

### Quem é o Cliente Ideal (ICP)
- **Perfil Demográfico/Empresarial**: Homens e mulheres, 22 a 45 anos, atuando como MEI (Microempreendedor Individual) ou ME (Microempresa no Simples Nacional) faturando entre R$ 5.000 e R$ 80.000/mês nos marketplaces.
- **Momento de Vida**: Já fizeram suas primeiras 10 a 50 vendas no Mercado Livre ou Shopee; perceberam que comprar de atravessadores do Brás/25 de Março espreme a margem para menos de 15%; querem importar da China, mas têm pânico de ter o lote barrado em Curitiba ou receber uma DARF com imposto impagável.
- **Volume de Compra**: Possuem entre R$ 800 e R$ 10.000 de capital de giro disponível para investir em pequenos lotes e giros rápidos de estoque.

### Onde Eles Estão (Canais de Concentração)
- **Grupos de WhatsApp e Telegram**: Centenas de comunidades ativas de "Vendedores Mercado Livre", "Shopee Sellers Brasil", "Importação Legalizada" e grupos de alunos de mentorias (Efeito Empreendedor, Academia do E-commerce).
- **Mercado Livre / Shopee (Busca Direta)**: Anúncios de sellers intermediários (termômetro verde, 50 a 500 vendas/mês) cujos dados de contato e CNPJ constam na consulta pública de Nota Fiscal.
- **YouTube e Instagram**: Seguidores de canais de e-commerce e importação buscando atalhos e listas de fornecedores nos comentários.

### Gatilhos de Compra
- **Medo da Perda**: Lembrança recente de ter tomado prejuízo em um lote encalhado ou de ter sido taxado em 100% de surpresa pela Receita Federal.
- **Desejo de Atalho e Praticidade**: Exaustão operacional de passar 4 horas por noite garimpando sites chineses sem saber se a conta fecha.
- **Ganho Imediato Desproporcional**: O valor da assinatura (R$ 47 a R$ 97) é pago com o lucro da venda de apenas **1 a 2 unidades** do lote recomendado no dossiê.

---

## 💰 3. Modelo Financeiro & Unit Economics

A estratégia financeira adota a regra de ouro do *bootstrapping*: **Monetização Concierge prévia com custo marginal zero** para financiar a futura infraestrutura de software.

### Tabela de Unit Economics e Métricas Projetadas

| Indicador / Linha | Estimativa | Detalhe / Racional |
| :--- | :--- | :--- |
| **Custo Inicial de Validação (MVP)** | **R$ 0,00** | Uso do script Python local existente (`aliexpress-finder`), exportação em Excel e montagem de PDF executivo no Notion/Canva. |
| **Custo de Operação / Unidade** | **R$ 0,00 a R$ 2,00** | Custo marginal de entrega por membro (praticamente nulo via WhatsApp/Telegram). Na fase SaaS, ~R$ 180 a R$ 350/mês total para VPS e proxies. |
| **Preço de Venda / Mensalidade** | **R$ 47,00/mês**<br/>**R$ 147,00 (Trimestral)**<br/>**R$ 247,00 (Semestral)** | Plano trimestral como padrão de entrada (*anchor pricing*) para neutralizar o risco de churn no segundo mês. |
| **Margem Bruta Alvo** | **90% a 95%** | Deduz apenas a taxa da plataforma de checkout (Kiwify/Kirvano/Asaas ~7% a 8%). |
| **CAC Alvo (Custo por Cliente)** | **R$ 0,00 (Orgânico)**<br/>**R$ 15,00 a R$ 30,00 (Ads)** | Foco inicial 100% em guerrilha orgânica e prospecção direta. Em tráfego pago futuro, teto de R$ 30 para plano trimestral de R$ 147. |
| **LTV Estimado (Tempo de Vida)** | **R$ 140,00 a R$ 220,00** | Com venda forçada de planos trimestrais/semestrais na entrada, o LTV médio sobe mesmo com churn natural após a compra do estoque. |

---

## 🛠️ 4. Arquitetura Operacional ou Tecnológica

O sistema divide-se em duas etapas: a **Fase 1 (Motor Local Concierge)** e a **Fase 2 (Plataforma Web SaaS)**.

### Camada de Apresentação / Frontend
- **Fase 1 (MVP)**: Zero frontend de software. A entrega ocorre via **Dossiê Executivo de Arbitragem Tributada** diagramado em PDF institucional (gerado no Notion/Canva) e disparado em grupo fechado no WhatsApp/Telegram.
- **Fase 2 (SaaS)**: Painel web minimalista em Next.js / Tailwind CSS com autenticação Supabase, onde o usuário visualiza cards de oportunidades diárias, pesquisa por URL do AliExpress e simula cenários tributários em tempo real.

### Backend, APIs & Banco de Dados
- **Motor de Coleta (`src/clients/`)**:
  - `direct_scraper.py`: Coletor baseado em Playwright Stealth e cabeçalhos emulados para extração direta de preços em Reais, frete Choice e dados de catálogo.
  - `official_api.py`: Conector para a API Oficial TOP Protocol do AliExpress (com assinatura HMAC-SHA256) para requisições seguras via App Key e App Secret de Afiliado/Dropshipping.
- **Motor Tributário e Financeiro (`src/finance/`)**:
  - `taxes.py`: Implementa as fórmulas oficiais da aduana brasileira:
    - Conversão do valor aduaneiro via AwesomeAPI (cotação do Dólar PTAX).
    - Imposto de Importação (II): 20% para remessas até US$ 50; 60% com abatimento fixo de US$ 20 para remessas acima de US$ 50.
    - Base de Cálculo do ICMS por dentro: `Base = (Preço + Frete + II) / (1 - Alíquota_ICMS)`.
    - Custo Final na Porta (Landed Cost em R$).
  - `margins.py`: Dedução das comissões do canal de venda (12% a 19% no Mercado Livre ou 14% a 20% na Shopee + taxas fixas por unidade vendida), Simples Nacional (4% a 7%) e cálculo do Lucro Líquido Real em Reais e do ROI percentual.
- **Filtros Anti-Pegadinha e Semânticos (`src/filters/`)**:
  - `anti_trick.py`: Detecta e expurga variações enganosas onde o menor preço do anúncio é referente a cabos, baterias, caixas vazias ou pulseiras avulsas.
  - `semantic.py`: Inclusão mandatória de atributos de qualidade e exclusão estrita de réplicas de marcas patenteadas.

### Integrações Chave
- **Checkout & Faturamento**: Kiwify, Kirvano ou Asaas (com recebimento automático via Pix e liberação imediata de acesso).
- **Comunicação**: WhatsApp Business API / Z-API e canal estruturado no Telegram.
- **Câmbio**: AwesomeAPI (atualização diária da cotação do dólar comercial).

### Fluxo Operacional Passo a Passo (Fase Concierge)
1. **Segunda-feira 07:00**: O fundador roda o motor Python localmente com parâmetros de margem líquida superior a 35% e fornecedores com nota acima de 4.7.
2. **Segunda-feira 09:00**: O script exporta a planilha de oportunidades brutas (`oportunidades_alibaba.xlsx`). O fundador audita manualmente as 3 a 5 oportunidades mais incontestáveis.
3. **Segunda-feira 11:00**: Os dados são consolidados no Dossiê Semanal em PDF (contendo fotos, link da fábrica, memória de cálculo tributário, preço mediano de venda no ML e lucro líquido projetado).
4. **Segunda-feira 12:00**: Disparo do PDF no canal fechado dos assinantes, acompanhado de um áudio explicativo destacando a melhor oportunidade da semana e orientações para negociar o lote.

---

## 📣 5. Estratégia de Go-to-Market (GTM) & Vendas

### Canais de Aquisição Iniciais (Custo Zero de Tráfego)
1. **Guerrilha de Alto Valor em Grupos de Sellers**: Participação em grupos abertos de vendedores de Mercado Livre e Shopee utilizando a tática do *Estudo de Caso Reverso*: postar a dissecação técnica de produtos que dão prejuízo oculto por conta do ICMS por dentro e oferecer gratuitamente o dossiê com os produtos que dão lucro real no privado.
2. **Prospecção Ativa Cirúrgica (Outbound WhatsApp)**: Localização de lojistas intermediários no Mercado Livre, identificação do CNPJ e contato direto com o tomador de decisão oferecendo uma auditoria gratuita de custo de reposição para o produto que ele já vende.

### Ideias de Ângulos de Anúncios / Criativos
- **Ângulo 1 (O Choque Tributário / Quebra de Mito)**:
  - *Gancho Visual*: Print de carrinho do AliExpress de US$ 48 mostrando o imposto que dobra o valor na tela final.
  - *Copy*: *"Você ainda acha que imposto no Remessa Conforme é só somar 20%? Se você não está calculando o ICMS por dentro, cada lote que você importa para revender no Mercado Livre está te dando até 18% de prejuízo invisível. Nós rodamos um algoritmo que faz o cálculo exato da Receita Federal e separamos 5 produtos que ainda deixam mais de 40% de margem líquida real. Baixe o relatório gratuito antes de comprar seu próximo estoque."*
- **Ângulo 2 (A Falha do AvantPro / Foco no Lucro)**:
  - *Gancho Visual*: Dashboard de software de métricas aberto em um produto com faturamento de R$ 80.000, com uma tarja vermelha escrito: 'MARGEM REAL: NEGATIVA'.
  - *Copy*: *"O AvantPro é ótimo para te mostrar o que os outros já venderam mês passado. O problema? Ele não sabe quanto a fábrica na China cobra, qual é o lote mínimo e nem quanto de imposto você vai pagar em Curitiba. Pare de olhar o retrovisor e comece a olhar o custo da fábrica. Conheça o Radar de Arbitragem Tributada."*

### Oferta de Entrada (Primeiros 10 a 20 Assinantes)
- **A Oferta Fundador (Beta VIP)**:
  - Mensal por **R$ 47,00/mês** (preço travado vitaliciamente) ou **R$ 119,00 no plano trimestral**.
  - **Bônus Exclusivo 1**: Acesso direto ao WhatsApp do fundador para validar a viabilidade tributária de qualquer produto trazido pelo lojista (1 consulta/semana).
  - **Bônus Exclusivo 2**: Script em inglês pronto para negociar desconto de lote no chat do fornecedor no Alibaba.
  - **Garantia Blindada de ROI**: Se em até 30 dias o lojista não encontrar no clube pelo menos uma oportunidade com potencial de lucro comprovado superior a R$ 500 no lote, o dinheiro é estornado via Pix sem perguntas.

---

## ⚠️ 6. Riscos, Desafios & Mitigações

### 1. Risco de Churn Alto por Ciclo de Compra do Lojista
- **Descrição**: O lojista compra a assinatura, encontra um bom produto no primeiro dossiê, faz o pedido do lote da China e cancela a mensalidade porque passará os próximos 45 a 60 dias focado exclusivamente em vender aquele estoque específico.
- *Mitigação*:
  1. Forçar a barreira de saída oferecendo o **Plano Trimestral com desconto agressivo** como opção padrão de checkout.
  2. Transformar o clube de "lista de produtos" em uma **rotina de monitoramento operacional indispensável**: enviar alertas quando concorrentes líderes ficarem sem estoque no Mercado Livre (janela de aumento de preço) e boletins de alterações em alíquotas estaduais de ICMS.

### 2. Risco de Canibalização entre os Próprios Membros
- **Descrição**: Se 100 assinantes receberem a mesma lista de 5 produtos, dezenas deles importarão o mesmo lote simultaneamente e criarão anúncios idênticos no Mercado Livre, queimando o preço na briga pelo BuyBox.
- *Mitigação*:
  1. **Segmentação por Pools Fechados**: Dividir a base de membros por nichos específicos de interesse (Ex: Nicho 1: Ferramentas e Hobbies; Nicho 2: Peças de Relojoaria e Acessórios; Nicho 3: Iluminação e Casa Inteligente). Cada grupo recebe dossiês contendo produtos distintos.
  2. Limitar o número de vagas no clube fundador a 25 ou 30 membros por ciclo.

### 3. Risco Técnico de Bloqueio de Scraping e Mudança de Layout
- **Descrição**: O AliExpress e o Alibaba alterarem classes CSS, implementarem desafios antibot agressivos (Cloudflare, Akamai, Captcha) ou bloquearem os IPs dos servidores de raspagem.
- *Mitigação*:
  1. Manter a arquitetura híbrida já projetada no motor: além do módulo de scraping direto, o sistema possui o conector pronto para a **API Oficial de Afiliados/Dropshipping do AliExpress (`official_api.py`)**, que utiliza assinatura HMAC-SHA256 e não sofre bloqueios de IP.
  2. Utilização de proxies residenciais rotativos no caso do coletor direto.

---

## 🗺️ 7. Roadmap de Execução & Checklist de Próximos Passos

### Fase 1 - Validação (Dias 1 a 15)
- [ ] Executar o script `aliexpress-finder` localmente e gerar a base de dados via `exporter.py`.
- [ ] Filtrar manualmente os 3 produtos de maior margem líquida real (acima de 38%) e menor complexidade aduaneira.
- [ ] Criar o template do **Dossiê Executivo de Arbitragem Tributada #01** (em PDF via Notion ou Canva).
- [ ] Elaborar uma publicação de alto valor técnico desvendando o cálculo do ICMS por dentro em 3 grupos de vendedores e no LinkedIn/Instagram.
- [ ] Distribuir o Dossiê #01 gratuitamente para os primeiros 15 lojistas que solicitarem via mensagem privada.
- [ ] Executar o pitch de fechamento individual via áudio no WhatsApp (Oferta Fundador por R$ 47/mês ou R$ 119/trimestre).
- [ ] **Meta da Fase**: Atingir de 5 a 10 assinantes pagantes (R$ 250 a R$ 600 em caixa) sem escrever nenhuma linha de código adicional.

### Fase 2 - Construção do MVP & Retenção (Dias 16 a 45)
- [ ] Criar comunidade restrita no WhatsApp/Telegram com fluxo de onboarding integrado à plataforma de pagamentos (Kiwify, Kirvano ou Asaas).
- [ ] Estabelecer a rotina de envio semanal de dossiês (segundas-feiras, 12:00).
- [ ] Implementar a rotina de alertas de ruptura de concorrentes e alterações tributárias para combater o cancelamento.
- [ ] Realizar entrevistas individuais semanais de 15 minutos com os assinantes mais ativos para mapear quais dados do Excel eles mais usam antes de comprar um lote.
- [ ] **Meta da Fase**: Alcançar 30 assinantes ativos e manter a taxa de cancelamento mensal abaixo de 10%.

### Fase 3 - Lançamento & Transição para Micro-SaaS (Dias 46 a 60)
- [ ] Empacotar o backend Python existente em uma API REST utilizando **FastAPI**.
- [ ] Construir uma interface web minimalista (Next.js ou Streamlit/Reflex) onde o lojista pode colar a URL de qualquer produto do AliExpress/Alibaba e receber na hora o cálculo do Landed Cost e a viabilidade no Mercado Livre.
- [ ] Liberar a plataforma web como uma atualização gratuita exclusiva para os membros do Clube VIP.
- [ ] Abrir as inscrições públicas do SaaS com planos a partir de R$ 97/mês, utilizando os próprios membros fundadores como prova social e estudos de caso de sucesso.
