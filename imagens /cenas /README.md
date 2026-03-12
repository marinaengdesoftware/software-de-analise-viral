# Detector e Extrator de Cenas

Esta etapa do sistema é responsável por **identificar e segmentar mudanças estruturais dentro do conteúdo analisado**, permitindo dividir o vídeo em unidades narrativas menores chamadas de **cenas**.

A detecção de cenas é uma etapa fundamental do pipeline, pois permite analisar a estrutura narrativa do conteúdo de forma mais precisa.

---

# Objetivo

O detector de cenas busca identificar **pontos de transição na narrativa visual**, onde ocorre uma mudança significativa na composição da imagem.

Essas transições podem incluir:

* mudança de enquadramento
* alteração de ambiente
* entrada ou saída de personagens
* mudança de foco narrativo
* transições visuais relevantes

A segmentação correta dessas cenas permite que as etapas seguintes do sistema analisem **como a narrativa é construída ao longo do conteúdo**.

---

# Processo de Extração

O processo de detecção e extração segue uma lógica geral:

```text
Vídeo de entrada
        ↓
Análise de continuidade visual
        ↓
Identificação de transições
        ↓
Segmentação de cenas
        ↓
Extração de frames representativos
```

Cada cena identificada passa a ser tratada como **uma unidade estrutural da narrativa**.

---

# Frames Representativos

Após a segmentação, o sistema extrai **frames representativos de cada cena**, que são utilizados para:

* análise de composição visual
* identificação de estímulos narrativos
* observação de padrões recorrentes
* apoio à identificação de beats narrativos

Esses frames servem como base para as próximas etapas do pipeline.

---

# Importância para a Análise Viral

Conteúdos com alta performance costumam apresentar **ritmo narrativo estruturado**, com alternância controlada de cenas que mantém a atenção do espectador.

A detecção de cenas permite estudar:

* ritmo de edição
* densidade de estímulos visuais
* duração média das cenas
* pontos de mudança narrativa

Esses fatores influenciam diretamente a retenção e o engajamento do público.

---

# Observação

Os exemplos presentes nesta pasta representam **amostras geradas durante o processo de segmentação de cenas**.

Eles são utilizados como referência visual para documentar a estrutura narrativa identificada pelo sistema.

