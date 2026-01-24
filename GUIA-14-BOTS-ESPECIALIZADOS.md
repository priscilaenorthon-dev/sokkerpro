# 📊 14 Bots Especializados SokkerPRO

## 🎯 Visão Geral

Este guia apresenta **14 bots especializados** para os principais mercados do SokkerPRO, com estratégias conservadoras, moderadas e agressivas.

### Distribuição por Mercado:
- **Escanteios:** 3 bots (Conservador, Moderado, Agressivo)
- **Gols 1º Tempo:** 3 bots (Conservador Over, Moderado Over 1.5, Agressivo Under)
- **Empate:** 3 bots (Conservador, Moderado Tático, Agressivo Zebra)
- **Gols 2º Tempo:** 2 bots (Conservador Over, Agressivo Over 1.5)
- **Vitória Favorito:** 2 bots (Conservador, Agressivo Virada)
- **Vitória Visitante:** 1 bot (Moderado Value)

---

## 📐 ESCANTEIOS - Bot 01: Conservador - Over 8.5

## 📋 Passo 1: Informações Básicas

### Mercado
**Over 8.5 Escanteios** - 9 ou mais corners no jogo completo

### Como Funciona
Estratégia conservadora para detectar jogos com bom volume de escanteios, focando em projeções seguras e histórico consistente.

### Nome do Bot
`bot-escanteios-conservador-8-5`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**25 até 70**

**Por quê?**  
Tempo para confirmar ritmo de corners e ainda ter margem para atingir 9+ escanteios.

### Odd Mínima de Entrada
**1.5**

**Por quê?**  
Esta odd garante valor mínimo para suas entradas. O bot pode gerar APENAS alertas (sem entradas automáticas) ou fazer entradas automáticas, dependendo da configuração do valor de entrada.

### Valor de Entrada
- **0** = Apenas alertas (você decide manualmente se entra)
- **Valor definido** = Bot contabiliza lucro/prejuízo automaticamente

### Filtro de Placar
**Qualquer**

**Por quê?**  
O importante é o volume de ataques e pressão, independente do placar.

### Gestão de Banca
- **Recomendado:** 1-2% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

- ✅ **Mínimo 5 escanteios já ocorridos**
- ✅ **Projeção de 11+ escanteios no final**
- ✅ **12+ ataques perigosos totais (Ambos Somados)**
- ✅ **65%+ barra de pressão (Qualquer Time)**

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

- ✅ **Média histórica de 9.5+ escanteios**

**Ideal Para:**
- Premier League
- Jogos com times que atacam pelas laterais
- Muito ataque desde o início

---

## 📐 ESCANTEIOS - Bot 02: Moderado - Over 10.5

## 📋 Passo 1: Informações Básicas

### Mercado
**Over 10.5 Escanteios** - 11 ou mais corners no jogo completo

### Como Funciona
Estratégia moderada para jogos muito ofensivos com alto volume de escanteios e pressão constante.

### Nome do Bot
`bot-escanteios-moderado-10-5`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**20 até 65**

**Por quê?**  
Identificar ritmo acelerado de corners cedo e ter tempo suficiente para atingir 11+ escanteios.

### Odd Mínima de Entrada
**1.6**

**Por quê?**  
Esta odd garante valor mínimo para suas entradas. O bot pode gerar APENAS alertas (sem entradas automáticas) ou fazer entradas automáticas, dependendo da configuração do valor de entrada.

### Valor de Entrada
- **0** = Apenas alertas (você decide manualmente se entra)
- **Valor definido** = Bot contabiliza lucro/prejuízo automaticamente

### Filtro de Placar
**Qualquer**

**Por quê?**  
O importante é o ritmo acelerado de escanteios.

### Gestão de Banca
- **Recomendado:** 2-3% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

- ✅ **Mínimo 6 escanteios ocorridos**
- ✅ **3+ escanteios nos últimos 10min**
- ✅ **Projeção de 13+ escanteios**
- ✅ **15+ ataques perigosos totais (Ambos Somados)**
- ✅ **4+ chutes bloqueados**

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

- ✅ **Média histórica de 11+ escanteios**

