# Data_Leakage_with_SHAP

Artigo publicado no Medium, clique [aqui](https://medium.com/p/a69985056ba3) para leitura completa.<br>

## Resumo

Detectar vazamento de dados é uma tarefa importantíssima em qualquer projeto de Machine Learning (ML). O vazamento ocorre quando informações que não deveriam estar disponíveis para o modelo, estão presentes nos dados de treinamento. Isso pode ocorrer a partir de dados de teste presentes no treino ou na presença de dados futuros, que ainda não estão disponíveis no momento da predição. <br>

A detecção de informações futuras nos dados de teste podem ser identificados numa análise exploratória bem feita, com um bom entendimento do negócios. Mas e se não percebemos logo de início e deixarmos passar ?<br>

Neste notebook foi montado um modelo de predição de longa permanência de internação hospitalar e demonstrado, na prática, como SHAP (SHapley Additive exPlanations) pode ser usado para detectar vazamento de dados.

* [Notebook](https://github.com/leticiamchd/Data_Leakage_with_SHAP/blob/main/Data_Leakage_with_SHAP.ipynb)
* [Notebook após correção do vazamento](https://github.com/leticiamchd/Data_Leakage_with_SHAP/blob/main/Data_Leakage_with_SHAPv2_0.ipynb)

