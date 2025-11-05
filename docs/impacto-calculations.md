# 📊 Cálculo de Impacto Ambiental - TrashMove

## Visão Geral

O TrashMove calcula o impacto ambiental baseado em **métricas científicas reconhecidas** internacionalmente para reciclagem e sustentabilidade.

---

## 🔢 Fórmulas de Cálculo

### 1. **CO₂ Evitado** (Redução de Emissões)

Para cada tipo de material reciclado, utilizamos fatores de conversão padrão:

```
CO₂ Evitado (kg) = Quantidade Reciclada (kg) × Fator de Emissão (kg CO₂/kg)
```

#### Fatores de Emissão por Material:

| Material | Fator CO₂/kg | Fonte |
|----------|-------------|-------|
| **Plástico (PET)** | 2.3 kg CO₂/kg | EPA, World Resources Institute |
| **Papel** | 1.5 kg CO₂/kg | EPA, Carbon Trust |
| **Alumínio** | 8.5 kg CO₂/kg | International Aluminum Institute |
| **Vidro** | 0.3 kg CO₂/kg | EPA, Glass Packaging Institute |
| **Metal (Latas)** | 3.5 kg CO₂/kg | Steel Recycling Institute |
| **Eletrônicos** | 15.0 kg CO₂/kg | UN E-Waste Monitor (média) |

#### Exemplo de Cálculo:

- **Plástico**: 5 kg × 2.3 = **11.5 kg CO₂ evitado**
- **Papel**: 10 kg × 1.5 = **15.0 kg CO₂ evitado**
- **Total**: **26.5 kg CO₂ evitado**

---

### 2. **Árvores Equivalente Salvos**

Baseado no impacto de **reciclagem de papel**:

```
Árvores Equivalentes = Papel Reciclado (kg) ÷ 15 kg
```

**Fonte**: Em média, **15 kg de papel reciclado** salvam **1 árvore** (EPA, Forest Products Association).

#### Exemplo:

- **Papel reciclado**: 48 kg
- **Árvores equivalentes**: 48 ÷ 15 = **3.2 árvores**

---

### 3. **Água Poupa da** (Em Litros)

```
Água Poupa da = Quantidade Reciclada (kg) × Fator de Água (L/kg)
```

#### Fatores por Material:

| Material | Fator Água (L/kg) |
|----------|------------------|
| **Plástico** | 50 L/kg |
| **Papel** | 300 L/kg |
| **Alumínio** | 1000 L/kg |
| **Vidro** | 20 L/kg |
| **Metal** | 200 L/kg |

#### Exemplo:

- **Papel**: 10 kg × 300 = **3,000 litros poupados**
- **Alumínio**: 2 kg × 1000 = **2,000 litros poupados**
- **Total**: **5,000 litros**

---

### 4. **Energia Poupa da** (Em kWh)

```
Energia Poupa da = Quantidade Reciclada (kg) × Fator de Energia (kWh/kg)
```

#### Fatores por Material:

| Material | Energia (kWh/kg) |
|----------|-----------------|
| **Plástico** | 12 kWh/kg |
| **Papel** | 7 kWh/kg |
| **Alumínio** | 120 kWh/kg |
| **Vidro** | 1 kWh/kg |
| **Metal** | 6 kWh/kg |

#### Exemplo:

- **Alumínio**: 2 kg × 120 = **240 kWh poupados**
- **Papel**: 10 kg × 7 = **70 kWh poupados**
- **Total**: **310 kWh**

---

### 5. **Pontos Verdes** (Gamificação)

Sistema de pontuação simplificado:

```
Pontos = Material Reciclado (kg) × Multiplicador de Material
```

#### Multiplicadores:

| Material | Multiplicador | Justificativa |
|----------|--------------|---------------|
| **Eletrônicos** | 20 pontos/kg | Alto impacto ambiental |
| **Alumínio** | 10 pontos/kg | Reciclagem de alto valor |
| **Plástico** | 5 pontos/kg | Problema crítico global |
| **Papel** | 4 pontos/kg | Impacto florestal |
| **Vidro** | 3 pontos/kg | Reciclagem infinita |
| **Metal (Latas)** | 6 pontos/kg | Alto valor de reciclagem |

#### Exemplo:

- **Eletrônicos**: 0.5 kg × 20 = **10 pontos**
- **Plástico**: 5 kg × 5 = **25 pontos**
- **Papel**: 10 kg × 4 = **40 pontos**
- **Total**: **75 pontos**

---

### 6. **Patentes / Níveis** (Gamificação)

Baseado no **total acumulado de kg reciclados**:

