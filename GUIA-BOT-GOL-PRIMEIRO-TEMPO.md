# Bot SokkerPRO - Gol no Primeiro Tempo

> **Seguindo o formato oficial do PDF SokkerPRO**

## 📋 Passo 1: Informações Básicas

**Mercado de Gols:**
- **Tipo:** Mais um gol até o fim do primeiro tempo
- **Linha:** Over 0.5 Gols (1T)
- **Como funciona:** Se o jogo está 0x0, precisa sair pelo menos 1 gol no primeiro tempo

**Nome do Bot:** `Gol 1T Conservador` ou `Over 0.5 - 1T`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
- **De:** 10
- **Até:** 35
- **Por quê?** Após o aquecimento inicial (0-10min) e com tempo suficiente antes do intervalo

### Odd Mínima de Entrada
- **Valor:** 1.5
- Se não configurar odd, o bot alertará em qualquer odd
- Com odd 1.5, só alertará quando o mercado estiver nesta cotação ou superior

### Valor de Entrada
- **Opções:** 0 (apenas alertas) ou defina um valor
- **0:** Apenas notificações, sem contabilizar lucro/prejuízo
- **[Seu valor]:** Contabiliza ROI, lucro e prejuízo automaticamente

### Filtro de Placar
- **Configuração:** Empate (0x0)
- **Motivo:** Jogos empatados tendem a abrir mais no primeiro tempo

### Gestão de Banca
- **Recomendado:** 1-2% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **Aplicação das condições:**  
> - **Casa:** Apenas ao time da casa  
> - **Visitante:** Apenas ao time visitante  
> - **Ambos Somados:** Soma total dos dois times  
> - **Qualquer Time:** Aplica a qualquer um dos times

#### Ataques
| Estatística | Aplicado a | Valor Mínimo | Motivo |
|-------------|------------|--------------|--------|
| Ataques Perigosos Totais | Ambos Somados | 6 | Indica que os times estão criando chances reais |
| Ataques Perigosos 3min | Qualquer Time | 1.5 | Momentum ofensivo crescente |
| Ataques Perigosos 5min | Qualquer Time | 1.0 | Consistência ofensiva |

#### Chutes
| Estatística | Aplicado a | Valor Mínimo | Motivo |
|-------------|------------|--------------|--------|
| Chutes no Gol | Ambos Somados | 2 | Pressão real sobre os goleiros |
| Chutes Dentro da Área | Qualquer Time | 2 | Maior probabilidade de gol |
| Total de Chutes | Ambos Somados | 4 | Jogo movimentado ofensivamente |

#### Outros Indicadores
- **Escanteios (Ambos Somados):** Mínimo 2
  - Cada escanteio aumenta ~2% a chance de gol
- **Barra de Pressão (Qualquer Time):** Mínimo 60%
  - Dominância clara aumenta chance de gol
- **Defesas do Goleiro (Qualquer Time):** Mínimo 1
  - Confirma finalização perigosa real

### 3️⃣ Condições PRÉ-JOGO (Históricas)

#### Médias H2H - Gols
- **Média Gols 1T (Ambos):** ≥ 1.0
  - Histórico dos últimos 5 jogos mostra tendência ofensiva no 1T

#### Médias H2H - Chutes
- **Média Chutes ao Gol 1T (Ambos):** ≥ 4
- **Média Chutes Dentro da Área 1T (Qualquer):** ≥ 2

#### Médias H2H - Ataques
- **Média Ataques Perigosos 1T (Ambos):** ≥ 8

#### Prognósticos SokkerPRO
- **Over 0.5 (1T):** ≥ 55%
  - Probabilidade mínima validada pelo algoritmo
- **Ambas Marcam (Opcional):** ≥ 45%
  - Se atendido, aumenta ainda mais a confiança

## 📊 Estratégia de Entrada

### Quando Entrar?
O bot deve alertar quando:
✅ **TODAS** as condições ao vivo críticas forem atendidas  
✅ **Pelo menos 70%** das condições pré-jogo forem atendidas  
✅ Odd ≥ 1.5  
✅ Minuto entre 10 e 35  
✅ Jogo empatado  

### Gestão de Banca
- **Recomendado:** 1-2% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

## 💡 Dicas e Cuidados

### ✅ Pontos Fortes
1. Faixa de tempo otimizada evita período de estudo inicial
2. Odd 1.5 oferece boa relação risco/retorno
3. Múltiplos filtros garantem entrada apenas em jogos ofensivos
4. Validação histórica e estatística dupla (ao vivo + pré-jogo)

### ⚠️ Cuidados
1. Evitar jogos muito travados mesmo que atendam critérios isolados
2. Preferir jogos equilibrados para maximizar probabilidade
3. Considerar importância do jogo (finais tendem a ser mais fechadas)
4. Atenção ao momento da temporada

### 🏆 Ligas Recomendadas
**Alto Desempenho:**
- Premier League (Inglaterra)
- La Liga (Espanha)
- Serie A (Itália)
- Bundesliga (Alemanha)
- Ligue 1 (França)

**Bom Desempenho:**
- Brasileirão
- Liga Portugal
- Eredivisie (Holanda)
- Championship (Inglaterra - 2ª divisão)

**Evitar:**
- Ligas muito defensivas
- Competições de baixo nível técnico
- Jogos entre times com média muito baixa de gols

## 📁 Como Usar no SokkerPRO

1. Abra o arquivo `bot-gol-primeiro-tempo.json`
2. Use os valores da seção `configuracao_essencial` no Passo 2
3. Configure as condições da seção `condicoes_ao_vivo` no Passo 3
4. Configure as condições da seção `condicoes_pre_jogo` no Passo 3
5. (Opcional) Filtre ligas conforme recomendações

## 📈 Resumo Rápido

```
MERCADO: Over 0.5 Gols (Primeiro Tempo)
FAIXA: Minuto 10 até 35
ODD MÍNIMA: 1.5
PLACAR: Empate (0x0)

CONDIÇÕES CRÍTICAS AO VIVO:
✓ 6+ ataques perigosos (somados)
✓ 2+ chutes no gol (somados)
✓ 2+ chutes na área (qualquer time)
✓ 60%+ barra de pressão (qualquer time)
✓ 1+ defesa goleiro (qualquer time)

CONDIÇÕES CRÍTICAS PRÉ-JOGO:
✓ 1+ média gols 1T
✓ 55%+ prognóstico Over 0.5 1T
✓ 8+ média ataques perigosos 1T
```

## 🎲 Exemplo Prático

**Jogo:** Manchester City x Arsenal  
**Minuto:** 18  
**Placar:** 0x0  
**Odd Over 0.5 1T:** 1.65  

**Ao Vivo:**
- Ataques Perigosos: 8 (4 City + 4 Arsenal) ✅
- Chutes no Gol: 3 (2 City + 1 Arsenal) ✅
- Chutes na Área: 3 (City) ✅
- Barra Pressão: 68% (City) ✅
- Defesas Goleiro: 2 (Arsenal) ✅

**Pré-Jogo:**
- Média Gols 1T: 1.4 ✅
- Over 0.5 1T: 67% ✅
- Média Ataques Perigosos 1T: 12 ✅

**DECISÃO:** ✅ ENTRAR - Todas condições atendidas!

---

## 📞 Suporte

Para dúvidas sobre a configuração ou ajustes finos baseados em seus resultados, consulte a documentação completa do SokkerPRO ou o PDF `sokkerprobots.pdf`.

**Boa sorte e boas apostas! 🍀⚽**
