# 🎯 Bot SokkerPRO - Gol no Segundo Tempo

## 📋 Descrição
Configuração otimizada de bot para o mercado **"Over 0.5 Gols no Segundo Tempo"** (sair pelo menos 1 gol no segundo tempo), focando em entradas entre os minutos 50 e 80 com odd mínima de 1.5.

## 🎯 Objetivo
Identificar jogos ao vivo onde há alta probabilidade de sair um gol no segundo tempo, aproveitando:
- A intensidade maior do segundo tempo (times buscando resultado)
- Cansaço defensivo e espaços que se abrem
- Urgência de times que precisam do gol
- Estatísticas ao vivo e histórico dos times

## ⚙️ Configuração Principal

### 1️⃣ Essencial
- **Mercado:** Over 0.5 Gols (2T) - Sair gol no segundo tempo
- **Faixa de Minutos:** 50 até 80
  - Por quê? Período de busca por resultado, antes da pressão/desespero final (80-90min)
- **Odd Mínima:** 1.5
- **Valor de Entrada:** 0 (apenas alertas) ou defina um valor para contabilizar lucro/prejuízo
- **Filtro de Placar:** Qualquer
  - Diferente do 1T! Times perdendo ou empatados atacam mais no 2T

### 2️⃣ Condições AO VIVO (Principais)

#### Ataques
| Estatística | Aplicado a | Valor Mínimo | Motivo |
|-------------|------------|--------------|--------|
| Ataques Perigosos Totais | Ambos Somados | 8 | Maior que 1T - continuidade ofensiva |
| Ataques Perigosos 3min | Qualquer Time | 1.8 | Intensidade crescente |
| Ataques Perigosos 5min | Qualquer Time | 1.2 | Pressão sustentada |
| Ataques Perigosos 10min | Qualquer Time | 2.0 | Time pressionando forte |

#### Chutes
| Estatística | Aplicado a | Valor Mínimo | Motivo |
|-------------|------------|--------------|--------|
| Chutes no Gol | Ambos Somados | 3 | Mais que 1T - maior urgência |
| Chutes Dentro da Área | Qualquer Time | 3 | Times mais ousados no 2T |
| Total de Chutes | Ambos Somados | 6 | Volume elevado |
| Tentativas de Gol | Qualquer Time | 4 | Agressividade ofensiva clara |

#### Outros Indicadores
- **Escanteios (Ambos Somados):** Mínimo 3
  - Pressão crescente no 2T
- **Barra de Pressão (Qualquer Time):** Mínimo 65%
  - Dominância mais clara no 2T
- **Defesas do Goleiro (Qualquer Time):** Mínimo 2
  - Múltiplas defesas = finalizações perigosas reais

### 3️⃣ Condições PRÉ-JOGO (Históricas)

#### Médias H2H - Gols
- **Média Gols Totais (Ambos):** ≥ 2.5
  - Jogos abertos tendem a ter gols no 2T
- **Média Gols 1T (Ambos):** ≥ 0.8
  - Se 1T teve gols, aumenta chance de 2T ter também

#### Médias H2H - Chutes
- **Média Chutes ao Gol (Ambos):** ≥ 8
- **Média Chutes Dentro da Área (Qualquer):** ≥ 4

#### Médias H2H - Ataques
- **Média Ataques Perigosos (Ambos):** ≥ 15

#### Prognósticos SokkerPRO
- **Over 1.5:** ≥ 60%
  - Se espera 2+ gols, haverá gols no 2T
- **Over 2.5:** ≥ 45%
  - Jogos com 3+ gols têm gols distribuídos
- **Ambas Marcam:** ≥ 50% (opcional)
  - Aumenta confiança se atendido

## 📊 Estratégia de Entrada

### Quando Entrar?
O bot deve alertar quando:
✅ **TODAS** as condições ao vivo críticas forem atendidas  
✅ **Pelo menos 70%** das condições pré-jogo forem atendidas  
✅ Odd ≥ 1.5  
✅ Minuto entre 50 e 80  
✅ Jogo mostrando sinais de continuidade ofensiva  

### Gestão de Banca
- **Recomendado:** 1-2% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

## 💡 Diferenças em Relação ao Bot de 1º Tempo

### 🔄 Principais Diferenças

| Aspecto | 1º Tempo | 2º Tempo |
|---------|----------|----------|
| **Faixa** | 10-35min | 50-80min |
| **Placar** | Empate | Qualquer |
| **Ataques Perigosos** | 6+ | 8+ |
| **Chutes no Gol** | 2+ | 3+ |
| **Barra Pressão** | 60%+ | 65%+ |
| **Defesas Goleiro** | 1+ | 2+ |
| **Média Gols (histórico)** | 1.0+ (1T) | 2.5+ (total) |

