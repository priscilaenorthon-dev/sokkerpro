# 🎯 4 Bots Essenciais para SokkerPRO

## 📋 Sobre Estes Bots

Complementam perfeitamente os bots que você já tem:
- ✅ Over Limite 75%
- ✅ Sair gol no segundo tempo
- ✅ Ambas Marcam
- ✅ Sem gol no Primeiro Tempo

---

## ⚽ Bot 1: Over 2.5 Gols (Jogo Completo)

## 📋 Passo 1: Informações Básicas

### Mercado
**Over 2.5 Gols** - Jogo completo terá 3 ou mais gols

### Como Funciona
Detecta jogos que terão **3 ou mais gols** no tempo completo, buscando partidas abertas com ambos os times atacando e criando chances.

### Nome do Bot
`bot-over-2-5-gols`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**15 até 75**

**Por quê?**  
Período suficiente para avaliar se o jogo tem ritmo ofensivo, mas ainda com tempo para os 3 gols saírem.

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
Idealmente com pelo menos 1 gol já marcado (1x0, 1x1, 2x0, etc.), indicando que o jogo está movimentado.

### Gestão de Banca
- **Recomendado:** 1-2% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

**4 Condições Principais:**
1. **Pelo menos 1 gol já marcado** - Jogo movimentado
2. **12+ ataques perigosos (Ambos Somados)** - Alto volume ofensivo
3. **6+ chutes no gol (Ambos Somados)** - Muitas finalizações
4. **60%+ barra de pressão (Qualquer Time)** - Dominância ofensiva

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

**3 Condições Principais:**
1. **2.8+ média de gols total (histórico)** - Times costumam fazer jogos com gols
2. **55%+ prognóstico Over 2.5** - Probabilidade alta
3. **60%+ prognóstico Ambas Marcam** - Ambos costumam balançar as redes

---

## 💡 Cenários Ideais

**✅ PERFEITO:**
- Jogo já tem 1-2 gols (1x1, 2x0, 1x2)
- Times ofensivos (Man City, Bayern, PSG)
- Ligas ofensivas (Eredivisie, Bundesliga, Brasileirão)
- Ambos times atacando
- Time perdendo buscando empate/vitória

**❌ EVITAR:**
- Jogo 0x0 muito travado
- Times muito defensivos
- Ligas táticas e fechadas

### 🏆 Melhores Ligas
- 🇳🇱 Eredivisie (Holanda) ⭐⭐⭐
- 🇩🇪 Bundesliga (Alemanha) ⭐⭐⭐
- 🇧🇷 Brasileirão ⭐⭐⭐
- 🏴󠁧󠁢󠁥󠁮󠁧󠁿 Premier League ⭐⭐

---

## 🚫 Bot 2: Under 2.5 Gols (Jogo Completo)

## 📋 Passo 1: Informações Básicas

### Mercado
**Under 2.5 Gols** - Jogo completo terá máximo 2 gols

### Como Funciona
Detecta jogos que terão **máximo 2 gols** no tempo completo, focando em partidas travadas, defensivas e com poucas chances criadas.

### Nome do Bot
`bot-under-2-5-gols`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**15 até 75**

**Por quê?**  
Período para confirmar que o jogo está travado e sem muitas chances, indicando tendência de poucos gols.

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
Idealmente 0x0 ou 1x0 após 30+ minutos, indicando jogo fechado.

### Gestão de Banca
- **Recomendado:** 1-2% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **⚠️ ATENÇÃO:** Condições INVERSAS - Usamos MÁXIMO em vez de MÍNIMO!

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

**3 Condições Principais (MÁXIMOS):**
1. **MÁXIMO 1 gol marcado** - Jogo ainda fechado
2. **MÁXIMO 8 ataques perigosos (Ambos Somados)** - Pouca movimentação
3. **MÁXIMO 4 chutes no gol (Ambos Somados)** - Poucas finalizações

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

**2 Condições Principais:**
1. **MÁXIMO 2.2 média de gols total** - Histórico de jogos fechados
2. **MÍNIMO 55% prognóstico Under 2.5** - Probabilidade alta

---

## 💡 Cenários Ideais

**✅ PERFEITO:**
- Jogo 0x0 ou 1x0 após 30+ minutos
- Times defensivos (Getafe, Atlético-MG)
- Ligas táticas (Serie A, La Liga)
- Poucas chances criadas
- Ambos satisfeitos com empate

**❌ EVITAR:**
- Jogo já tem 2+ gols
- Times muito ofensivos
- Muitas chances criadas

### 🏆 Melhores Ligas
- 🇮🇹 Serie A (Itália) ⭐⭐⭐
- 🇪🇸 La Liga (Espanha - jogos táticos) ⭐⭐
- 🇫🇷 Ligue 1 (França) ⭐⭐

---

## 📐 Bot 3: Over 9.5 Escanteios

## 📋 Passo 1: Informações Básicas

### Mercado
**Over 9.5 Escanteios** - Jogo completo terá 10 ou mais escanteios

### Como Funciona
Detecta jogos que terão **10 ou mais escanteios** no total, buscando partidas com muito ataque pelas laterais e pressão ofensiva constante.

### Nome do Bot
`bot-over-9-5-escanteios`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**20 até 75**

**Por quê?**  
Tempo suficiente para estabelecer um ritmo de escanteios e projetar o total final do jogo.

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

**3 Condições Principais:**
1. **4+ escanteios já ocorridos (aos 20-30min)** - Bom ritmo de corners
2. **2+ escanteios nos últimos 10 minutos** - Continuidade do ritmo
3. **10+ ataques perigosos (Ambos Somados)** - Muita pressão ofensiva

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

