# 🤖 SokkerPro - 12 Bots de Alta Odds

Coleção de 12 bots especializados para diferentes mercados de apostas esportivas, desenvolvidos com base no guia completo **sokkerprobots.pdf**. Cada bot foi cuidadosamente projetado para identificar oportunidades com **odds altas** e **critérios rigorosos**.

---

## 📋 Índice

1. [Bot 01 - Over 0.5 Gols 1T - Alta Pressão](#bot-01)
2. [Bot 02 - Over 1.5 Escanteios 1T - Times Ofensivos](#bot-02)
3. [Bot 03 - Under 0.5 Gols 1T - Favoritos Defensivos](#bot-03)
4. [Bot 04 - Over 0.5 Gols Asiático 1T](#bot-04)
5. [Bot 05 - Over Escanteios Asiático](#bot-05)
6. [Bot 06 - Sem Mais Gols 1T - Jogos Travados](#bot-06)
7. [Bot 07 - Over Total Escanteios - Times Agressivos](#bot-07)
8. [Bot 08 - Ambas Marcam (BTTS)](#bot-08)
9. [Bot 09 - Vitória Casa - Favoritos Dominantes](#bot-09)
10. [Bot 10 - Over 0.5 Gols 1T - Pressão Visitante](#bot-10)
11. [Bot 11 - Under Escanteios Asiático](#bot-11)
12. [Bot 12 - Over 1.5 Gols 1T - Times Goleadores](#bot-12)

---

## 🎯 Bot 01 - Over 0.5 Gols 1T - Alta Pressão

**Arquivo:** `bot01_over05_goals_1t_high_pressure.json`

### Mercado
- **Tipo:** Mais um gol até o fim do primeiro tempo (Over 0.5 Gols 1T)
- **Odds Alvo:** 1.65 a 2.50

### Estratégia
Identifica jogos 0x0 onde um time está pressionando intensamente com muitos ataques perigosos, finalizações e escanteios.

### Critérios Principais
- ✅ Mínimo 8 ataques perigosos
- ✅ Pelo menos 2 chutes no gol
- ✅ 3+ escanteios
- ✅ Barra de pressão acima de 75%
- ✅ Entrada: minutos 8-38 do 1T

### Análise
- **Winrate Estimado:** 60-65%
- **ROI Estimado:** 15-20%
- **Risco:** Médio

---

## 🎯 Bot 02 - Over 1.5 Escanteios 1T - Times Ofensivos

**Arquivo:** `bot02_over15_corners_1t_attacking.json`

### Mercado
- **Tipo:** Mais um escanteio até o fim do primeiro tempo (Over 1.5 Corners 1T)
- **Odds Alvo:** 1.55 a 2.00

### Estratégia
Busca jogos onde times pressionam pelas laterais. Entra quando já há 1 escanteio e padrão ofensivo está estabelecido.

### Critérios Principais
- ✅ Já tem 1 escanteio (precisa mais 1 para over 1.5)
- ✅ Mínimo 35 ataques totais somados
- ✅ 12+ ataques perigosos somados
- ✅ Média histórica de 3.5+ escanteios no 1T
- ✅ Entrada: minutos 10-40 do 1T

### Análise
- **Winrate Estimado:** 65-70%
- **ROI Estimado:** 18-25%
- **Risco:** Médio-Baixo

---

## 🎯 Bot 03 - Under 0.5 Gols 1T - Favoritos Defensivos

**Arquivo:** `bot03_under05_goals_1t_defensive.json`

### Mercado
- **Tipo:** Sem mais gols até o fim do primeiro tempo
- **Odds Alvo:** 1.50 a 2.00

### Estratégia
Entrada tardia (min 25-43) quando favorito vence por 1 gol e controla o jogo defensivamente.

### Critérios Principais
- ✅ Favorito vencendo por 1 gol de diferença
- ✅ Baixa frequência de ataques perigosos recentes
- ✅ Favorito com 55%+ de posse
- ✅ Zebra com baixa pressão (máx 40%)
- ✅ Entrada: minutos 25-43 do 1T

### Análise
- **Winrate Estimado:** 70-75%
- **ROI Estimado:** 20-28%
- **Risco:** Baixo

---

## 🎯 Bot 04 - Over 0.5 Gols Asiático 1T

**Arquivo:** `bot04_over05_asian_goals_1t.json`

### Mercado
- **Tipo:** Mais um gol asiático no primeiro tempo
- **Proteção:** Se sair exatamente 1 gol, devolve aposta
- **Odds Alvo:** 1.70 a 2.30

### Estratégia
Mercado asiático para reduzir risco. Busca jogos equilibrados com ambos times atacando.

### Critérios Principais
- ✅ 12+ ataques perigosos somados
- ✅ 3+ chutes no gol somados
- ✅ Jogo equilibrado (posse 45-55% cada)
- ✅ Ambos times com histórico de gols no 1T
- ✅ Entrada: minutos 5-35 do 1T

### Análise
- **Winrate Estimado:** 55-60% vitória + 15-20% devolução = 70-80% não perde
- **ROI Estimado:** 12-18%
- **Risco:** Baixo (proteção asiática)

---

## 🎯 Bot 05 - Over Escanteios Asiático

**Arquivo:** `bot05_over_asian_corners.json`

### Mercado
- **Tipo:** Over Escanteios Asiático
- **Proteção:** Se der exatamente 8, devolve; 9+, vitória
- **Odds Alvo:** 1.60 a 2.10

### Estratégia
Jogos com histórico muito forte de escanteios. Proteção asiática reduz risco.

### Critérios Principais
- ✅ Mínimo 2 escanteios já ocorridos
- ✅ 18+ ataques perigosos somados
- ✅ Média histórica de 10.5+ escanteios no jogo completo
- ✅ 3+ chutes bloqueados
- ✅ Entrada: minutos 15-42 do 1T

### Análise
- **Winrate Estimado:** 60-65% + 10-15% devolução
- **ROI Estimado:** 15-22%
- **Risco:** Baixo

---

## 🎯 Bot 06 - Sem Mais Gols 1T - Jogos Travados

**Arquivo:** `bot06_no_more_goals_1t.json`

### Mercado
- **Tipo:** Sem mais gols até o fim do primeiro tempo
- **Odds Alvo:** 1.55 a 2.20

### Estratégia
Jogos 0x0 muito defensivos ou travados. Entrada tardia (min 20-44).

### Critérios Principais
- ✅ Placar 0x0
- ✅ Baixíssima intensidade ofensiva recente
- ✅ Máximo 2 chutes no gol somados
- ✅ Jogo truncado com muitas faltas
- ✅ Entrada: minutos 20-44 do 1T

### Análise
- **Winrate Estimado:** 65-70%
- **ROI Estimado:** 18-25%
- **Risco:** Médio

---

## 🎯 Bot 07 - Over Total Escanteios - Times Agressivos

**Arquivo:** `bot07_over_total_corners.json`

### Mercado
- **Tipo:** Over 9.5 ou 10.5 Escanteios no Jogo Completo
- **Odds Alvo:** 1.70 a 2.50

### Estratégia
Confrontos entre times extremamente ofensivos com histórico excepcional de escanteios.

### Critérios Principais
- ✅ Mínimo 4 escanteios nos primeiros 20 minutos
- ✅ 25+ ataques perigosos somados
- ✅ Média histórica de 11+ escanteios no jogo
- ✅ Calcular projeção: (escanteios/minuto) x 90
- ✅ Entrada: minutos 12-75

### Análise
- **Winrate Estimado:** 55-60%
- **ROI Estimado:** 20-30%
- **Risco:** Médio
- **Nota:** Um dos mercados com maiores odds

---

## 🎯 Bot 08 - Ambas Marcam (BTTS)

**Arquivo:** `bot08_both_teams_score.json`

### Mercado
- **Tipo:** Both Teams To Score (BTTS) - Sim
- **Odds Alvo:** 1.65 a 2.30

### Estratégia
Jogos abertos onde AMBOS times estão finalizando e criando chances reais.

### Critérios Principais
- ✅ Cada time com mínimo 5 ataques perigosos
- ✅ Cada time com 2+ chutes no gol
- ✅ Cada time com 2+ escanteios
- ✅ Ambos goleiros trabalhando (1+ defesa cada)
- ✅ Entrada: minutos 5-70

### Análise
- **Winrate Estimado:** 60-65%
- **ROI Estimado:** 18-25%
- **Risco:** Médio
- **Melhor em:** Jogos 1x0 onde perdedor está pressionando

---

## 🎯 Bot 09 - Vitória Casa - Favoritos Dominantes

**Arquivo:** `bot09_home_win_favorites.json`

### Mercado
- **Tipo:** Resultado Final - 1 (Home Win)
- **Odds Alvo:** 2.00 a 4.00

### Estratégia
Captura odds altas quando favorito forte está empatado ou perdendo mas dominando totalmente.

### Critérios Principais
- ✅ Prognóstico casa vence: 70%+
- ✅ Casa com 15+ ataques perigosos
- ✅ Casa com 5+ chutes no gol
- ✅ Barra de pressão casa: 80%+
- ✅ Posse de bola casa: 60%+
- ✅ Entrada: qualquer momento do jogo

### Análise
- **Winrate Estimado:** 50-55%
- **ROI Estimado:** 25-35%
- **Risco:** Médio-Alto
- **Nota:** Odds muito altas compensam winrate menor

---

## 🎯 Bot 10 - Over 0.5 Gols 1T - Pressão Visitante

**Arquivo:** `bot10_over05_goals_1t_away_pressure.json`

### Mercado
- **Tipo:** Over 0.5 Gols no 1T - Foco Visitante
- **Odds Alvo:** 1.70 a 2.40

### Estratégia
Times visitantes fortes dominando no 1T. Mercado subestima visitantes, gerando odds melhores.

### Critérios Principais
- ✅ Visitante com 10+ ataques perigosos
- ✅ Visitante com 3+ chutes no gol
- ✅ Visitante com mais escanteios que casa
- ✅ Barra de pressão visitante: 70%+
- ✅ Entrada: minutos 10-40 do 1T

### Análise
- **Winrate Estimado:** 58-63%
- **ROI Estimado:** 20-28%
- **Risco:** Médio
- **Vantagem:** Visitantes fortes são subestimados

---

## 🎯 Bot 11 - Under Escanteios Asiático

**Arquivo:** `bot11_under_asian_corners.json`

### Mercado
- **Tipo:** Under Escanteios Asiático no 1T
- **Proteção:** Se sair exatamente mais 1, devolve
- **Odds Alvo:** 1.60 a 2.20

### Estratégia
Jogos controlados com pouquíssimos escanteios. Entrada tardia no 1T.

### Critérios Principais
- ✅ Máximo 2 escanteios até o momento
- ✅ Baixa intensidade ofensiva
- ✅ Média histórica de máx 3.5 escanteios no 1T
- ✅ Jogo controlado (75%+ passes certos)
- ✅ Entrada: minutos 20-44 do 1T

### Análise
- **Winrate Estimado:** 65-70% + 10% devolução
- **ROI Estimado:** 18-25%
- **Risco:** Baixo
- **Nota:** Mercado pouco explorado

---

## 🎯 Bot 12 - Over 1.5 Gols 1T - Times Goleadores

**Arquivo:** `bot12_over15_goals_1t_high_scoring.json`

### Mercado
- **Tipo:** Over 1.5 Gols no 1T
- **Odds Alvo:** 2.50 a 5.00

### Estratégia
⚠️ **Bot Agressivo** - Alto risco, alta recompensa. Apenas para jogos com TODAS condições atendidas.

### Critérios Principais
- ✅ 15+ ataques perigosos somados
- ✅ 5+ chutes no gol somados
- ✅ Média histórica de 1.8+ gols no 1T
- ✅ Intensidade ofensiva extrema (2.0+ ataques perigosos/min)
- ✅ Entrada: minutos 1-35 do 1T

### Análise
- **Winrate Estimado:** 40-45%
- **ROI Estimado:** 30-50%
- **Risco:** Alto
- **Nota:** Odds excepcionais (3.00-6.00) compensam winrate menor
- **Perfil:** Clássicos, derbies, confrontos diretos

---

## 📊 Resumo Comparativo

| Bot | Mercado | Odds Alvo | Winrate | ROI | Risco |
|-----|---------|-----------|---------|-----|-------|
| 01 | Over 0.5 Gols 1T | 1.65-2.50 | 60-65% | 15-20% | Médio |
| 02 | Over 1.5 Corners 1T | 1.55-2.00 | 65-70% | 18-25% | Médio-Baixo |
| 03 | Under 0.5 Gols 1T | 1.50-2.00 | 70-75% | 20-28% | Baixo |
| 04 | Over 0.5 Asiático 1T | 1.70-2.30 | 70-80%* | 12-18% | Baixo |
| 05 | Over Corners Asiático | 1.60-2.10 | 70-80%* | 15-22% | Baixo |
| 06 | No More Goals 1T | 1.55-2.20 | 65-70% | 18-25% | Médio |
| 07 | Over Total Corners | 1.70-2.50 | 55-60% | 20-30% | Médio |
| 08 | BTTS | 1.65-2.30 | 60-65% | 18-25% | Médio |
| 09 | Home Win | 2.00-4.00 | 50-55% | 25-35% | Médio-Alto |
| 10 | Over 0.5 1T Visitante | 1.70-2.40 | 58-63% | 20-28% | Médio |
| 11 | Under Corners Asiático | 1.60-2.20 | 75-80%* | 18-25% | Baixo |
| 12 | Over 1.5 Gols 1T | 2.50-5.00 | 40-45% | 30-50% | Alto |

*Inclui % de devolução do mercado asiático

---

## 💡 Recomendações de Uso

### Bots Conservadores (Iniciantes)
- **Bot 03** - Under 0.5 Gols 1T (70-75% winrate)
- **Bot 04** - Over Asiático (proteção)
- **Bot 05** - Corners Asiático (proteção)
- **Bot 11** - Under Corners Asiático

### Bots Intermediários
- **Bot 01** - Over 0.5 Gols Alta Pressão
- **Bot 02** - Over 1.5 Corners
- **Bot 06** - No More Goals
- **Bot 08** - BTTS

### Bots Avançados (Valor)
- **Bot 07** - Over Total Corners (odds altas)
- **Bot 09** - Home Win (odds muito altas)
- **Bot 10** - Visitante Pressão
- **Bot 12** - Over 1.5 Gols 1T (agressivo)

---

## 🔧 Como Usar

1. **Selecione o Bot** adequado ao tipo de jogo que está analisando
2. **Verifique TODOS os critérios** do Passo 3 (Condições)
3. **Confirme as condições pré-jogo** (médias H2H e prognósticos)
4. **Entre apenas dentro da faixa de minutos** especificada
5. **Respeite a odd mínima** estabelecida
6. **Use gestão de banca** recomendada (2-5% por entrada)

---

## ⚠️ Avisos Importantes

1. ✅ **Siga TODOS os critérios** - Não basta atender alguns
2. ✅ **Respeite os minutos de entrada** - Timing é crucial
3. ✅ **Gestão de banca** - Nunca aposte mais que 5% em uma entrada
4. ✅ **ROI é a longo prazo** - Não julgue por 5-10 entradas
5. ⚠️ **Bots de alto risco** (09, 12) exigem critérios ainda mais rigorosos
6. ⚠️ **Mercados asiáticos** oferecem proteção mas odds menores

---

## 📈 Análise de Mercados por Odds Potenciais

### Odds Altíssimas (2.50+)
- 🥇 **Bot 12** - Over 1.5 Gols 1T (3.00-6.00)
- 🥈 **Bot 09** - Home Win (2.50-4.50)
- 🥉 **Bot 07** - Over Total Corners (2.00-3.00)

### Odds Altas (2.00-2.50)
- **Bot 10** - Visitante Pressão (1.85-2.50)
- **Bot 01** - Alta Pressão (1.70-2.20)
- **Bot 06** - No More Goals (1.80-2.50)

### Odds Médias-Altas (1.60-2.00)
- **Bot 02** - Corners 1T (1.70-2.20)
- **Bot 04** - Asiático Gols (1.85-2.40)
- **Bot 08** - BTTS (1.80-2.50)

### Odds Seguras com Proteção (1.50-2.20)
- **Bot 03** - Under Defensivo (1.70-2.30)
- **Bot 05** - Corners Asiático (1.75-2.20)
- **Bot 11** - Under Corners Asiático (1.75-2.40)

---

## 🎓 Estrutura dos Arquivos JSON

Cada bot contém:
- ✅ **Passo 1:** Informações Básicas (mercado, tipo, objetivo)
- ✅ **Passo 2:** Configuração Essencial (minutos, odds, placar)
- ✅ **Passo 3:** Condições AO VIVO (ataques, chutes, escanteios, etc.)
- ✅ **Passo 3:** Condições PRÉ-JOGO (médias H2H, prognósticos)
- ✅ **Critérios de Entrada:** Momento ideal, odds, gestão
- ✅ **Análise de Mercado:** Potencial, risco, winrate, ROI

---

## 📚 Base de Conhecimento

Todos os bots foram criados seguindo rigorosamente as diretrizes do **sokkerprobots.pdf**, que documenta:

- Mercados de Gols e Escanteios
- Configuração de faixas de minutos
- Filtros de placar
- Condições AO VIVO (ataques, chutes, posse, defesa, disciplina)
- Condições PRÉ-JOGO (médias H2H)
- Prognósticos SokkerPRO

---

## 🚀 Começando

Para começar a usar os bots:

1. Escolha um bot adequado ao seu perfil de risco
2. Leia completamente o arquivo JSON do bot
3. Estude as condições e critérios
4. Configure no SokkerPRO seguindo os parâmetros
5. Teste com valores pequenos inicialmente
6. Acompanhe resultados e ajuste conforme necessário

---

## 📞 Suporte

Para dúvidas sobre critérios específicos, consulte o **sokkerprobots.pdf** que contém explicações detalhadas de cada estatística e condição.

---

**Desenvolvido com análise minuciosa para maximizar odds e ROI** 🎯
