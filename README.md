# GeoGuardian

**FIAP** — _Faculdade de Informática e Administração Paulista_  
**Matéria:** _Disruptive Architectures: IoT, IoB & Generative AI_  
**Turma:** _2TDSPW_  
**Professor:** _Alberto Messias_

## Integrantes

- Cauã Marcelo Machado — _RM 558024_
- Gabriel Lima Silva — _RM 556773_
- Felipe Melo de Sousa — _RM 556099_

---

## Descrição do Problema

Atualmente, diversas regiões enfrentam riscos ambientais como enchentes, deslizamentos e rompimentos de barragens. Apesar da coleta massiva de dados por sensores IoT, a análise desses dados em larga escala apresenta desafios que dificultam a identificação antecipada de eventos críticos. Isso pode resultar em:

- Falsos positivos e alertas irrelevantes;
- Dificuldade em priorizar riscos reais;
- Atrasos na tomada de decisão, aumentando o perigo para comunidades e o meio ambiente.

O **GeoGuardian** visa solucionar esses problemas aplicando análise preditiva e machine learning para transformar dados brutos em insights precisos, antecipando situações de risco e otimizando a resposta às emergências.

---

## Objetivo do Projeto

Criar uma solução inteligente para monitoramento ambiental que:

- Simula e gera dados realistas de sensores IoT;
- Analisa padrões de risco e distribuições dos alertas;
- Utiliza modelos de machine learning para classificar o nível de risco;
- Facilita a tomada de decisões rápidas e embasadas para equipes de segurança.

---

## Etapas do Projeto

### Fase 1 — Setup e Bibliotecas

- Instalação das bibliotecas Python necessárias para análise de dados e machine learning: pandas, seaborn, matplotlib, scikit-learn, xgboost.

### Fase 2 — Geração do Dataset Simulado

- Simulação de 5.000 registros contendo localização, dados ambientais (temperatura, umidade, vibração, qualidade do solo), nível de risco e data.

### Fase 3 — Análise Exploratória dos Dados

- Avaliação das características do dataset;
- Visualização da distribuição de níveis de risco e localização dos sensores;
- Análise das variáveis ambientais e correlações.

### Fase 4 — Visualização de Dados

- Gráficos para facilitar o entendimento dos padrões de risco e localização;
- Histogramas e mapas de calor para correlação entre variáveis.

### Fase 5 — Machine Learning: Classificação do Nível de Risco

- Codificação das variáveis categóricas;
- Treinamento de modelo XGBoost para previsão do risco;
- Avaliação do desempenho com métricas de acurácia e matriz de confusão.

### Fase 6 — Exportação dos Dados

- Salvamento do dataset simulado para uso futuro.

---

## Conclusão

O **GeoGuardian** oferece uma solução escalável para a gestão de riscos ambientais baseada em dados IoT, permitindo:

- Previsão antecipada de situações de risco;
- Identificação de padrões críticos e locais vulneráveis;
- Melhoria na alocação de recursos de segurança;
- Resposta mais eficiente e rápida a incidentes.

---

## Aplicações Futuras

- Monitoramento em tempo real para cidades inteligentes;
- Uso em segurança privada e proteção patrimonial;
- Extensão para monitoramento de riscos digitais e físicos.

---

## Arquivos do Projeto

- `geoguardian_dataset.csv` — Dataset simulado com 5.000 registros de sensores IoT.
- Notebook Python com código para geração, análise e modelagem dos dados.

---

Se quiser, entre em contato para contribuir, tirar dúvidas ou sugerir melhorias!

---

**Cauã Marcelo Machado, Gabriel Lima Silva, Felipe Melo de Sousa**  
_FIAP - 2025_