**Ideal Para:**
- Jogos muito ofensivos
- Ambos times atacando
- Histórico de muitos corners

---

## 📐 ESCANTEIOS - Bot 03: Agressivo - Under 7.5

## 📋 Passo 1: Informações Básicas

### Mercado
**Under 7.5 Escanteios** - Máximo 7 corners no jogo completo

### Como Funciona
Estratégia agressiva para jogos travados e táticos com poucos escanteios.

### Nome do Bot
`bot-escanteios-agressivo-under-7-5`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**30 até 70**

**Por quê?**  
Confirmar que o jogo está travado com poucos corners antes de entrar.

### Odd Mínima de Entrada
**1.5**

**Por quê?**  
Esta odd garante valor mínimo para suas entradas. O bot pode gerar APENAS alertas (sem entradas automáticas) ou fazer entradas automáticas, dependendo da configuração do valor de entrada.

### Valor de Entrada
- **0** = Apenas alertas (você decide manualmente se entra)
- **Valor definido** = Bot contabiliza lucro/prejuízo automaticamente

### Filtro de Placar
**Qualquer**

**Por quê?**  
O importante é a falta de pressão ofensiva e poucos ataques pelas laterais.

### Gestão de Banca
- **Recomendado:** 2-4% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **⚠️ ATENÇÃO:** Condições INVERSAS - Usamos MÁXIMO em vez de MÍNIMO!

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

- ✅ **MÁXIMO 3 escanteios ocorridos**
- ✅ **Projeção de máx 7 corners**
- ✅ **MÁXIMO 8 ataques perigosos (Ambos Somados)**
- ✅ **Diferença de posse máx 15%**

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

- ✅ **Média histórica máx 8 corners**

**Ideal Para:**
- Jogos travados, táticos
- Times defensivos
- Clássicos estudados

---

## ⚽ GOLS 1T - Bot 04: Conservador - Over 0.5

## 📋 Passo 1: Informações Básicas

### Mercado
**Over 0.5 Gols (Primeiro Tempo)** - Pelo menos 1 gol no 1T

### Como Funciona
Estratégia conservadora para detectar jogos com chances reais de gol no primeiro tempo.

### Nome do Bot
`bot-gol-1t-conservador`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**15 até 35**

**Por quê?**  
Avaliar ritmo ofensivo e ainda ter tempo para o gol sair no 1T.

### Odd Mínima de Entrada
**1.4**

**Por quê?**  
Esta odd garante valor mínimo para suas entradas. O bot pode gerar APENAS alertas (sem entradas automáticas) ou fazer entradas automáticas, dependendo da configuração do valor de entrada.

### Valor de Entrada
- **0** = Apenas alertas (você decide manualmente se entra)
- **Valor definido** = Bot contabiliza lucro/prejuízo automaticamente

### Filtro de Placar
**Empate (0x0)**

**Por quê?**  
Jogo ainda sem gols, mas com chances sendo criadas.

### Gestão de Banca
- **Recomendado:** 1-2% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

- ✅ **6+ ataques perigosos (Ambos Somados)**
- ✅ **2+ grandes chances criadas**
- ✅ **3+ chutes no gol (Ambos Somados)**
- ✅ **60%+ barra de pressão (Qualquer Time)**

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

- ✅ **Média histórica 1.2+ gols no 1T**
- ✅ **60%+ prognóstico Over 0.5 1T**

**Ideal Para:**
- Jogos equilibrados ofensivos
- Ligas movimentadas
- Times que marcam cedo

---

## ⚽ GOLS 1T - Bot 05: Moderado - Over 1.5

## 📋 Passo 1: Informações Básicas

### Mercado
**Over 1.5 Gols (Primeiro Tempo)** - 2 ou mais gols no 1T

### Como Funciona
Estratégia moderada para jogos muito abertos com múltiplos gols esperados no primeiro tempo.

### Nome do Bot
`bot-gol-1t-moderado-1-5`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**15 até 40**

**Por quê?**  
Se já tem 1 gol, avaliar se há tempo e ritmo para sair outro no 1T.

### Odd Mínima de Entrada
**1.8**

**Por quê?**  
Esta odd garante valor mínimo para suas entradas. O bot pode gerar APENAS alertas (sem entradas automáticas) ou fazer entradas automáticas, dependendo da configuração do valor de entrada.

