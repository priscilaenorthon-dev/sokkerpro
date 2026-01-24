# ⚡ CONFIGURAÇÃO RÁPIDA - Bot SEM Gol 1º Tempo

> **Seguindo o formato oficial do PDF SokkerPRO**

## 📋 PASSO 1: Informações Básicas

**Mercado de Gols:**
- **Tipo:** Sem mais gols até o fim do primeiro tempo
- **Linha:** Under 0.5 Gols (1T)
- **Como funciona:** Aposta ganha se o primeiro tempo terminar 0x0. Se sair qualquer gol no primeiro tempo (jogo ficar 1x0, 0x1, 1x1, etc.), você perde.

**Nome do Bot:** `Sem Gol 1T` ou `Under 0.5 - 1T`

---

## ⚙️ PASSO 2: Configuração Essencial

```
Faixa de Minutos
├─ De: 10
└─ Até: 35

Odd Mínima de Entrada: 1.5

Valor de Entrada: 0 (para apenas alertas) ou [seu valor] para contabilizar lucro/prejuízo

Filtro de Placar: Empate (0x0) ⚠️ OBRIGATÓRIO!
```

---

## 🎯 PASSO 3: Condições

### ⚠️ ATENÇÃO: Condições INVERSAS!

Este bot usa **MÁXIMO** em vez de MÍNIMO.
Queremos jogo **TRAVADO**, não ofensivo!

### CONDIÇÕES AO VIVO (4 condições - MÁXIMOS)

#### ⚔️ Ataques
```
Ataques Perigosos Totais
├─ Aplicado a: Ambos Somados
└─ MÁXIMO: 3  (jogo travado!)
```

#### 🎯 Chutes
```
Chutes no Gol
├─ Aplicado a: Ambos Somados
└─ MÁXIMO: 1  (sem finalizações!)

Total de Chutes
├─ Aplicado a: Ambos Somados
└─ MÁXIMO: 3  (pouca movimentação!)
```

#### 📊 Pressão
```
Barra de Pressão
├─ Aplicado a: Ambos Times
└─ MÁXIMO: 50%  (nenhum dominando!)
```

---

### CONDIÇÕES PRÉ-JOGO (2 condições)

#### ⚽ Médias H2H - Gols
```
Média de Gols (1T)
├─ Aplicado a: Ambos Somados
└─ MÁXIMO: 0.6  (histórico sem gols!)
```

#### 🔮 Prognósticos
```
Prognóstico Under 0.5 (1T)
└─ MÍNIMO: 55  (probabilidade alta de não sair gol)

Prognóstico Ambas Marcam (Não) [OPCIONAL]
└─ MÍNIMO: 50
```

---

## 📋 CHECKLIST DE ENTRADA

Antes de entrar, verifique:

### ✅ Essenciais - CRÍTICO!
- [ ] Minuto entre 10 e 35
- [ ] Odd ≥ 1.5
- [ ] Jogo empatado 0x0 (SEM GOLS!)
  - ⚠️ Se já tem gol, NÃO ENTRE!

### ✅ Condições (TODAS - máximos!)
- [ ] 3 ou MENOS ataques perigosos somados
- [ ] 1 ou MENOS chute no gol somado
- [ ] 3 ou MENOS chutes totais somados
- [ ] 50% ou MENOS barra pressão (ambos)
- [ ] 0.6 ou MENOS média gols 1T (histórico)
- [ ] 55%+ prognóstico Under 0.5 1T

---

## 🔄 DIFERENÇA: COM GOL vs SEM GOL

| Item | Bot COM Gol | Bot SEM Gol |
|------|-------------|-------------|
| **Mercado** | Over 0.5 1T | Under 0.5 1T |
| **Tipo** | MÍNIMO | MÁXIMO |
| **Ataques Perig.** | Min 4+ | Máx 3 |
| **Chutes Gol** | Min 1+ | Máx 1 |
| **Barra Press.** | Min 55%+ | Máx 50% |
| **Objetivo** | OFENSIVO | TRAVADO |