### 📈 Por quê valores mais altos?
1. Times buscam resultado com mais urgência no 2T
2. Espaços se abrem com cansaço defensivo
3. Substituições ofensivas criam mais oportunidades
4. Time perdendo pressiona muito mais

## 💡 Dicas e Cuidados

### ✅ Cenários Ideais
1. **Empate 0x0 ou 1x1** - Times buscando vitória
2. **Favorito perdendo por 1 gol** - Pressão máxima!
3. **Placar aberto (2x1, 2x2)** - Jogo dinâmico continua
4. **Jogo equilibrado** - Ambos atacando

### ⚠️ Evitar
1. **Goleadas** - 3+ gols de diferença (time vencedor gerencia)
2. **Após 75min** - Podem entrar em gestão/cansaço
3. **Times muito defensivos** - Mesmo perdendo, alguns não atacam
4. **Finais de campeonato** - Podem ser muito fechadas

### 🏆 Ligas Recomendadas
**Excelentes para 2º Tempo:**
- Brasileirão (segundo tempo tradicionalmente aberto)
- Eredivisie (Holanda - jogos ofensivos)
- Bundesliga (Alemanha)
- Championship (Inglaterra - 2ª divisão)
- Liga Portugal

**Boas:**
- Premier League
- La Liga
- Ligue 1

**Evitar:**
- Serie A (Itália - muito tática/defensiva)
- Ligas de baixo nível técnico

## 📁 Como Usar no SokkerPRO

1. Abra o arquivo `bot-gol-segundo-tempo.json`
2. Use os valores da seção `configuracao_essencial` no Passo 2
3. Configure as condições da seção `condicoes_ao_vivo` no Passo 3
4. Configure as condições da seção `condicoes_pre_jogo` no Passo 3
5. (Opcional) Filtre ligas conforme recomendações

## 📈 Resumo Rápido

```
MERCADO: Over 0.5 Gols (Segundo Tempo)
FAIXA: Minuto 50 até 80
ODD MÍNIMA: 1.5
PLACAR: Qualquer (preferir equilibrados)

CONDIÇÕES CRÍTICAS AO VIVO:
✓ 8+ ataques perigosos (somados)
✓ 3+ chutes no gol (somados)
✓ 3+ chutes na área (qualquer time)
✓ 6+ chutes totais (somados)
✓ 65%+ barra de pressão (qualquer time)
✓ 2+ defesas goleiro (qualquer time)
✓ 3+ escanteios (somados)

CONDIÇÕES CRÍTICAS PRÉ-JOGO:
✓ 2.5+ média gols totais
✓ 60%+ prognóstico Over 1.5
✓ 15+ média ataques perigosos
✓ 8+ média chutes ao gol
```

## 🎲 Exemplo Prático

**Jogo:** Fluminense x Botafogo  
**Minuto:** 65  
**Placar:** 1x1  
**Odd Over 0.5 2T:** 1.55 ✅  

**Ao Vivo:**
- Ataques Perigosos (jogo): 12 (6 Flu + 6 Bot) ✅
- Chutes no Gol (jogo): 5 (3 Flu + 2 Bot) ✅
- Chutes na Área (2T): 4 (Flu) ✅
- Total Chutes (2T): 8 ✅
- Barra Pressão: 70% (Flu) ✅
- Defesas Goleiro: 3 (Bot) ✅
- Escanteios (2T): 4 (3 Flu + 1 Bot) ✅

**Pré-Jogo:**
- Média Gols Totais: 2.8 ✅
- Over 1.5: 68% ✅
- Média Ataques Perigosos: 18 ✅
- Média Chutes ao Gol: 10 ✅

**Contexto:** Jogo equilibrado (1x1), ambos precisando da vitória, segundo tempo aberto com muitas chances!

**DECISÃO:** ✅ **ENTRAR!** Todas condições atendidas!

---

## 🔄 Combinação com Bot de 1º Tempo

Você pode usar **AMBOS** os bots:
- **Bot 1T:** Minutos 10-35
- **Bot 2T:** Minutos 50-80

Isso cobre praticamente todo o jogo, mas com critérios específicos para cada tempo!

⚠️ **Atenção:** Nunca entre duas vezes no mesmo jogo. Se entrou no 1T, não entre no 2T do mesmo jogo.

---

## 📞 Suporte

Para dúvidas sobre a configuração ou ajustes finos baseados em seus resultados, consulte a documentação completa do SokkerPRO ou o PDF `sokkerprobots.pdf`.

**Boa sorte e boas apostas! 🍀⚽**