**1 Condição Principal:**
1. **10+ média de escanteios total (histórico)** - Times costumam gerar muitos corners

---

## 💡 Fórmula de Projeção

```
Projeção = (Escanteios Atuais / Minuto Atual) × 90

Exemplo:
- 4 escanteios aos 25 minutos
- Projeção = (4 / 25) × 90 = 14.4 escanteios ✅
```

---

## 💡 Cenários Ideais

**✅ PERFEITO:**
- Bom ritmo de escanteios desde início
- Times que atacam pelas laterais
- Jogo equilibrado com muito ataque
- Premier League (conhecida por muitos corners)
- Jogo com muita pressão ofensiva

**❌ EVITAR:**
- Poucos escanteios no início
- Jogo muito travado
- Ritmo lento de corners

### 🏆 Melhores Ligas
- 🏴󠁧󠁢󠁥󠁮󠁧󠁿 Premier League ⭐⭐⭐
- 🇩🇪 Bundesliga ⭐⭐
- 🏴󠁧󠁢󠁥󠁮󠁧󠁿 Championship ⭐⭐

---

## 🟨 Bot 4: Over 4.5 Cartões

## 📋 Passo 1: Informações Básicas

### Mercado
**Over 4.5 Cartões** - Jogo completo terá 5 ou mais cartões (amarelos/vermelhos)

### Como Funciona
Detecta jogos que terão **5 ou mais cartões** no total, focando em partidas nervosas, com muitas faltas, clássicos e jogos decisivos.

### Nome do Bot
`bot-over-4-5-cartoes`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**20 até 75**

**Por quê?**  
Tempo para avaliar se o jogo está "pegado" com muitas faltas e cartões sendo distribuídos.

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
O importante é o nível de rivalidade, faltas e intensidade do jogo, independente do placar.

### Gestão de Banca
- **Recomendado:** 1-2% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

**2 Condições Principais:**
1. **2+ cartões amarelos já dados** - Árbitro distribuindo cartões
2. **15+ faltas cometidas (Ambos Somados)** - Jogo pegado com muitas infrações

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

**1 Condição Principal:**
1. **5+ média de cartões amarelos (histórico)** - Times costumam ser punidos

**Contextos Favoráveis:**
- Clássicos e derbies
- Árbitro rigoroso
- Jogo decisivo/nervoso
- Rivalidade histórica

---

## 💡 Cenários Ideais

**✅ PERFEITO:**
- Clássicos (Fla x Flu, Barça x Real, Boca x River)
- Jogos decisivos (finais, mata-mata)
- Árbitro conhecido por dar muitos cartões
- Jogo equilibrado e nervoso
- Muitas faltas sendo cometidas
- Libertadores e Sul-Americano

**❌ EVITAR:**
- Jogo tranquilo sem faltas
- Árbitro permissivo
- Times sem rivalidade
- Jogo já decidido

### 🏆 Melhores Competições
- 🏆 Libertadores ⭐⭐⭐
- 🇦🇷 Campeonato Argentino ⭐⭐⭐
- 🇧🇷 Brasileirão (clássicos) ⭐⭐
- 🇪🇸 La Liga (derbies) ⭐⭐

---

## 📊 Comparação dos 4 Bots

| Bot | Tipo | Mercado | Condições | Ideal Para |
|-----|------|---------|-----------|------------|
| **Over 2.5** | MÍNIMO | 3+ gols | 7 | Jogos ofensivos |
| **Under 2.5** | MÁXIMO | Max 2 gols | 5 | Jogos defensivos |
| **Over 9.5 Corners** | MÍNIMO | 10+ escanteios | 4 | Muita pressão |
| **Over 4.5 Cards** | MÍNIMO | 5+ cartões | 3 | Jogos pegados |

---

## 🔄 Agora Você Tem 8 Bots!

### Bots Anteriores:
1. ✅ Over Limite 75%
2. ✅ Gol no Segundo Tempo
3. ✅ Ambas Marcam
4. ✅ Sem Gol no Primeiro Tempo

### Bots Novos:
5. ✅ Over 2.5 Gols
6. ✅ Under 2.5 Gols
7. ✅ Over 9.5 Escanteios
8. ✅ Over 4.5 Cartões

**Cobertura completa de mercados! 🎯**

---

## 💡 Como Escolher o Bot Certo

### Por Característica do Jogo:

**Jogo OFENSIVO (muitos ataques):**
→ Over 2.5 Gols, Over Escanteios

**Jogo TRAVADO (poucas chances):**
→ Under 2.5 Gols, Sem Gol 1T

**Jogo NERVOSO (muitas faltas):**
→ Over Cartões

**Jogo EQUILIBRADO (ambos atacando):**
→ Ambas Marcam, Over 2.5

### Por Liga/Competição:

**Eredivisie, Bundesliga:**
→ Over 2.5, Over Escanteios

**Serie A:**
→ Under 2.5, Under 0.5 1T

**Libertadores:**
→ Over Cartões, Jogos pegados

**Premier League:**
→ Over Escanteios, Ambas Marcam

---

## 💰 Gestão de Banca

```
Todos os bots: 1-2% da banca por entrada
Máximo absoluto: 5% da banca
```

---

## ⚠️ Regras de Ouro

1. **NUNCA** combine Over e Under do mesmo mercado
2. **SEMPRE** respeite a gestão de banca
3. **AGUARDE** todas as condições serem atendidas
4. **ANALISE** o contexto do jogo
5. **SEJA PACIENTE** - qualidade > quantidade

---

**Boa sorte e boas apostas! 🍀⚽💰**
