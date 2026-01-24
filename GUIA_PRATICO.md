# 📖 Guia Prático de Uso dos Bots SokkerPro

## Como Interpretar e Usar os Bots

Este guia mostra **exemplos práticos** de como usar cada bot na plataforma SokkerPRO.

---

## 🔧 Configuração Inicial na Plataforma

### Passo 1: Acessar SokkerPRO
1. Vá para https://go.sokkerpro.com
2. Faça login na sua conta
3. Navegue até "Criar Novo Bot"

### Passo 2: Escolher o Bot
1. Escolha um dos 12 bots baseado no seu perfil
2. Abra o arquivo JSON correspondente
3. Use as informações para configurar

### Passo 3: Configuração no Sistema
Preencha os campos do SokkerPRO com os dados do JSON:

---

## 📝 Exemplo Prático 1: Bot 01 - Over 0.5 Gols 1T

### Situação Real
Você está assistindo um jogo ao vivo:
- **Arsenal (casa) vs Brighton (fora)**
- **Minuto:** 15
- **Placar:** 0x0
- **Estatísticas ao vivo:**
  - Arsenal: 12 ataques perigosos, 4 chutes no gol, 4 escanteios
  - Brighton: 5 ataques perigosos, 1 chute no gol, 1 escanteio
  - Barra de pressão Arsenal: 82%

### Verificar Condições PRÉ-JOGO
Consultando histórico (últimos 5 jogos):
- ✅ Arsenal em casa: média 1.2 gols no 1T
- ✅ Média chutes ao gol 1T: 3.5
- ✅ Prognóstico Over 0.5 1T: 58%

### Verificar Condições AO VIVO
- ✅ Ataques perigosos Arsenal: 12 (mín: 8) ✓
- ✅ Chutes no gol Arsenal: 4 (mín: 2) ✓
- ✅ Escanteios Arsenal: 4 (mín: 3) ✓
- ✅ Barra de pressão: 82% (mín: 75%) ✓
- ✅ Minuto: 15 (faixa: 8-38) ✓

### Verificar Odd
- **Odd atual:** 1.85 (mín: 1.65) ✓

### ✅ ENTRADA CONFIRMADA
- **Bot:** 01
- **Mercado:** Over 0.5 Gols 1T
- **Odd:** 1.85
- **Valor:** 50 (3% da banca de 1.667)
- **Retorno potencial:** 92.50

---

## 📝 Exemplo Prático 2: Bot 03 - Under 0.5 Gols 1T

### Situação Real
- **Manchester City (casa) vs Sheffield (fora)**
- **Minuto:** 32
- **Placar:** 1x0 (City vencendo)
- **Estatísticas ao vivo:**
  - City: 60% posse, 2 ataques perigosos nos últimos 5 min
  - Sheffield: 25% pressão, 0 chutes no gol nos últimos 3 min
  - City fazendo toques sem arriscar

### Verificar Condições PRÉ-JOGO
- ✅ City prognóstico vitória: 78% (favorito forte)
- ✅ Média gols 1T: 0.8 (histórico baixo)

### Verificar Condições AO VIVO
- ✅ Favorito vencendo por 1 gol ✓
- ✅ Minuto: 32 (faixa: 25-43) ✓
- ✅ Ataques perigosos 5min: 0.4 (máx: 0.7) ✓
- ✅ Posse favorito: 60% (mín: 55%) ✓
- ✅ Pressão zebra: 25% (máx: 40%) ✓
- ✅ Sheffield com 10 faltas (frustração) ✓

### Verificar Odd
- **Odd atual:** 1.75 (mín: 1.50) ✓

### ✅ ENTRADA CONFIRMADA
- **Bot:** 03
- **Mercado:** Sem Mais Gols até fim 1T
- **Odd:** 1.75
- **Valor:** 100 (5% da banca - baixo risco)
- **Retorno potencial:** 175

---

## 📝 Exemplo Prático 3: Bot 08 - Ambas Marcam

