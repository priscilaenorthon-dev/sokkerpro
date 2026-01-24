# 🚫 Bot SokkerPRO - SEM Gol no Primeiro Tempo

## 📋 Passo 1: Informações Básicas

**Mercado de Gols:**
- **Tipo:** Sem mais gols até o fim do primeiro tempo
- **Linha:** Under 0.5 Gols (1T)
- **Como funciona:** Aposta ganha se o primeiro tempo terminar 0x0. Se sair qualquer gol no primeiro tempo, você perde.

**Nome do Bot:** `Sem Gol 1T` ou `Under 0.5 - 1T`

---

## ⚙️ Passo 2: Configuração Essencial

### Faixa de Minutos
**10 até 35**

**Por quê?**  
Confirmar que jogo está travado antes de entrar. Este período é suficiente para avaliar se ambos os times estão jogando de forma defensiva ou sem criar chances claras.

### Odd Mínima de Entrada
**1.5**

**Por quê?**  
Esta odd garante valor mínimo para suas entradas. O bot pode gerar APENAS alertas (sem entradas automáticas) ou fazer entradas automáticas, dependendo da configuração do valor de entrada.

### Valor de Entrada
- **0** = Apenas alertas (você decide manualmente se entra)
- **Valor definido** = Bot contabiliza lucro/prejuízo automaticamente

### Filtro de Placar
**Empate (0x0)**

**Por quê?**  
CRÍTICO: Se já saiu gol, já perdemos a aposta! O placar precisa estar obrigatoriamente em 0x0.

### Gestão de Banca
- **Recomendado:** 1-2% da banca por entrada
- **Máximo:** Nunca mais que 5% da banca
- **Tipo:** Valor fixo por entrada

---

## 🎯 Passo 3: Condições

### Condições AO VIVO

> **⚠️ ATENÇÃO:** Condições INVERSAS - Usamos MÁXIMO em vez de MÍNIMO!

> **Nota:** Estas condições se aplicam a **Casa/Visitante/Ambos Somados/Qualquer Time** conforme especificado em cada linha.

#### Ataques
| Estatística | Aplicado a | Valor MÁXIMO | Motivo |
|-------------|------------|--------------|--------|
| Ataques Perigosos Totais | Ambos Somados | 3 | Jogo travado, poucas chances |

#### Chutes
| Estatística | Aplicado a | Valor MÁXIMO | Motivo |
|-------------|------------|--------------|--------|
| Chutes no Gol | Ambos Somados | 1 | Sem finalizações perigosas |
| Total de Chutes | Ambos Somados | 3 | Pouca movimentação ofensiva |

#### Outros Indicadores
- **Barra de Pressão (Ambos Times):** MÁXIMO 50%
  - Nenhum time dominando - jogo equilibrado e fechado

### Condições PRÉ-JOGO

> **Nota H2H:** Médias baseadas nos confrontos diretos (Head to Head) entre os times.

#### Médias H2H - Gols
- **Média Gols 1T (Ambos):** MÁXIMO 0.6
  - Histórico de primeiros tempos sem gols

#### Prognósticos SokkerPRO
- **Under 0.5 (1T):** ≥ 55%
  - Probabilidade alta de não sair gol
- **Ambas Marcam Não:** ≥ 50% (opcional)
  - Reforça que pelo menos um time não marcará

---

## 📊 Estratégia de Entrada

### Quando Entrar?
O bot deve alertar quando:
✅ **TODAS** as condições ao vivo forem atendidas  
✅ **TODAS** as condições pré-jogo forem atendidas  
✅ Odd ≥ 1.5  
✅ Minuto entre 10 e 35  
✅ Jogo empatado 0x0 (SEM GOLS!)  

---

## 💡 Diferenças do Bot "COM Gol"

### 🔄 Comparação

| Aspecto | Bot COM Gol (Over) | Bot SEM Gol (Under) |
|---------|-------------------|---------------------|
| **Mercado** | Over 0.5 1T | Under 0.5 1T |
| **Tipo Condição** | MÍNIMO | MÁXIMO |
| **Ataques Perig.** | Mín. 4+ | Máx. 3 |
| **Chutes Gol** | Mín. 1+ | Máx. 1 |
| **Barra Press.** | Mín. 55%+ | Máx. 50% |
| **Objetivo** | Jogo OFENSIVO | Jogo TRAVADO |

### 📈 Lógica Inversa
- **Over:** Quer jogo MOVIMENTADO com MUITOS ataques
- **Under:** Quer jogo TRAVADO com POUCOS ataques

## 💡 Cenários Ideais

### ✅ ENTRAR (Perfeito para Under)
1. **Times muito defensivos**
   - Atlético-MG, Getafe, Burnley (conhecidos por serem fechados)
   