| Patente | Requisito | Kg Acumulado |
|---------|-----------|--------------|
| 🌱 **Iniciante Verde** | - | 0-5 kg |
| 🌿 **Guardião Sustentável** | Básico | 20 kg |
| 🌎 **Herói Ambiental** | Avançado | 50 kg |
| 🔋 **Líder Ecológico** | Expert | 100 kg |
| 🌟 **Embaixador do Planeta** | Especial | Múltiplos + Social |

---

## 📈 Cálculo Mensal (Exemplo Real)

### Dados do Usuário (Janeiro/2025):

| Material | Quantidade | Data |
|----------|-----------|------|
| Plástico PET | 5 kg | 05/01 |
| Papel | 8 kg | 12/01 |
| Alumínio | 1.5 kg | 20/01 |
| Eletrônicos | 0.5 kg | 28/01 |
| **TOTAL** | **15 kg** | - |

### Resultados do Cálculo:

#### 1. CO₂ Evitado:
- Plástico: 5 × 2.3 = **11.5 kg CO₂**
- Papel: 8 × 1.5 = **12.0 kg CO₂**
- Alumínio: 1.5 × 8.5 = **12.75 kg CO₂**
- Eletrônicos: 0.5 × 15 = **7.5 kg CO₂**
- **TOTAL**: **43.75 kg CO₂**

#### 2. Árvores:
- Papel: 8 ÷ 15 = **0.53 árvores**

#### 3. Água:
- Plástico: 5 × 50 = **250 L**
- Papel: 8 × 300 = **2,400 L**
- Alumínio: 1.5 × 1000 = **1,500 L**
- **TOTAL**: **4,150 litros**

#### 4. Energia:
- Plástico: 5 × 12 = **60 kWh**
- Papel: 8 × 7 = **56 kWh**
- Alumínio: 1.5 × 120 = **180 kWh**
- **TOTAL**: **296 kWh**

#### 5. Pontos:
- Eletrônicos: 0.5 × 20 = **10 pts**
- Plástico: 5 × 5 = **25 pts**
- Papel: 8 × 4 = **32 pts**
- Alumínio: 1.5 × 10 = **15 pts**
- **TOTAL**: **82 pontos**

#### 6. Patente:
- **Total acumulado**: 15 kg → 🌱 **Iniciante Verde**

---

## 🔄 Atualização em Tempo Real

O app calcula automaticamente quando o usuário:

1. ✅ **Registra uma coleta** via formulário
2. ✅ **Confirma a coleta** do caminhão (check-in)
3. ✅ **Conecta com balanças IoT** (futuro)
4. ✅ **Integra com cooperativas** parceiras

---

## 📊 Dashboard de Impacto

O usuário visualiza:

```
┌─────────────────────────────────────┐
│ 🌱 SEU IMPACTO ESTE MÊS             │
├─────────────────────────────────────┤
│ 📦 Reciclado: 15 kg                 │
│ 🌍 CO₂ Evitado: -43.75 kg           │
│ 🌳 Árvores: 0.5                     │
│ 💧 Água: 4,150 L                    │
│ ⚡ Energia: 296 kWh                  │
│ 🎯 Pontos: 82                       │
│ 🏆 Patente: Iniciante Verde         │
└─────────────────────────────────────┘
```

---

## 🌐 Impacto Coletivo (Cidade/Comunidade)

Para mostrar o **impacto agregado**:

```
Impacto Total = Σ (Impacto de todos os usuários)
```

**Exemplo**: Se 1000 usuários reciclaram no mês:

- **Total Reciclado**: 15,000 kg (15 toneladas)
- **CO₂ Evitado**: 43,750 kg (43.75 toneladas)
- **Árvores**: 530 árvores
- **Água**: 4,150,000 litros (4.15 ML)

---

## 📚 Referências Científicas

1. **EPA** (Environmental Protection Agency) - Fatores de emissão
2. **Carbon Trust** - Métricas de carbono
3. **World Resources Institute** - Dados globais
4. **International Aluminum Institute** - Reciclagem de alumínio
5. **UN E-Waste Monitor** - Eletrônicos
6. **Steel Recycling Institute** - Latas de metal

---

## 🔮 Melhorias Futuras

1. **IoT Integration**: Balanças automáticas
2. **Machine Learning**: Previsão de impacto
3. **Blockchain**: Certificação de crédito de carbono
4. **API Gov**: Integração com dados municipais
5. **Comparações**: Benchmark regional/nacional

---

## 💡 Transparência

Todos os cálculos são:
- ✅ **Auditáveis** pelo usuário
- ✅ **Baseados em ciência** reconhecida
- ✅ **Atualizados** conforme novas pesquisas
- ✅ **Divulgados** na tela de detalhes

**"Transformando lixo em valor, um kg por vez."** 🌱

