Decifrando a Caixa Preta: Tornando Modelos de IA Explicáveis com LIME 

Este projeto implementa técnicas de Explainable AI (XAI) utilizando a biblioteca  LIME (Local Interpretable Model-Agnostic Explanations)  para tornar transparentes as decisões de um modelo de machine learning aplicado à análise de risco de crédito bancário.

🎯 Objetivos

Desenvolver um modelo preditivo para classificação de risco de crédito
Aplicar LIME  para gerar explicações locais das previsões do modelo
Demonstrar como a interpretabilidade pode melhorar a confiança  em sistemas de ML
Analisar limitações e benefícios das explicações geradas.

LIME (Local Interpretable Model-Agnostic Explanations)

Explicações Locais: Entende decisões específicas para cada cliente
Model-Agnostic: Funciona com qualquer tipo de modelo
Aproximação Local: Usa modelos lineares para explicar predições individuais
Interpretabilidade: Gera explicações em linguagem compreensível

  Modelo Preditivo Escolhido
Random Forest Classifier
Justificativa da Escolha:

Performance: Excelente capacidade preditiva para dados tabulares
Robustez: Resistente a overfitting e outliers
Feature Importance: Fornece importância global das variáveis
Interpretabilidade Parcial: Estrutura de árvores é relativamente interpretável
Estabilidade: Predições consistentes para LIME


