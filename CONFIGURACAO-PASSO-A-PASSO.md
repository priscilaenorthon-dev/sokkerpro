# 🎯 CONFIGURAÇÃO PASSO A PASSO - 14 BOTS SOKKERPRO

> **Guia completo seguindo a estrutura oficial do SokkerPRO**  
> Este documento segue o formato do PDF oficial: **Passo 1** (Informações Básicas), **Passo 2** (Configuração Essencial), **Passo 3** (Condições).

## 📋 Índice Rápido

- [Bot 01 - Escanteios Conservador (Over 8.5)](#bot-01---escanteios-conservador-over-85)
- [Bot 02 - Escanteios Moderado (Over 10.5)](#bot-02---escanteios-moderado-over-105)
- [Bot 03 - Escanteios Agressivo (Under 7.5)](#bot-03---escanteios-agressivo-under-75)
- [Bot 04 - Gol 1T Conservador (Over 0.5)](#bot-04---gol-1t-conservador-over-05)
- [Bot 05 - Gol 1T Moderado (Over 1.5)](#bot-05---gol-1t-moderado-over-15)
- [Bot 06 - Sem Gol 1T Agressivo (Under 0.5)](#bot-06---sem-gol-1t-agressivo-under-05)
- [Bot 07 - Empate Conservador](#bot-07---empate-conservador)
- [Bot 08 - Empate Moderado (Tático)](#bot-08---empate-moderado-tático)
- [Bot 09 - Empate Agressivo (Zebra)](#bot-09---empate-agressivo-zebra)
- [Bot 10 - Gol 2T Conservador (Over 0.5)](#bot-10---gol-2t-conservador-over-05)
- [Bot 11 - Gol 2T Agressivo (Over 1.5)](#bot-11---gol-2t-agressivo-over-15)
- [Bot 12 - Favorito Conservador](#bot-12---favorito-conservador)
- [Bot 13 - Favorito Agressivo (Virada)](#bot-13---favorito-agressivo-virada)
- [Bot 14 - Visitante Moderado (Value)](#bot-14---visitante-moderado-value)

---

## Bot 01 - Escanteios Conservador (Over 8.5)

### 📋 Passo 1: Informações Básicas

**Mercado de Escanteios:**
- **Tipo:** Mais um escanteio até o fim do jogo
- **Linha:** Over 8.5 Escanteios (9+ corners)
- **Como funciona:** Se o jogo tem 7 escanteios, precisa ter mais 8.5 escanteios, ou seja, 9 ou mais no total

**Nome do Bot:** `Escanteios Conservador`

### ⚙️ Passo 2: Configuração Essencial

**Faixa de Minutos:**
- **De:** 25
- **Até:** 70
- *Por quê?* Tempo suficiente para analisar o padrão do jogo e ainda ter margem para corners acontecerem

**Odd Mínima de Entrada:** 1.5
- Se não configurar odd, o bot alertará em qualquer odd
- Com odd 1.5, só alertará quando o mercado estiver nesta cotação ou superior

**Valor de Entrada:** 0 (apenas alertas) ou defina seu valor
- 0 = Apenas notificações, sem contabilizar lucro/prejuízo
- [Seu valor] = Contabiliza ROI, lucro e prejuízo automaticamente

**Filtro de Placar:** Qualquer
- Funciona em qualquer placar

**Gestão de Banca:** 1-2% (Conservador)

### 🎯 Passo 3: Condições

#### ✅ Condições AO VIVO (Todas obrigatórias)

**1. Escanteios**
- **Escanteios Totais (Ambos Somados):** Mínimo 5
- **Escanteios últimos 10min (Ambos Somados):** Mínimo 2

**2. Projeção**
- **Cálculo:** (Escanteios atuais ÷ Minuto atual) × 90
- **Valor Mínimo:** 11 escanteios projetados

**3. Estatísticas de Ataque**
- **Ataques Perigosos Totais (Ambos Somados):** Mínimo 12
- **Chutes Bloqueados (Ambos Somados):** Mínimo 3
- **Barra de Pressão (Qualquer Time):** Mínimo 65%

#### 📊 Condições PRÉ-JOGO (Todas obrigatórias)

> **Sobre as Médias H2H:** Calculadas com base nos últimos 5 jogos:  
> • Time da casa: últimos 5 jogos em casa  
> • Time visitante: últimos 5 jogos como visitante

**1. Histórico de Escanteios**
- Média de Escanteios (últimos 5 jogos): `Mínimo 9.5`
- Média Casa + Visitante: `Mínimo 10`

**2. Estilo de Jogo**
- Times que atacam pelas laterais
- Histórico de muitos cruzamentos

### 🎯 Cenários Ideais
- ✅ Premier League
- ✅ Bundesliga
- ✅ Times com laterais ofensivos (Liverpool, Bayern, Man City)
- ✅ Jogos abertos desde o início

### ⚠️ Evitar
- ❌ Jogos muito travados
- ❌ Times que jogam pelo meio
- ❌ Histórico baixo de corners

---

## Bot 02 - Escanteios Moderado (Over 10.5)

### 📋 Passo 1: Informações Básicas

**Mercado de Escanteios:**
- **Tipo:** Mais um escanteio até o fim do jogo
- **Linha:** Over 10.5 Escanteios (11+ corners)
- **Como funciona:** Se o jogo tem 8 escanteios, precisa ter mais 10.5 escanteios, ou seja, 11 ou mais no total

**Nome do Bot:** `Escanteios Moderado`

### ⚙️ Passo 2: Configuração Essencial

**Faixa de Minutos:**
- **De:** 20
- **Até:** 65
- *Por quê?* Entrada mais cedo para jogos com ritmo intenso e alto volume de corners desde o início

**Odd Mínima de Entrada:** 1.6
- Se não configurar odd, o bot alertará em qualquer odd
- Com odd 1.6, só alertará quando o mercado estiver nesta cotação ou superior

**Valor de Entrada:** 0 (apenas alertas) ou defina seu valor
- 0 = Apenas notificações, sem contabilizar lucro/prejuízo
- [Seu valor] = Contabiliza ROI, lucro e prejuízo automaticamente

**Filtro de Placar:** Qualquer
- Funciona em qualquer placar

**Gestão de Banca:** 2-3% (Moderado)

### 🎯 Passo 3: Condições

#### ✅ Condições AO VIVO (Todas obrigatórias)

**1. Escanteios**
- **Escanteios Totais (Ambos Somados):** Mínimo 6
- **Escanteios últimos 10min (Ambos Somados):** Mínimo 3
- **Escanteios últimos 5min (Ambos Somados):** Mínimo 2

**2. Projeção**
- **Cálculo:** (Escanteios atuais ÷ Minuto atual) × 90
- **Valor Mínimo:** 13 escanteios projetados

**3. Estatísticas de Ataque**
- **Ataques Perigosos Totais (Ambos Somados):** Mínimo 15
- **Chutes Bloqueados (Ambos Somados):** Mínimo 4
- **Chutes Totais (Ambos Somados):** Mínimo 12
- **Barra de Pressão (Qualquer Time):** Mínimo 70%

#### 📊 Condições PRÉ-JOGO (Todas obrigatórias)

> **Sobre as Médias H2H:** Calculadas com base nos últimos 5 jogos:  
> • Time da casa: últimos 5 jogos em casa  
> • Time visitante: últimos 5 jogos como visitante

**1. Histórico de Escanteios**
- Média de Escanteios (últimos 5 jogos): `Mínimo 11`
- Ambos times com média 5.5+ escanteios

**2. Características do Jogo**
- Ambos times atacando
- Jogo muito aberto

### 🎯 Cenários Ideais
- ✅ Jogos muito ofensivos (Eredivisie, Bundesliga)
- ✅ Ambas equipes pressionando
- ✅ Histórico alto de corners entre os times

### ⚠️ Evitar
- ❌ Jogos com apenas um time atacando
- ❌ Defesas muito sólidas
- ❌ Contra-ataques rápidos (poucos corners)

---

## Bot 03 - Escanteios Agressivo (Under 7.5)

### 📋 Passo 1: Informações Básicas

**Mercado de Escanteios:**
- **Tipo:** Sem mais escanteios até o fim do jogo
- **Linha:** Under 7.5 Escanteios (máximo 7 corners)
- **Como funciona:** O jogo não pode ter mais de 7 escanteios no total

**Nome do Bot:** `Escanteios Agressivo Under`

### ⚙️ Passo 2: Configuração Essencial

**Faixa de Minutos:**
- **De:** 30
- **Até:** 70
- *Por quê?* Tempo suficiente para confirmar o padrão de jogo travado com poucos corners

**Odd Mínima de Entrada:** 1.5
- Se não configurar odd, o bot alertará em qualquer odd
- Com odd 1.5, só alertará quando o mercado estiver nesta cotação ou superior

**Valor de Entrada:** 0 (apenas alertas) ou defina seu valor
- 0 = Apenas notificações, sem contabilizar lucro/prejuízo
- [Seu valor] = Contabiliza ROI, lucro e prejuízo automaticamente

**Filtro de Placar:** Qualquer
- Funciona em qualquer placar

**Gestão de Banca:** 2-4% (Agressivo)

### 🎯 Passo 3: Condições

#### ✅ Condições AO VIVO (Todas obrigatórias - MÁXIMOS)

**1. Escanteios**
- **Escanteios Totais (Ambos Somados):** MÁXIMO 3
- **Escanteios últimos 10min (Ambos Somados):** MÁXIMO 1

**2. Projeção**
- **Cálculo:** (Escanteios atuais ÷ Minuto atual) × 90
- **Valor Máximo:** 7 escanteios projetados

**3. Estatísticas de Ataque**
- **Ataques Perigosos Totais (Ambos Somados):** MÁXIMO 8
- **Chutes Bloqueados (Ambos Somados):** MÁXIMO 2
- **Diferença de Posse:** MÁXIMO 15% (jogo equilibrado)

#### 📊 Condições PRÉ-JOGO (Todas obrigatórias)

> **Sobre as Médias H2H:** Calculadas com base nos últimos 5 jogos:  
> • Time da casa: últimos 5 jogos em casa  
> • Time visitante: últimos 5 jogos como visitante

**1. Histórico de Escanteios**
- Média de Escanteios (últimos 5 jogos): `MÁXIMO 8`
- Ambos times com média baixa

**2. Estilo de Jogo**
- Times que jogam no contra-ataque
- Defesas organizadas
- Jogos táticos/travados

### 🎯 Cenários Ideais
- ✅ Serie A (Itália)
- ✅ Times defensivos (Getafe, Atlético Madrid, Burnley)
- ✅ Clássicos equilibrados e estudados
- ✅ Jogos decisivos (finais, playoffs)

### ⚠️ Evitar
- ❌ Jogos muito abertos
- ❌ Times ofensivos que cruzam muito
- ❌ Um time dominando completamente

---

## Bot 04 - Gol 1T Conservador (Over 0.5)

### 📋 Passo 1: Informações Básicas

**Mercado de Gols:**
- **Tipo:** Mais um gol até o fim do primeiro tempo
- **Linha:** Over 0.5 Gols 1º Tempo
- **Como funciona:** Sair mais um gol no jogo, exemplo: jogo 0x0 seria mais de 0.5

**Nome do Bot:** `Gol 1T Conservador`

### ⚙️ Passo 2: Configuração Essencial

**Faixa de Minutos:**
- **De:** 15
- **Até:** 35
- *Por quê?* Janela ideal no 1º tempo com tempo suficiente para sair pelo menos 1 gol

**Odd Mínima de Entrada:** 1.4
- Se não configurar odd, o bot alertará em qualquer odd
- Com odd 1.4, só alertará quando o mercado estiver nesta cotação ou superior

**Valor de Entrada:** 0 (apenas alertas) ou defina seu valor
- 0 = Apenas notificações, sem contabilizar lucro/prejuízo
- [Seu valor] = Contabiliza ROI, lucro e prejuízo automaticamente

**Filtro de Placar:** 0x0 (OBRIGATÓRIO)
- Só funciona com jogo sem gols

**Gestão de Banca:** 1-2% (Conservador)

### 🎯 Passo 3: Condições

#### ✅ Condições AO VIVO (Todas obrigatórias)

**1. Estatísticas de Ataque**
- **Ataques Perigosos Totais (Ambos Somados):** Mínimo 6
- **Grandes Chances Criadas (Ambos Somados):** Mínimo 2
- **Chutes no Gol (Ambos Somados):** Mínimo 3
- **Chutes na Área (Ambos Somados):** Mínimo 4

**2. Pressão Ofensiva**
- **Barra de Pressão (Qualquer Time):** Mínimo 60%
- **Ataques nos últimos 5min (Ambos Somados):** Mínimo 3

**3. Finalizações**
- **Total de Chutes (Ambos Somados):** Mínimo 6
- **Defesas do Goleiro (Ambos Somados):** Mínimo 2

#### 📊 Condições PRÉ-JOGO (Todas obrigatórias)

> **Sobre as Médias H2H:** Calculadas com base nos últimos 5 jogos:  
> • Time da casa: últimos 5 jogos em casa  
> • Time visitante: últimos 5 jogos como visitante

**1. Histórico de Gols**
- Média de Gols 1T (últimos 5 jogos): `Mínimo 1.2`
- Média de Gols combinada Casa + Visitante: `Mínimo 1.0`

**2. Prognóstico**
- Prognóstico Over 0.5 1T: `Mínimo 60%`

### 🎯 Cenários Ideais
- ✅ Jogo 0x0 muito ofensivo
- ✅ Muitas finalizações sem converter
- ✅ Times ofensivos (Barcelona, Liverpool, Bayern)
- ✅ Jogos abertos desde o início

### ⚠️ Evitar
- ❌ Se já saiu gol (mesmo que seja 1x0)
- ❌ Jogo travado com poucas chances
- ❌ Times muito defensivos

---

## Bot 05 - Gol 1T Moderado (Over 1.5)

### 📋 Passo 1: Informações Básicas

**Mercado de Gols:**
- **Tipo:** Mais um gol até o fim do primeiro tempo
- **Linha:** Over 1.5 Gols 1º Tempo (2+ gols)
- **Como funciona:** Se já tem 1 gol, precisa sair mais 1 para completar 2+ gols no 1T

**Nome do Bot:** `Gol 1T Moderado`

### ⚙️ Passo 2: Configuração Essencial

**Faixa de Minutos:**
- **De:** 15
- **Até:** 40
- *Por quê?* Tempo adequado para jogos com ritmo intenso onde já saiu 1 gol

**Odd Mínima de Entrada:** 1.8
- Se não configurar odd, o bot alertará em qualquer odd
- Com odd 1.8, só alertará quando o mercado estiver nesta cotação ou superior

**Valor de Entrada:** 0 (apenas alertas) ou defina seu valor
- 0 = Apenas notificações, sem contabilizar lucro/prejuízo
- [Seu valor] = Contabiliza ROI, lucro e prejuízo automaticamente

**Filtro de Placar:** 1 gol já marcado (1x0 ou 0x1)
- Requer pelo menos 1 gol marcado

**Gestão de Banca:** 2-3% (Moderado)

### 🎯 Passo 3: Condições

#### ✅ Condições AO VIVO (Todas obrigatórias)

**1. Gols e Ritmo**
- **Gols marcados no 1T:** Mínimo 1
- **Tempo desde último gol:** Máximo 8 minutos

**2. Estatísticas de Ataque**
- **Ataques Perigosos Totais (Ambos Somados):** Mínimo 10
- **Grandes Chances Criadas (Ambos Somados):** Mínimo 3
- **Chutes no Gol (Ambos Somados):** Mínimo 5

**3. Pressão Ofensiva**
- **Barra de Pressão (Qualquer Time):** Mínimo 65%
- Ambos times atacando ativamente

#### 📊 Condições PRÉ-JOGO (Todas obrigatórias)

> **Sobre as Médias H2H:** Calculadas com base nos últimos 5 jogos:  
> • Time da casa: últimos 5 jogos em casa  
> • Time visitante: últimos 5 jogos como visitante

**1. Histórico de Gols**
- Média de Gols 1T (últimos 5 jogos): `Mínimo 1.8`
- Histórico de jogos com 2+ gols no 1T: `Mínimo 40%`

**2. Características**
- Ambos times muito ofensivos
- Defesas frágeis

### 🎯 Cenários Ideais
- ✅ Jogo 1x0 muito aberto
- ✅ Ritmo frenético de jogo
- ✅ Eredivisie, Brasileirão
- ✅ Times que não se defendem (Atalanta, Bayer Leverkusen)

### ⚠️ Evitar
- ❌ Jogo 0x0 (usar Bot 04 neste caso)
- ❌ Time vencedor se fechando
- ❌ Jogo esfriando após o gol

---

## Bot 06 - Sem Gol 1T Agressivo (Under 0.5)

### 📋 Passo 1: Informações Básicas

**Mercado de Gols:**
- **Tipo:** Sem mais gols até o fim do primeiro tempo
- **Linha:** Under 0.5 Gols 1º Tempo (0 gols)
- **Como funciona:** Aposta ganha se o primeiro tempo terminar 0x0. Se sair qualquer gol no primeiro tempo, você perde.

**Nome do Bot:** `Sem Gol 1T Agressivo`

### ⚙️ Passo 2: Configuração Essencial

**Faixa de Minutos:**
- **De:** 20
- **Até:** 40
- *Por quê?* Tempo adequado para confirmar padrão de jogo travado sem muitas chances

**Odd Mínima de Entrada:** 1.5
- Se não configurar odd, o bot alertará em qualquer odd
- Com odd 1.5, só alertará quando o mercado estiver nesta cotação ou superior

**Valor de Entrada:** 0 (apenas alertas) ou defina seu valor
- 0 = Apenas notificações, sem contabilizar lucro/prejuízo
- [Seu valor] = Contabiliza ROI, lucro e prejuízo automaticamente

**Filtro de Placar:** 0x0 (OBRIGATÓRIO - se sair gol, aposta perdida)
- Só funciona com jogo sem gols

**Gestão de Banca:** 2-4% (Agressivo)

### 🎯 Passo 3: Condições

#### ✅ Condições AO VIVO (Todas obrigatórias - MÁXIMOS)

**1. Estatísticas de Ataque**
- **Ataques Perigosos Totais (Ambos Somados):** MÁXIMO 4
- **Grandes Chances Criadas (Ambos Somados):** MÁXIMO 0
- **Chutes no Gol (Ambos Somados):** MÁXIMO 1

**2. Pressão Ofensiva**
- **Barra de Pressão (Qualquer Time):** MÁXIMO 50% (equilibrado)
- **Total de Chutes (Ambos Somados):** MÁXIMO 4

**3. Ritmo de Jogo**
- **Faltas (Ambos Somados):** Mínimo 8 (jogo travado)
- **Escanteios (Ambos Somados):** MÁXIMO 3

#### 📊 Condições PRÉ-JOGO (Todas obrigatórias)

> **Sobre as Médias H2H:** Calculadas com base nos últimos 5 jogos:  
> • Time da casa: últimos 5 jogos em casa  
> • Time visitante: últimos 5 jogos como visitante

**1. Histórico de Gols**
- Média de Gols 1T (últimos 5 jogos): `MÁXIMO 0.6`
- Histórico de 0x0 no 1T: `Mínimo 50%`

**2. Prognóstico**
- Prognóstico Under 0.5 1T: `Mínimo 55%`

**3. Características**
- Times muito defensivos
- Jogos táticos

### 🎯 Cenários Ideais
- ✅ Jogo 0x0 muito travado
- ✅ Poucas finalizações
- ✅ Serie A (Itália)
- ✅ Times defensivos (Atlético-MG, Getafe, Burnley)
- ✅ Finais e clássicos estudados

### ⚠️ Evitar
- ❌ Jogos abertos
- ❌ Times muito ofensivos
- ❌ Se já saiu gol (aposta perdida automaticamente)

---

## Bot 07 - Empate Conservador

### 📋 Passo 1: Informações Básicas

**Mercado de Resultado:**
- **Tipo:** Empate (Draw)
- **Como funciona:** O jogo deve terminar empatado em qualquer placar

**Nome do Bot:** `Empate Conservador`

### ⚙️ Passo 2: Configuração Essencial

**Faixa de Minutos:**
- **De:** 60
- **Até:** 80
- *Por quê?* Fase final do jogo onde o padrão de equilíbrio está consolidado

**Odd Mínima de Entrada:** 2.0
- Se não configurar odd, o bot alertará em qualquer odd
- Com odd 2.0, só alertará quando o mercado estiver nesta cotação ou superior

**Valor de Entrada:** 0 (apenas alertas) ou defina seu valor
- 0 = Apenas notificações, sem contabilizar lucro/prejuízo
- [Seu valor] = Contabiliza ROI, lucro e prejuízo automaticamente

**Filtro de Placar:** Empate OU diferença de 1 gol
- Empate em qualquer placar ou diferença de apenas 1 gol

**Gestão de Banca:** 1-2% (Conservador)

### 🎯 Passo 3: Condições

#### ✅ Condições AO VIVO (Todas obrigatórias)

**1. Placar**
- **Situação:** 0x0, 1x1, 2x2 OU 1x0, 0x1
- Se diferença de 1 gol: Time perdendo deve estar pressionando

**2. Equilíbrio do Jogo**
- **Posse de Bola:** Entre 45% e 55% (muito equilibrado)
- **Diferença de Ataques Perigosos:** MÁXIMO 3
- **Diferença de Chutes:** MÁXIMO 4

**3. Estatísticas Balanceadas**
- **Barra de Pressão:** Entre 45% e 55%
- Escanteios de ambos: Próximos
- Chutes no gol: Próximos

#### 📊 Condições PRÉ-JOGO (Todas obrigatórias)

> **Sobre as Médias H2H:** Calculadas com base nos últimos 5 jogos:  
> • Time da casa: últimos 5 jogos em casa  
> • Time visitante: últimos 5 jogos como visitante

**1. Histórico H2H**
- Empates nos últimos 5 confrontos: `Mínimo 2`
- Média de gols diferença H2H: `MÁXIMO 1.5`

**2. Força das Equipes**
- Diferença de ranking/odds: `MÁXIMA 20%`
- Times de força similar

### 🎯 Cenários Ideais
- ✅ Jogo muito equilibrado
- ✅ Nenhum time conseguindo impor ritmo
- ✅ Clássicos regionais equilibrados
- ✅ Times de meio de tabela

### ⚠️ Evitar
- ❌ Um time dominando claramente
- ❌ Jogo muito aberto (muitos gols esperados)
- ❌ Diferença técnica muito grande

---

## Bot 08 - Empate Moderado (Tático)

### 📋 Passo 1: Informações Básicas

**Mercado de Resultado:**
- **Tipo:** Empate (Draw)
- **Como funciona:** O jogo deve terminar empatado em qualquer placar

**Nome do Bot:** `Empate Tático`

### ⚙️ Passo 2: Configuração Essencial

**Faixa de Minutos:**
- **De:** 50
- **Até:** 75
- *Por quê?* Jogos decisivos tendem a ficar mais travados nesta fase

**Odd Mínima de Entrada:** 2.2
- Se não configurar odd, o bot alertará em qualquer odd
- Com odd 2.2, só alertará quando o mercado estiver nesta cotação ou superior

**Valor de Entrada:** 0 (apenas alertas) ou defina seu valor
- 0 = Apenas notificações, sem contabilizar lucro/prejuízo
- [Seu valor] = Contabiliza ROI, lucro e prejuízo automaticamente

**Filtro de Placar:** Empate ou 1x0/0x1
- Empate ou diferença mínima de gols

**Gestão de Banca:** 2-3% (Moderado)

### 🎯 Passo 3: Condições

#### ✅ Condições AO VIVO (Todas obrigatórias)

**1. Tipo de Jogo**
- **Faltas (Ambos Somados):** Mínimo 12 (jogo travado)
- **Cartões Amarelos (Ambos Somados):** Mínimo 2
- Ritmo de jogo: Lento/estudado

**2. Características Táticas**
- **Posse de Bola:** Entre 40% e 60%
- **Ataques Perigosos (Ambos Somados):** MÁXIMO 10 (jogo fechado)
- Muitas faltas táticas

**3. Contexto**
- Jogo decisivo (final, playoff, derby)
- Ambos times com medo de perder
- Jogo físico/pegado

#### 📊 Condições PRÉ-JOGO (Todas obrigatórias)

> **Sobre as Médias H2H:** Calculadas com base nos últimos 5 jogos:  
> • Time da casa: últimos 5 jogos em casa  
> • Time visitante: últimos 5 jogos como visitante

**1. Importância do Jogo**
- Tipo: `Final, Derby, Jogo Decisivo`
- Momento: Mata-mata, últimas rodadas

**2. Histórico**
- Jogos entre si costumam ser equilibrados
- Rivais ou clássicos

### 🎯 Cenários Ideais
- ✅ Finais de campeonato
- ✅ Derbies (Fla x Flu, Barça x Real, Inter x Milan)
- ✅ Mata-mata (Libertadores, Champions)
- ✅ Jogos "6 pontos" no final do campeonato

### ⚠️ Evitar
- ❌ Jogos sem importância
- ❌ Jogo muito aberto
- ❌ Um time precisa muito da vitória

---

## Bot 09 - Empate Agressivo (Zebra)

### 📋 Passo 1: Informações Básicas

**Mercado de Resultado:**
- **Tipo:** Empate (Draw)
- **Como funciona:** O jogo deve terminar empatado em qualquer placar

**Nome do Bot:** `Empate Zebra`

### ⚙️ Passo 2: Configuração Essencial

**Faixa de Minutos:**
- **De:** 45
- **Até:** 70
- *Por quê?* Janela onde o favorito tem tempo de empatar mas já está sob pressão

**Odd Mínima de Entrada:** 2.5
- Se não configurar odd, o bot alertará em qualquer odd
- Com odd 2.5, só alertará quando o mercado estiver nesta cotação ou superior

**Valor de Entrada:** 0 (apenas alertas) ou defina seu valor
- 0 = Apenas notificações, sem contabilizar lucro/prejuízo
- [Seu valor] = Contabiliza ROI, lucro e prejuízo automaticamente

**Filtro de Placar:** Visitante ganhando OU empate com favorito pressionando
- Situação de zebra ou favorito em dificuldade

**Gestão de Banca:** 3-5% (Agressivo)

### 🎯 Passo 3: Condições

#### ✅ Condições AO VIVO (Todas obrigatórias)

**1. Situação do Placar**
- Opção A: Visitante vencendo por 1 gol
- Opção B: Empate com favorito pressionando muito

**2. Desempenho do Favorito**
- Favorito está pressionando mas não converte
- **Posse do Favorito:** Mínimo 55%
- **Ataques Perigosos Favorito:** Mínimo 8

**3. Defesa do Visitante**
- Visitante organizado defensivamente
- **Defesas do goleiro visitante:** Mínimo 4
- **Chutes bloqueados visitante:** Mínimo 3

**4. Contexto**
- Favorito precisa empatar/virar
- Pressão aumentando no favorito

#### 📊 Condições PRÉ-JOGO (Todas obrigatórias)

> **Sobre as Médias H2H:** Calculadas com base nos últimos 5 jogos:  
> • Time da casa: últimos 5 jogos em casa  
> • Time visitante: últimos 5 jogos como visitante

**1. Odds**
- Odd do Favorito: `MÁXIMO 1.60` (grande favorito)
- Diferença clara de força

**2. Visitante**
- Visitante com boa defesa
- Histórico de segurar resultados fora

### 🎯 Cenários Ideais
- ✅ Grande favorito surpreendido
- ✅ Visitante defendendo bem (0x1 ou 0x0)
- ✅ Favorito atacando mas sem efetividade
- ✅ Zebra em andamento que pode acabar empate

### ⚠️ Evitar
- ❌ Visitante sendo massacrado
- ❌ Diferença de 2+ gols
- ❌ Favorito jogando mal

---

## Bot 10 - Gol 2T Conservador (Over 0.5)

### 📋 Passo 1: Informações Básicas

**Mercado de Gols:**
- **Tipo:** Mais um gol até o fim do segundo tempo
- **Linha:** Over 0.5 Gols 2º Tempo
- **Como funciona:** Sair pelo menos 1 gol no segundo tempo

**Nome do Bot:** `Gol 2T Conservador`

### ⚙️ Passo 2: Configuração Essencial

**Faixa de Minutos:**
- **De:** 50
- **Até:** 75
- *Por quê?* Tempo adequado no 2T para time que precisa de gol reagir

**Odd Mínima de Entrada:** 1.4
- Se não configurar odd, o bot alertará em qualquer odd
- Com odd 1.4, só alertará quando o mercado estiver nesta cotação ou superior

**Valor de Entrada:** 0 (apenas alertas) ou defina seu valor
- 0 = Apenas notificações, sem contabilizar lucro/prejuízo
- [Seu valor] = Contabiliza ROI, lucro e prejuízo automaticamente

**Filtro de Placar:** Qualquer (mas um time precisa de gol)
- Situações onde há motivação para atacar

**Gestão de Banca:** 1-2% (Conservador)

### 🎯 Passo 3: Condições

#### ✅ Condições AO VIVO (Todas obrigatórias)

**1. Situação do Jogo**
- Um time precisa urgentemente de gol
- Opções: Empate insuficiente, time perdendo, etc.

**2. Estatísticas do 2T**
- **Ataques Perigosos no 2T (Ambos Somados):** Mínimo 4
- **Chutes no 2T (Ambos Somados):** Mínimo 3
- **Tempo de jogo no 2T:** Mínimo 5 minutos

**3. Mudanças Táticas**
- **Substituições ofensivas feitas:** Mínimo 1
- Entrada de atacantes
- Mudança de formação para atacar

**4. Pressão Ofensiva**
- **Barra de Pressão (Qualquer Time):** Mínimo 60%
- Time que precisa do gol atacando

#### 📊 Condições PRÉ-JOGO (Todas obrigatórias)

> **Sobre as Médias H2H:** Calculadas com base nos últimos 5 jogos:  
> • Time da casa: últimos 5 jogos em casa  
> • Time visitante: últimos 5 jogos como visitante

**1. Histórico**
- Média de Gols totais (últimos 5 jogos): `Mínimo 2.0`
- Times costumam marcar no 2T

**2. Características**
- Time que precisa do gol tem capacidade ofensiva

### 🎯 Cenários Ideais
- ✅ Favorito perdendo e pressionando
- ✅ Empate insuficiente para ambos
- ✅ Jogo aberto no 2T
- ✅ Substituições ofensivas feitas

### ⚠️ Evitar
- ❌ Time vencedor segurando resultado
- ❌ Jogo muito fechado
- ❌ Nenhum time pressionando

---

## Bot 11 - Gol 2T Agressivo (Over 1.5)

### 📋 Passo 1: Informações Básicas

**Mercado de Gols:**
- **Tipo:** Mais um gol até o fim do segundo tempo
- **Linha:** Over 1.5 Gols 2º Tempo (2+ gols)
- **Como funciona:** Sair pelo menos 2 gols no segundo tempo

**Nome do Bot:** `Gol 2T Agressivo`

### ⚙️ Passo 2: Configuração Essencial

**Faixa de Minutos:**
- **De:** 50
- **Até:** 70
- *Por quê?* Tempo suficiente para múltiplos gols com jogo aberto

**Odd Mínima de Entrada:** 2.0
- Se não configurar odd, o bot alertará em qualquer odd
- Com odd 2.0, só alertará quando o mercado estiver nesta cotação ou superior

**Valor de Entrada:** 0 (apenas alertas) ou defina seu valor
- 0 = Apenas notificações, sem contabilizar lucro/prejuízo
- [Seu valor] = Contabiliza ROI, lucro e prejuízo automaticamente

**Filtro de Placar:** Mínimo 1 gol no 2T já marcado
- Requer pelo menos 1 gol no segundo tempo

**Gestão de Banca:** 3-4% (Agressivo)

### 🎯 Passo 3: Condições

#### ✅ Condições AO VIVO (Todas obrigatórias)

**1. Gols no 2T**
- **Gols marcados no 2T:** Mínimo 1
- **Tempo desde último gol:** MÁXIMO 5 minutos

**2. Estatísticas do 2T**
- **Ataques Perigosos no 2T (Ambos Somados):** Mínimo 10
- **Chutes no Gol no 2T (Ambos Somados):** Mínimo 4
- **Grandes Chances no 2T (Ambos Somados):** Mínimo 2

**3. Ritmo de Jogo**
- Jogo muito aberto
- Ambos times atacando
- Espaços aparecendo

**4. Pressão**
- **Barra de Pressão (Qualquer Time):** Mínimo 65%
- Jogo em alta intensidade

#### 📊 Condições PRÉ-JOGO (Todas obrigatórias)

> **Sobre as Médias H2H:** Calculadas com base nos últimos 5 jogos:  
> • Time da casa: últimos 5 jogos em casa  
> • Time visitante: últimos 5 jogos como visitante

**1. Histórico**
- Média de Gols totais (últimos 5 jogos): `Mínimo 3.0`
- Histórico de jogos abertos

**2. Características**
- Ambos times ofensivos
- Defesas frágeis

### 🎯 Cenários Ideais
- ✅ Jogo muito aberto no 2T
- ✅ 1 gol já saiu no 2T e ritmo segue intenso
- ✅ Times que não sabem defender
- ✅ Jogos malucos (Atalanta, Leverkusen, etc)

### ⚠️ Evitar
- ❌ Nenhum gol no 2T ainda
- ❌ Jogo esfriando
- ❌ Time se fechando após marcar

---

## Bot 12 - Favorito Conservador

### 📋 Passo 1: Informações Básicas

**Mercado de Resultado:**
- **Tipo:** Vitória do Favorito
- **Como funciona:** O favorito deve vencer a partida

**Nome do Bot:** `Favorito Conservador`

### ⚙️ Passo 2: Configuração Essencial

**Faixa de Minutos:**
- **De:** 60
- **Até:** 80
- *Por quê?* Fase final onde o domínio do favorito está consolidado

**Odd Mínima de Entrada:** 1.3
- Se não configurar odd, o bot alertará em qualquer odd
- Com odd 1.3, só alertará quando o mercado estiver nesta cotação ou superior

**Valor de Entrada:** 0 (apenas alertas) ou defina seu valor
- 0 = Apenas notificações, sem contabilizar lucro/prejuízo
- [Seu valor] = Contabiliza ROI, lucro e prejuízo automaticamente

**Filtro de Placar:** Favorito vencendo OU empatado
- Favorito em vantagem ou controlando empate

**Gestão de Banca:** 2-3% (Conservador)

### 🎯 Passo 3: Condições

#### ✅ Condições AO VIVO (Todas obrigatórias)

**1. Placar**
- Opção A: Favorito já vencendo (1x0, 2x0, 2x1)
- Opção B: Empate com favorito dominando

**2. Domínio do Favorito**
- **Posse de Bola Favorito:** Mínimo 55%
- **Ataques Perigosos Favorito:** Mínimo 8
- **Chutes no Gol Favorito:** Mínimo 4

**3. Pressão Ofensiva**
- **Barra de Pressão (favorito):** Mínimo 60%
- Favorito no campo de ataque

**4. Visitante**
- Visitante sem reação
- **Chutes visitante:** MÁXIMO 3

#### 📊 Condições PRÉ-JOGO (Todas obrigatórias)

> **Sobre as Médias H2H:** Calculadas com base nos últimos 5 jogos:  
> • Time da casa: últimos 5 jogos em casa  
> • Time visitante: últimos 5 jogos como visitante

**1. Odds**
- Odd do Favorito: `Entre 1.20 e 1.50` (claro favorito)

**2. Histórico**
- Favorito vence visitante frequentemente
- Mando de campo forte

**3. Forma**
- Favorito em boa fase
- Visitante em má fase

### 🎯 Cenários Ideais
- ✅ Favorito vencendo 1x0 e controlando
- ✅ Empate mas favorito dominando completamente
- ✅ Mando de campo forte
- ✅ Visitante sem reação

### ⚠️ Evitar
- ❌ Favorito perdendo
- ❌ Jogo muito equilibrado
- ❌ Visitante criando chances

---

## Bot 13 - Favorito Agressivo (Virada)

### 📋 Passo 1: Informações Básicas

**Mercado de Resultado:**
- **Tipo:** Vitória do Favorito
- **Como funciona:** O favorito deve vencer a partida (virar o jogo)

**Nome do Bot:** `Favorito Virada`

### ⚙️ Passo 2: Configuração Essencial

**Faixa de Minutos:**
- **De:** 55
- **Até:** 75
- *Por quê?* Tempo ideal para virada - suficiente para reagir mas com urgência

**Odd Mínima de Entrada:** 1.8
- Se não configurar odd, o bot alertará em qualquer odd
- Com odd 1.8, só alertará quando o mercado estiver nesta cotação ou superior

**Valor de Entrada:** 0 (apenas alertas) ou defina seu valor
- 0 = Apenas notificações, sem contabilizar lucro/prejuízo
- [Seu valor] = Contabiliza ROI, lucro e prejuízo automaticamente

**Filtro de Placar:** Favorito perdendo por 1 gol
- Favorito em desvantagem mínima

**Gestão de Banca:** 3-5% (Agressivo)

### 🎯 Passo 3: Condições

#### ✅ Condições AO VIVO (Todas obrigatórias)

**1. Placar**
- **Favorito perdendo:** 0x1 ou 1x2
- Diferença de apenas 1 gol

**2. Pressão Extrema do Favorito**
- **Posse de Bola Favorito:** Mínimo 65%
- **Ataques Perigosos Favorito:** Mínimo 12
- **Barra de Pressão:** Mínimo 70%

**3. Finalizações**
- **Chutes no Gol Favorito:** Mínimo 6
- **Grandes Chances Favorito:** Mínimo 3
- Favorito bombardeando

**4. Defesa Visitante**
- Visitante apenas se defendendo
- **Defesas goleiro visitante:** Mínimo 5
- Visitante sem contra-ataques efetivos

**5. Mudanças Táticas**
- Substituições ofensivas feitas
- All-in do favorito

#### 📊 Condições PRÉ-JOGO (Todas obrigatórias)

> **Sobre as Médias H2H:** Calculadas com base nos últimos 5 jogos:  
> • Time da casa: últimos 5 jogos em casa  
> • Time visitante: últimos 5 jogos como visitante

**1. Odds**
- Odd do Favorito (pré-jogo): `MÁXIMO 1.40` (grande favorito)
- Zebra acontecendo

**2. Capacidade de Reação**
- Favorito tem histórico de viradas
- Elenco forte para reagir

### 🎯 Cenários Ideais
- ✅ Grande favorito perdendo 0x1
- ✅ Favorito atacando desesperadamente
- ✅ Visitante só se defendendo
- ✅ Muitas chances sendo criadas
- ✅ Minuto 60-70 (tempo suficiente)

### ⚠️ Evitar
- ❌ Favorito perdendo por 2+ gols
- ❌ Visitante contra-atacando bem
- ❌ Muito pouco tempo restante (85min+)
- ❌ Favorito sem inspiração

---

## Bot 14 - Visitante Moderado (Value)

### 📋 Passo 1: Informações Básicas

**Mercado de Resultado:**
- **Tipo:** Vitória do Visitante
- **Como funciona:** O visitante deve vencer a partida

**Nome do Bot:** `Visitante Value`

### ⚙️ Passo 2: Configuração Essencial

**Faixa de Minutos:**
- **De:** 55
- **Até:** 75
- *Por quê?* Tempo onde o visitante já consolidou vantagem ou está controlando

**Odd Mínima de Entrada:** 2.0
- Se não configurar odd, o bot alertará em qualquer odd
- Com odd 2.0, só alertará quando o mercado estiver nesta cotação ou superior

**Valor de Entrada:** 0 (apenas alertas) ou defina seu valor
- 0 = Apenas notificações, sem contabilizar lucro/prejuízo
- [Seu valor] = Contabiliza ROI, lucro e prejuízo automaticamente

**Filtro de Placar:** Visitante vencendo OU empatado
- Visitante em vantagem ou controlando empate

**Gestão de Banca:** 2-4% (Moderado)

### 🎯 Passo 3: Condições

#### ✅ Condições AO VIVO (Todas obrigatórias)

**1. Placar**
- Opção A: Visitante vencendo (0x1, 0x2, 1x2)
- Opção B: Empate com visitante defendendo bem

**2. Organização Defensiva**
- **Defesas goleiro visitante:** Mínimo 4
- **Chutes bloqueados visitante:** Mínimo 3
- Defesa sólida do visitante

**3. Eficiência do Visitante**
- Se vencendo: Contra-ataques perigosos
- Aproveitamento de chances: Alto
- Jogo sob controle

**4. Casa sem Efetividade**
- Posse casa pode ser alta, mas sem converter
- Chutes no gol casa sem efetividade
- Casa nervoso/ansioso

#### 📊 Condições PRÉ-JOGO (Todas obrigatórias)

> **Sobre as Médias H2H:** Calculadas com base nos últimos 5 jogos:  
> • Time da casa: últimos 5 jogos em casa  
> • Time visitante: últimos 5 jogos como visitante

**1. Odds**
- Odd do Visitante: `Entre 2.50 e 4.00`
- Value na odd atual ao vivo

**2. Visitante**
- Visitante organizado
- Bom histórico fora de casa
- Qualidade para segurar resultado

**3. Casa**
- Casa não é tão forte em casa
- Histórico de tropeços

### 🎯 Cenários Ideais
- ✅ Visitante vencendo 0x1 e controlando
- ✅ Defesa visitante muito sólida
- ✅ Casa atacando sem efetividade
- ✅ Contra-ataques visitantes perigosos
- ✅ Visitante com qualidade (não é zebra pura)

### ⚠️ Evitar
- ❌ Visitante sendo massacrado
- ❌ Gol visitante foi sorte/erro bizarro
- ❌ Casa dominando completamente
- ❌ Visitante muito inferior tecnicamente

---

## 📊 Resumo de Gestão de Banca

| Perfil | Bots | % Banca |
|--------|------|---------|
| **Conservador** | 01, 04, 07, 10, 12 | 1-2% |
| **Moderado** | 02, 05, 08, 14 | 2-3% |
| **Agressivo** | 03, 06, 09, 11, 13 | 2-5% |

---

## ⚠️ Regras Gerais Importantes

### 🚫 Nunca Faça
1. ❌ Entre em mais de um bot no mesmo jogo
2. ❌ Ignore as condições pré-jogo
3. ❌ Entre sem verificar TODAS as condições
4. ❌ Aumente a banca após losses (Martingale)
5. ❌ Entre fora da faixa de minutos especificada

### ✅ Sempre Faça
1. ✅ Verifique todas as condições (AO VIVO + PRÉ-JOGO)
2. ✅ Respeite a gestão de banca
3. ✅ Entre apenas na odd mínima especificada
4. ✅ Aguarde a faixa de minutos correta
5. ✅ Analise o contexto do jogo

### 📝 Dicas de Uso
- **Diversifique:** Use bots de mercados diferentes
- **Priorize:** Bots conservadores para começar
- **Registre:** Anote os resultados de cada bot
- **Ajuste:** Após 50+ entradas, analise e ajuste se necessário
- **Paciência:** Não force entradas - aguarde as condições ideais

---

## 🎯 Checklist Antes de Entrar

Antes de confirmar qualquer aposta, verifique:

- [ ] Todas as condições AO VIVO foram atendidas?
- [ ] Todas as condições PRÉ-JOGO foram atendidas?
- [ ] Estou na faixa de minutos correta?
- [ ] A odd está acima da mínima especificada?
- [ ] O placar está de acordo (quando aplicável)?
- [ ] A gestão de banca está correta (% da banca total)?
- [ ] Não estou em tilt ou forçando entrada?

**Se TODAS as respostas forem SIM, pode entrar. Se alguma for NÃO, NÃO ENTRE!**

---

## 📞 Suporte

Dúvidas? Revise:
1. **GUIA-14-BOTS-ESPECIALIZADOS.md** - Explicações detalhadas
2. **REFERENCIA-RAPIDA-14-BOTS.md** - Tabelas resumidas
3. **sokkerprobots.pdf** - Regras do SokkerPRO

**Bons greens! 🟢⚽**