### Valor de Entrada
- **0** = Apenas alertas (você decide manualmente se entra)
- **Valor definido** = Bot contabiliza lucro/prejuízo automaticamente

### Filtro de Placar
**Pelo menos 1 gol marcado**

**Por quê?**  
Jogo já aberto, buscando mais gols no 1T.

### Gestão de Banca
- **Recomendado:** 2-3% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

- ✅ **Mínimo 1 gol já marcado**
- ✅ **10+ ataques perigosos (Ambos Somados)**
- ✅ **5+ chutes no gol (Ambos Somados)**
- ✅ **Jogo aberto (espaços)**

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

- ✅ **Média histórica 1.5+ gols 1T**
- ✅ **50%+ prognóstico Over 1.5 1T**

**Ideal Para:**
- Jogo 1x0 ou 1x1 aos 20-25min
- Times muito ofensivos
- Jogo aberto com espaços

---

## ⚽ GOLS 1T - Bot 06: Agressivo - Under 0.5

## 📋 Passo 1: Informações Básicas

### Mercado
**Under 0.5 Gols (Primeiro Tempo)** - SEM gols no 1T

### Como Funciona
Estratégia agressiva para jogos muito travados onde não se espera gol no primeiro tempo.

### Nome do Bot
`bot-sem-gol-1t-agressivo`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**20 até 40**

**Por quê?**  
Confirmar que jogo está travado antes de entrar, mas ainda no 1T.

### Odd Mínima de Entrada
**1.5**

**Por quê?**  
Esta odd garante valor mínimo para suas entradas. O bot pode gerar APENAS alertas (sem entradas automáticas) ou fazer entradas automáticas, dependendo da configuração do valor de entrada.

### Valor de Entrada
- **0** = Apenas alertas (você decide manualmente se entra)
- **Valor definido** = Bot contabiliza lucro/prejuízo automaticamente

### Filtro de Placar
**0x0 OBRIGATÓRIO**

**Por quê?**  
Se já saiu gol, a aposta já está perdida!

### Gestão de Banca
- **Recomendado:** 2-4% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **⚠️ ATENÇÃO:** Condições INVERSAS - Usamos MÁXIMO em vez de MÍNIMO!

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

- ✅ **0 gols (obrigatório)**
- ✅ **MÁXIMO 4 ataques perigosos (Ambos Somados)**
- ✅ **MÁXIMO 1 grande chance**
- ✅ **MÁXIMO 2 chutes no gol (Ambos Somados)**
- ✅ **Diferença posse máx 10%**

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

- ✅ **Média histórica máx 0.7 gols 1T**

**Ideal Para:**
- Clássicos equilibrados
- Jogos muito travados
- Times táticos

**⚠️ ALERTA:** Se sair gol, perda imediata

---

## 🤝 EMPATE - Bot 07: Conservador - Draw

## 📋 Passo 1: Informações Básicas

### Mercado
**Empate (Draw)** - Jogo termina empatado

### Como Funciona
Estratégia conservadora para jogos muito equilibrados onde o empate é o resultado mais provável.

### Nome do Bot
`bot-empate-conservador`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**60 até 80**

**Por quê?**  
Jogo próximo do fim, ainda empatado, com equilíbrio claro.

### Odd Mínima de Entrada
**2.0**

**Por quê?**  
Esta odd garante valor mínimo para suas entradas. O bot pode gerar APENAS alertas (sem entradas automáticas) ou fazer entradas automáticas, dependendo da configuração do valor de entrada.

### Valor de Entrada
- **0** = Apenas alertas (você decide manualmente se entra)
- **Valor definido** = Bot contabiliza lucro/prejuízo automaticamente

### Filtro de Placar
**Empate (0x0 ou 1x1)**

**Por quê?**  
Jogo deve estar empatado para apostar no empate final.

### Gestão de Banca
- **Recomendado:** 1-2% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

- ✅ **Jogo empatado**
- ✅ **Diferença máx 3 finalizações**
- ✅ **Diferença máx 10% posse**
- ✅ **Diferença máx 3 ataques**

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