### Situação Real
- **Liverpool (casa) vs Chelsea (fora)**
- **Minuto:** 25
- **Placar:** 1x0 (Liverpool)
- **Estatísticas ao vivo:**
  - Liverpool: 7 ataques perigosos, 3 chutes no gol, 3 escanteios
  - Chelsea: 9 ataques perigosos, 4 chutes no gol, 4 escanteios
  - Jogo aberto e equilibrado

### Verificar Condições PRÉ-JOGO
- ✅ Liverpool média gols em casa: 1.8
- ✅ Chelsea média gols fora: 1.4
- ✅ Prognóstico BTTS: 65%
- ✅ Ambos finalizam bem

### Verificar Condições AO VIVO (AMBOS)
**Liverpool:**
- ✅ Ataques perigosos: 7 (mín: 5) ✓
- ✅ Chutes no gol: 3 (mín: 2) ✓
- ✅ Escanteios: 3 (mín: 2) ✓

**Chelsea:**
- ✅ Ataques perigosos: 9 (mín: 5) ✓
- ✅ Chutes no gol: 4 (mín: 2) ✓
- ✅ Escanteios: 4 (mín: 2) ✓

**Equilíbrio:**
- ✅ Posse: Liverpool 52%, Chelsea 48% ✓

### Verificar Odd
- **Odd atual:** 2.10 (mín: 1.65) ✓

### ✅ ENTRADA CONFIRMADA
- **Bot:** 08
- **Mercado:** Ambas Marcam - Sim
- **Odd:** 2.10
- **Valor:** 60 (3% da banca)
- **Retorno potencial:** 126
- **Lógica:** Chelsea perdendo mas atacando muito, alta chance de empatar ou fazer o segundo

---

## 📝 Exemplo Prático 4: Bot 12 - Over 1.5 Gols 1T (Agressivo)

### Situação Real
- **Bayern (casa) vs Dortmund (fora)** - CLÁSSICO ALEMÃO
- **Minuto:** 12
- **Placar:** 0x0
- **Estatísticas ao vivo:**
  - Ataques perigosos somados: 18
  - Chutes no gol somados: 6
  - Escanteios somados: 5
  - Intensidade altíssima

### Verificar Condições PRÉ-JOGO
- ✅ Bayern média gols 1T em casa: 1.4
- ✅ Dortmund média gols 1T fora: 1.0
- ✅ Média somada 1T: 2.2 (mín: 1.8) ✓
- ✅ Prognóstico Over 1.5 1T: 42% (mín: 35%) ✓
- ✅ Clássico ofensivo histórico

### Verificar Condições AO VIVO
- ✅ Ataques perigosos: 18 (mín: 15) ✓
- ✅ Chutes no gol: 6 (mín: 5) ✓
- ✅ Escanteios: 5 (mín: 4) ✓
- ✅ Ataques perigosos/min: 1.5 (mín: 2.0) ✗

### ❌ NÃO ENTRAR
Não atende TODOS os critérios. Bot 12 é agressivo e requer TODAS condições.

**Decisão:** Aguardar mais 5 minutos para ver se intensidade aumenta ou usar outro bot.

---

## 📝 Exemplo Prático 5: Bot 02 - Over 1.5 Escanteios 1T

### Situação Real
- **Atalanta (casa) vs Inter (fora)**
- **Minuto:** 18
- **Placar:** 0x0
- **Estatísticas ao vivo:**
  - Escanteios: Atalanta 1, Inter 0 (total: 1)
  - Ataques totais somados: 42
  - Ataques perigosos somados: 14
  - Chutes bloqueados somados: 3

### Verificar Condições PRÉ-JOGO
- ✅ Média escanteios 1T somada: 4.2 (mín: 3.5) ✓
- ✅ Média ataques 1T: 38 (mín: 35) ✓
- ✅ Times ofensivos

### Verificar Condições AO VIVO
- ✅ Escanteios atual: 1 (já tem 1, precisa +1) ✓
- ✅ Ataques totais: 42 (mín: 35) ✓
- ✅ Ataques perigosos: 14 (mín: 12) ✓
- ✅ Chutes bloqueados: 3 (mín: 2) ✓
- ✅ Minuto: 18 (faixa: 10-40) ✓