2. **Clássicos equilibrados**
   - Flamengo x Fluminense, Barcelona x Real Madrid (se estudam)
   
3. **Jogos decisivos**
   - Finais, mata-mata (times com medo de perder)
   
4. **Condições adversas**
   - Chuva forte, frio extremo (dificulta ataque)

### ⚠️ EVITAR (Perigoso para Under)
1. **Times muito ofensivos**
   - Manchester City, PSG, Bayern (sempre atacam)
   
2. **Ligas ofensivas**
   - Eredivisie, Bundesliga (muitos gols)
   
3. **Times precisando vencer**
   - Brigando contra rebaixamento no final do campeonato
   
4. **Jogos já com gol**
   - Se placar não é 0x0, já perdemos!

### 🏆 Ligas Recomendadas

**Excelentes para Under 1T:**
- 🇮🇹 **Serie A (Itália)** - Muito tática e defensiva
- 🇫🇷 **Ligue 1 (França)** - Jogos equilibrados
- 🏆 **Libertadores** - Times se estudam muito
- 🇦🇷 **Campeonato Argentino** - Jogo estudado

**Evitar:**
- 🇳🇱 Eredivisie (muitos gols)
- 🇩🇪 Bundesliga (ofensiva)
- 🏴󠁧󠁢󠁥󠁮󠁧󠁿 Championship (imprevisível)

## 📁 Como Usar no SokkerPRO

1. Abra o arquivo `bot-sem-gol-primeiro-tempo.json`
2. Use os valores da seção `configuracao_essencial` no Passo 2
3. Configure as condições da seção `condicoes_ao_vivo` no Passo 3
   - ⚠️ **ATENÇÃO:** Use MÁXIMO, não MÍNIMO!
4. Configure as condições da seção `condicoes_pre_jogo` no Passo 3
5. (Opcional) Filtre ligas conforme recomendações

## 📈 Resumo Rápido

```
MERCADO: Under 0.5 Gols (Primeiro Tempo) - SEM GOL
FAIXA: Minuto 10 até 35
ODD MÍNIMA: 1.5
PLACAR: Empate 0x0 (OBRIGATÓRIO!)

CONDIÇÕES AO VIVO (MÁXIMOS):
✓ MÁXIMO 3 ataques perigosos (somados)
✓ MÁXIMO 1 chute no gol (somado)
✓ MÁXIMO 3 chutes totais (somados)
✓ MÁXIMO 50% barra pressão (ambos)

CONDIÇÕES PRÉ-JOGO:
✓ MÁXIMO 0.6 média gols 1T
✓ MÍNIMO 55% prognóstico Under 0.5 1T
```

## 🎲 Exemplo Prático

**Jogo:** Atlético-MG x Fluminense  
**Minuto:** 25  
**Placar:** 0x0 ✅  
**Odd Under 0.5 1T:** 1.60 ✅  

**Ao Vivo:**
- Ataques Perigosos: 2 (1 Galo + 1 Flu) ✅ (máx 3)
- Chutes no Gol: 0 ✅ (máx 1)
- Chutes Totais: 2 ✅ (máx 3)
- Barra Pressão: 45% (Galo), 42% (Flu) ✅ (máx 50%)

**Pré-Jogo:**
- Média Gols 1T: 0.4 ✅ (máx 0.6)
- Under 0.5 1T: 62% ✅ (mín 55%)

**Contexto:** 
- Jogo clássico equilibrado
- Ambos times defensivos
- Primeiro tempo estudado, sem chances claras
- Histórico de jogos fechados

**DECISÃO:** ✅ **ENTRAR!** Todas condições atendidas!

---

## ⚠️ REGRAS CRÍTICAS

### 1. Placar DEVE ser 0x0
Se já saiu gol, **NÃO ENTRE!** A aposta já está perdida.

### 2. Use MÁXIMO, não MÍNIMO
Este bot é INVERSO - queremos valores BAIXOS, não altos.

### 3. Evite jogos ofensivos
Times conhecidos por atacar muito são perigosos.

### 4. Confira o prognóstico
Under 0.5 1T deve estar em 55%+ (probabilidade alta).

---

## 🔄 Combinando os 3 Bots

Você agora tem:
1. **Bot COM gol 1T** (Over 0.5 1T) - Min 10-35
2. **Bot SEM gol 1T** (Under 0.5 1T) - Min 10-35
3. **Bot COM gol 2T** (Over 0.5 2T) - Min 50-80

⚠️ **REGRA:** Escolha APENAS UM bot por jogo no 1T (Over OU Under, não ambos)!

---

## 📞 Suporte

Para dúvidas sobre a configuração ou ajustes finos baseados em seus resultados, consulte a documentação completa do SokkerPRO ou o PDF `sokkerprobots.pdf`.

**Boa sorte e boas apostas! 🍀⚽**
