# Otimização do Diagnóstico de Câncer de Mama Utilizando Aprendizado de Máquina

## Visão Geral do Projeto
Este projeto explora a aplicação de técnicas avançadas de aprendizado de máquina para otimizar o diagnóstico de câncer de mama. Utilizando o "Breast Cancer Wisconsin (Diagnostic) Dataset", desenvolvemos modelos preditivos para melhorar a precisão, eficiência e confiabilidade do diagnóstico de câncer de mama.

## Características Principais
- Técnicas de pré-processamento de dados e seleção de características
- Implementação de diversos algoritmos de aprendizado de máquina, incluindo Máquinas de Vetores de Suporte (SVM)
- Avaliação do desempenho do modelo usando métricas como precisão, recall e F1-score
- Visualização de resultados usando matrizes de confusão e gráficos de dispersão

## Tecnologias Utilizadas
- Python
- Pandas
- Scikit-learn
- Seaborn (para visualizações)
- Matplotlib (para visualizações)

## Metodologia
1. **Pré-processamento de Dados**: Limpeza e normalização do conjunto de dados Wisconsin Breast Cancer.
2. **Seleção de Características**: Utilização da Eliminação Recursiva de Características com Validação Cruzada (RFECV) para identificar as características mais significativas.
3. **Seleção do Modelo**: Avaliação de múltiplos modelos, incluindo K-Nearest Neighbors (KNN), Support Vector Classifier (SVC) e Random Forest Classifier (RFC).
4. **Treinamento e Avaliação do Modelo**: Treinamento do modelo selecionado (SVC) e avaliação de seu desempenho usando várias métricas.

## Resultados
- O Support Vector Classifier (SVC) alcançou alta precisão na classificação de tumores mamários.
- Características-chave identificadas para o diagnóstico incluem 'radius_mean', 'texture_mean', 'perimeter_mean', 'area_mean', 'concavity_mean' e 'concave points_mean'.
- O modelo demonstrou desempenho robusto na minimização de falsos positivos e falsos negativos.

### Visualizações

#### Busca da quantidade ideal de features para o modelo
![image](https://github.com/user-attachments/assets/d39f9b22-46f2-48f2-a45e-0efaba9f9ac7)

#### Visualização 2D dos dados
![image](https://github.com/user-attachments/assets/f029e4a7-1906-4e31-9812-6048e1bfe26d)


#### Resultado final do modelo
![image](https://github.com/user-attachments/assets/d22ef89a-aaaf-4a45-ae34-a57f8e7b709c)

## Trabalhos Futuros
- Expandir o conjunto de dados para incluir fatores clínicos e demográficos mais diversos.
- Explorar técnicas adicionais de aprendizado de máquina e modelos de aprendizado profundo.
- Investigar o potencial de aplicação clínica no mundo real e integração com ferramentas de diagnóstico existentes.

## Contribuidores
- Ederjofre Filho
- Dalton Erthal

## Licença
None

## Agradecimentos
- Universidade de Coimbra por apoiar esta pesquisa
- Dr. William H. Wolberg e a Universidade de Wisconsin por fornecer o conjunto de dados

---

Para informações mais detalhadas sobre a metodologia, resultados e discussões, consulte o artigo completo neste repositório.