### Verificar Odd
- **Odd atual:** 1.72 (mín: 1.55) ✓

### ✅ ENTRADA CONFIRMADA
- **Bot:** 02
- **Mercado:** Over 1.5 Escanteios 1T
- **Odd:** 1.72
- **Valor:** 75 (4% da banca)
- **Retorno potencial:** 129

---

## 🎯 Fluxo de Decisão Rápido

```
1. Assistindo jogo ao vivo
   ↓
2. Identificar padrão (ataque intenso? defensivo? escanteios?)
   ↓
3. Escolher bot candidato
   ↓
4. Verificar minuto (está na faixa?)
   ↓
5. Verificar placar (filtro correto?)
   ↓
6. Verificar condições PRÉ-JOGO
   ↓
7. Verificar condições AO VIVO (TODAS)
   ↓
8. Verificar odd (acima do mínimo?)
   ↓
9. ENTRAR ou NÃO ENTRAR
```

---

## ⚠️ Situações de NÃO ENTRADA

### Exemplo 1: Faltam Condições
- Bot exige 8 ataques perigosos
- Time tem apenas 6
- ❌ **NÃO ENTRAR** - aguardar ou desistir

### Exemplo 2: Fora da Faixa de Minutos
- Bot opera entre min 10-40
- Jogo está no minuto 42
- ❌ **NÃO ENTRAR** - janela fechou

### Exemplo 3: Odd Abaixo do Mínimo
- Bot exige odd mín 1.65
- Odd atual: 1.58
- ❌ **NÃO ENTRAR** - sem valor

### Exemplo 4: Placar Incorreto
- Bot exige empate 0x0
- Jogo está 1x0
- ❌ **NÃO ENTRAR** - critério não atendido

---

## 💰 Gestão de Banca - Exemplos

### Banca: R$ 2.000

**Conservador (Bot 03):**
- Entrada: 5% = R$ 100
- Odd: 1.75
- Retorno: R$ 175
- Lucro: R$ 75

**Intermediário (Bot 01):**
- Entrada: 3% = R$ 60
- Odd: 1.85
- Retorno: R$ 111
- Lucro: R$ 51

**Agressivo (Bot 12):**
- Entrada: 2% = R$ 40
- Odd: 3.50
- Retorno: R$ 140
- Lucro: R$ 100

---

## 📊 Planilha de Controle (Sugestão)

Crie uma planilha com:

| Data | Jogo | Bot | Minuto | Odd | Valor | Resultado | Lucro/Prejuízo |
|------|------|-----|--------|-----|-------|-----------|----------------|
| 24/01 | Arsenal x Brighton | Bot 01 | 15 | 1.85 | 60 | Verde | +51 |
| 24/01 | City x Sheffield | Bot 03 | 32 | 1.75 | 100 | Verde | +75 |
| 24/01 | Liverpool x Chelsea | Bot 08 | 25 | 2.10 | 60 | Red | -60 |

---

## 🎓 Dicas Finais

1. ✅ **Use checklist mental:** Não pule nenhum critério
2. ✅ **Seja disciplinado:** Se falta 1 critério, NÃO ENTRE
3. ✅ **Gestão é fundamental:** Nunca mais de 5% em uma entrada
4. ✅ **Diversifique:** Use vários bots em vários jogos
5. ✅ **Analise resultados:** Após 50 entradas, veja qual bot funciona melhor para você
6. ⚠️ **Bots agressivos:** Use menos dinheiro (2-3%)
7. ⚠️ **Não force:** Se não tem jogo bom, não entre
8. ⚠️ **Evite tilt:** Se perder 3 seguidas, pare e revise

---

## 📱 Uso no Mobile

Os arquivos JSON podem ser consultados no celular:
1. Baixe os 12 arquivos JSON
2. Use app de leitura de JSON ou conversor para PDF
3. Tenha sempre à mão durante jogos ao vivo
4. Marque seus bots favoritos

---

**Boas apostas e que os bots tragam bons resultados! 🎯📊**