- ✅ **40%+ empates recentes**
- ✅ **Times de nível similar**

**Ideal Para:**
- Jogos muito equilibrados
- Times satisfeitos com empate
- Nível técnico similar

---

## 🤝 EMPATE - Bot 08: Moderado - Draw Tático

## 📋 Passo 1: Informações Básicas

### Mercado
**Empate (Draw)** - Jogo termina empatado (foco em jogos táticos)

### Como Funciona
Estratégia moderada para jogos travados onde ambos preferem não perder.

### Nome do Bot
`bot-empate-moderado-tatico`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**50 até 75**

**Por quê?**  
Jogo tático se confirmando, ambos controlando sem arriscar.

### Odd Mínima de Entrada
**2.2**

**Por quê?**  
Esta odd garante valor mínimo para suas entradas. O bot pode gerar APENAS alertas (sem entradas automáticas) ou fazer entradas automáticas, dependendo da configuração do valor de entrada.

### Valor de Entrada
- **0** = Apenas alertas (você decide manualmente se entra)
- **Valor definido** = Bot contabiliza lucro/prejuízo automaticamente

### Filtro de Placar
**Empate (0x0 ou 1x1)**

**Por quê?**  
Jogo deve estar empatado para apostar no empate final.

### Gestão de Banca
- **Recomendado:** 2-3% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

- ✅ **Jogo empatado**
- ✅ **Jogo travado/tático**
- ✅ **12+ faltas (jogo pegado)**
- ✅ **Ritmo lento/controlado**

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

- ✅ **Jogo importante (final, semi, derby)**

**Ideal Para:**
- Finais e semifinais
- Derbies
- Jogos onde empate é aceitável

---

## 🤝 EMPATE - Bot 09: Agressivo - Draw Zebra

## 📋 Passo 1: Informações Básicas

### Mercado
**Empate (Draw)** - Favorito sendo surpreendido

### Como Funciona
Estratégia agressiva para quando o favorito não está vencendo e pode empatar.

### Nome do Bot
`bot-empate-agressivo-zebra`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**45 até 70**

**Por quê?**  
Zebra em andamento, favorito pressionando mas sem sucesso.

### Odd Mínima de Entrada
**2.5**

**Por quê?**  
Esta odd garante valor mínimo para suas entradas. O bot pode gerar APENAS alertas (sem entradas automáticas) ou fazer entradas automáticas, dependendo da configuração do valor de entrada.

### Valor de Entrada
- **0** = Apenas alertas (você decide manualmente se entra)
- **Valor definido** = Bot contabiliza lucro/prejuízo automaticamente

### Filtro de Placar
**Empate ou visitante vencendo**

**Por quê?**  
Favorito não está vencendo, situação de zebra.

### Gestão de Banca
- **Recomendado:** 3-5% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

- ✅ **Favorito não vencendo**
- ✅ **Favorito pressionando (60%+)**
- ✅ **Visitante defendendo bem**
- ✅ **2+ chances contra-ataque visitante**

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

- ✅ **Odds favorito pré-jogo < 1.5**

**Ideal Para:**
- Favorito sendo surpreendido
- Visitante surpreendendo
- Zebra em andamento

---

## ⏱️ GOLS 2T - Bot 10: Conservador - Over 0.5

## 📋 Passo 1: Informações Básicas

### Mercado
**Over 0.5 Gols (Segundo Tempo)** - Pelo menos 1 gol no 2T

### Como Funciona
Estratégia conservadora para quando time precisa de gol no segundo tempo.

### Nome do Bot
`bot-gol-2t-conservador`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**50 até 75**

**Por quê?**  
Time mostrando urgência, ainda com tempo para o gol sair.

### Odd Mínima de Entrada
**1.4**

**Por quê?**  
Esta odd garante valor mínimo para suas entradas. O bot pode gerar APENAS alertas (sem entradas automáticas) ou fazer entradas automáticas, dependendo da configuração do valor de entrada.

### Valor de Entrada
- **0** = Apenas alertas (você decide manualmente se entra)
- **Valor definido** = Bot contabiliza lucro/prejuízo automaticamente

### Filtro de Placar
**Qualquer**

