Como elevei a precisão de um modelo de precificação de imóveis de R² 0,47 para **0,7603** com Engenharia de Recursos Estratégica! 🚀

---

### 🧠 O DIAGNÓSTICO: MODELAGEM SEGMENTADA

Eu reconheci que o mercado imobiliário não era homogêneo. Tentar usar um modelo único (o modelo simples falhava) era o erro.

A solução foi criar um sistema de dois modelos:

* **1️⃣ Segmento Padrão (Preços ≤ R$ 400k):**
    * Foco: Estabilidade e Precisão.
    * Ação: Apliquei Limpeza Seletiva de Outliers (IQR) para remover o ruído.
    * Resultado (R²): **0,53** (Estável).

* **2️⃣ Segmento Luxo (R$ 400k a R$ 2M):**
    * Foco: Poder Preditivo.
    * Ação: Usei a Transformação Logarítmica e MANTIVE os Outliers de preço para que o modelo aprendesse as regras do topo do mercado.
    * Resultado (R²): **0,60** (Alto poder explicativo).

---

### 🏆 O SALTO DE PERFORMANCE

O sistema combinado gerou este resultado final, superando em muito o modelo inicial:

**R² GLOBAL FINAL: ✨ 0,7603 ✨**

**MAE GLOBAL: R$ 86.429,71** (Erro médio reduzido em mais de R$ 15 mil).

A principal lição: Entender o negócio e aplicar a Engenharia de Recursos de forma oposta em cada segmento foi o que fez a diferença.

![Preview da Plataforma](images/grafico.jfif)