---

## 💡 CENÁRIOS IDEAIS

### 🟢 PERFEITO para Under (SEM gol)
```
✅ Times defensivos
   → Atlético-MG, Getafe, Burnley

✅ Clássicos equilibrados
   → Times se estudam no 1T

✅ Jogos decisivos
   → Finais, mata-mata (medo de perder)

✅ Más condições
   → Chuva, frio (dificulta ataque)
```

### 🔴 EVITAR (Perigoso)
```
❌ Times ofensivos
   → Man City, PSG, Bayern

❌ Ligas ofensivas
   → Eredivisie, Bundesliga

❌ Times precisando vencer
   → Últimas rodadas, brigando contra rebaixamento

❌ Jogo já com gol
   → Placar diferente de 0x0
```

---

## 🏆 LIGAS RECOMENDADAS

### ✅ Excelentes (Defensivas)
- 🇮🇹 Serie A (Itália) ⭐⭐⭐
- 🇫🇷 Ligue 1 (França) ⭐⭐
- 🏆 Libertadores ⭐⭐
- 🇦🇷 Argentina ⭐⭐

### ❌ Evitar (Ofensivas)
- 🇳🇱 Eredivisie (Holanda)
- 🇩🇪 Bundesliga (Alemanha)
- 🏴󠁧󠁢󠁥󠁮󠁧󠁿 Championship (Inglaterra 2ª)

---

## 💰 GESTÃO DE BANCA

```
Conservador: 1% da banca
Moderado:    2% da banca
Agressivo:   3% da banca (máximo 5%)
```

---

## 🎯 EXEMPLO PRÁTICO

**Jogo:** Getafe x Athletic Bilbao  
**Minuto:** 22  
**Placar:** 0x0 ✅  
**Odd Under 0.5 1T:** 1.75 ✅  

**Ao Vivo:**
- Ataques Perigosos: 1 ✅ (máx 3)
- Chutes no Gol: 0 ✅ (máx 1)
- Chutes Totais: 1 ✅ (máx 3)
- Barra Pressão: 42% / 38% ✅ (máx 50%)

**Pré-Jogo:**
- Média Gols 1T: 0.3 ✅ (máx 0.6)
- Under 0.5 1T: 68% ✅ (mín 55%)

**Contexto:**
- Getafe = time MUITO defensivo
- Jogo travado, sem chances
- La Liga = liga tática

**DECISÃO:** ✅ ENTRAR COM CONFIANÇA!

---

## ⚠️ REGRAS CRÍTICAS

### 1️⃣ Placar = 0x0 (OBRIGATÓRIO!)
Se já saiu gol, **PERDEU** a aposta Under!

### 2️⃣ Use MÁXIMO, não MÍNIMO
Quer valores BAIXOS, não ALTOS!

### 3️⃣ Jogo deve estar TRAVADO
Poucas chances, pouca movimentação!

### 4️⃣ Prognóstico Under 55%+
Probabilidade deve estar A FAVOR!

---

## 🔄 OS 3 BOTS DISPONÍVEIS

```
1. COM Gol 1T (Over 0.5 1T)
   └─ Min 10-35, busca jogos OFENSIVOS

2. SEM Gol 1T (Under 0.5 1T)  ← ESTE!
   └─ Min 10-35, busca jogos TRAVADOS

3. COM Gol 2T (Over 0.5 2T)
   └─ Min 50-80, segundo tempo
```

⚠️ **ESCOLHA:** No 1T, use Over OU Under, NUNCA ambos!

---

## 💡 DICA FINAL

**Este bot é para jogos DEFENSIVOS!**

Se você gosta de jogos movimentados, use o bot "COM Gol".
Se você gosta de jogos táticos/travados, use este bot "SEM Gol".

**Paciência é fundamental! Espere o jogo PERFEITO!** 🎯✨