**Por quê?**  
O importante é a urgência e pressão ofensiva no 2T.

### Gestão de Banca
- **Recomendado:** 1-2% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

- ✅ **Time precisa de gol**
- ✅ **4+ ataques perigosos no 2T**
- ✅ **1+ atacante entrou (substituição)**

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

- ✅ **Média histórica 1.3+ gols 2T**
- ✅ **60%+ prognóstico Over 0.5 2T**

**Ideal Para:**
- Favorito empatando/perdendo
- Substituições ofensivas
- Time precisando vencer

---

## ⏱️ GOLS 2T - Bot 11: Agressivo - Over 1.5

## 📋 Passo 1: Informações Básicas

### Mercado
**Over 1.5 Gols (Segundo Tempo)** - 2 ou mais gols no 2T

### Como Funciona
Estratégia agressiva para segundo tempo muito aberto com múltiplos gols esperados.

### Nome do Bot
`bot-gol-2t-agressivo-1-5`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**50 até 70**

**Por quê?**  
2T aberto, tempo para saírem 2+ gols.

### Odd Mínima de Entrada
**2.0**

**Por quê?**  
Esta odd garante valor mínimo para suas entradas. O bot pode gerar APENAS alertas (sem entradas automáticas) ou fazer entradas automáticas, dependendo da configuração do valor de entrada.

### Valor de Entrada
- **0** = Apenas alertas (você decide manualmente se entra)
- **Valor definido** = Bot contabiliza lucro/prejuízo automaticamente

### Filtro de Placar
**Qualquer**

**Por quê?**  
O importante é o jogo estar aberto no 2T com ambos atacando.

### Gestão de Banca
- **Recomendado:** 3-4% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

- ✅ **Mínimo 1 gol já no 2T**
- ✅ **Jogo muito aberto**
- ✅ **Ambos atacando**
- ✅ **6+ ataques perigosos 2T (Ambos Somados)**

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

- ✅ **Média histórica 1.8+ gols 2T**

**Ideal Para:**
- 2T aberto (1x0, 1x1)
- Time perdendo pressionando
- Jogo com espaços

---

## 🏆 FAVORITO - Bot 12: Conservador

## 📋 Passo 1: Informações Básicas

### Mercado
**Vitória do Favorito** - Time favorito vence a partida

### Como Funciona
Estratégia conservadora para favorito dominando e próximo de vencer.

### Nome do Bot
`bot-favorito-conservador`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**60 até 80**

**Por quê?**  
Favorito dominando, jogo próximo do fim.

### Odd Mínima de Entrada
**1.3**

**Por quê?**  
Esta odd garante valor mínimo para suas entradas. O bot pode gerar APENAS alertas (sem entradas automáticas) ou fazer entradas automáticas, dependendo da configuração do valor de entrada.

### Valor de Entrada
- **0** = Apenas alertas (você decide manualmente se entra)
- **Valor definido** = Bot contabiliza lucro/prejuízo automaticamente

### Filtro de Placar
**Favorito vencendo ou empatado**

**Por quê?**  
Favorito em posição de vencer ou pressionar para vitória.

### Gestão de Banca
- **Recomendado:** 2-3% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

- ✅ **Favorito vencendo por 1 ou empatado**
- ✅ **55%+ posse favorito**
- ✅ **8+ finalizações favorito**
- ✅ **65%+ pressão favorito**
- ✅ **Máx 2 chances contra-ataque visitante**

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

- ✅ **Odds favorito pré < 1.7**

**Ideal Para:**
- Favorito dominando
- Visitante sem chances
- Favorito 1x0 ou 0x0 pressionando

---

## 🏆 FAVORITO - Bot 13: Agressivo - Virada

## 📋 Passo 1: Informações Básicas

### Mercado
**Vitória do Favorito (Virada)** - Favorito vira o jogo

### Como Funciona
Estratégia agressiva para favorito perdendo mas com grande pressão para virar.

### Nome do Bot
`bot-favorito-agressivo-virada`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**55 até 75**

**Por quê?**  
Favorito perdendo, pressão máxima, ainda com tempo.

### Odd Mínima de Entrada
**1.8**

**Por quê?**  
Esta odd garante valor mínimo para suas entradas. O bot pode gerar APENAS alertas (sem entradas automáticas) ou fazer entradas automáticas, dependendo da configuração do valor de entrada.

### Valor de Entrada
- **0** = Apenas alertas (você decide manualmente se entra)
- **Valor definido** = Bot contabiliza lucro/prejuízo automaticamente

### Filtro de Placar
**Favorito perdendo por 1 gol**

**Por quê?**  
Situação de virada, favorito pressionando muito.

### Gestão de Banca
- **Recomendado:** 3-5% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

- ✅ **Favorito perdendo por 1 (0x1, 1x2)**
- ✅ **70%+ pressão favorito**
- ✅ **10+ finalizações favorito**
- ✅ **2+ substituições ofensivas**
- ✅ **Adversário cansado/apenas defendendo**

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

- ✅ **Odds favorito pré < 1.5**

**Ideal Para:**
- Favorito forte perdendo injustamente
- Visitante apenas defendendo
- Odds altas por situação

---

## 🚌 VISITANTE - Bot 14: Moderado - Away Value

## 📋 Passo 1: Informações Básicas

### Mercado
**Vitória do Visitante** - Time visitante vence a partida

### Como Funciona
Estratégia moderada para visitante surpreendendo e segurando o resultado.

### Nome do Bot
`bot-visitante-moderado-value`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**55 até 75**

**Por quê?**  
Visitante vencendo/empatando, defendendo bem.

### Odd Mínima de Entrada
**2.0**

**Por quê?**  
Esta odd garante valor mínimo para suas entradas. O bot pode gerar APENAS alertas (sem entradas automáticas) ou fazer entradas automáticas, dependendo da configuração do valor de entrada.

### Valor de Entrada
- **0** = Apenas alertas (você decide manualmente se entra)
- **Valor definido** = Bot contabiliza lucro/prejuízo automaticamente

### Filtro de Placar
**Visitante vencendo ou empatado**

**Por quê?**  
Visitante em posição de vencer ou segurar empate e buscar vitória.

### Gestão de Banca
- **Recomendado:** 2-4% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

- ✅ **Visitante vencendo por 1 ou empatado**
- ✅ **Defesa visitante organizada**
- ✅ **3+ contra-ataques perigosos visitante**
- ✅ **2+ cartões amarelos casa (nervosa)**
- ✅ **Casa pressionando sem efetividade**
- ✅ **5+ chutes fora da casa**

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

- ✅ **35%+ vitórias fora visitante**
- ✅ **Odds visitante pré > 2.5**

**Ideal Para:**
- Visitante 0x1 defendendo bem
- Casa pressionando sem sucesso
- Bons contra-ataques

---

## 📊 Resumo Estratégico

### Por Perfil de Risco:

**CONSERVADOR (5 bots):**
- Bot 01: Escanteios Over 8.5
- Bot 04: Gol 1T Over 0.5
- Bot 07: Empate Equilibrado
- Bot 10: Gol 2T Over 0.5
- Bot 12: Favorito Dominante

**MODERADO (5 bots):**
- Bot 02: Escanteios Over 10.5
- Bot 05: Gol 1T Over 1.5
- Bot 08: Empate Tático
- Bot 14: Visitante Value

**AGRESSIVO (4 bots):**
- Bot 03: Escanteios Under 7.5
- Bot 06: Sem Gol 1T
- Bot 09: Empate Zebra
- Bot 11: Gol 2T Over 1.5
- Bot 13: Favorito Virada

---

## ⚠️ REGRAS GERAIS

### Gestão de Banca:
- **Conservador:** 1-2% por entrada
- **Moderado:** 2-3% por entrada
- **Agressivo:** 2-5% por entrada
- **NUNCA** mais de 5% em uma única entrada

### Não Combine:
- ❌ Over e Under do mesmo mercado
- ❌ Múltiplos bots agressivos simultaneamente
- ❌ Bots conflitantes no mesmo jogo

### Priorize:
- ✅ Dados ao vivo confirmados
- ✅ Histórico sólido
- ✅ Contexto do jogo
- ✅ Qualidade sobre quantidade

---

**Boa sorte e boas apostas! 🍀⚽💰**
