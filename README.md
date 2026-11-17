# Machine Learning Aplicado à Engenharia

Slides, notebooks e trabalhos da disciplina de graduação em Engenharia Elétrica da Universidade Federal de São João del-Rei (UFSJ), ministrada por Samir A. M. Martins. Fundamentos matemáticos e aplicações em Python: análise de dados, classificação, regressão, identificação de sistemas dinâmicos e recomendação.

[Ementa](EMENTA.md) · [Aulas](#aulas) · [Aplicações](#aplicações-e-estudos-de-caso) · [Dados](#dados-e-execução) · [Trabalhos](#trabalhos-da-disciplina)

## Aulas

| Aula | Conteúdo | Código | Slides |
| --- | --- | --- | --- |
| 01 | Introdução, Python básico, Anaconda, Jupyter e Spyder | [Notebook](aula_1_ml_py_basis/codigo_aula1.ipynb) | [PDF](aula_1_ml_py_basis/aula1_ml.pdf) |
| 02 | Conda, pip, instalação de bibliotecas e exportação de ambientes | - | [PDF](aula_2_ml_env_conda/ml_aula2.pdf) |
| 03 | NumPy, Matplotlib e Pandas | [NumPy](aula_3_np_pd_plt/codigo_numpy.ipynb), [Pandas](aula_3_np_pd_plt/codigo_pandas.ipynb), [Matplotlib](aula_3_np_pd_plt/codigo_matplotlib.py) | [PDF](aula_3_np_pd_plt/ml_np_plt_pd.pdf) |
| 04 | Estatística descritiva, correlação, probabilidade e Bayes | [Notebook](aula_4_est_prob_parte1/estatistica_probabilidade.ipynb) | [PDF](aula_4_est_prob_parte1/ml_est_prob.pdf) |
| 05 | Arquivos, fontes de dados e APIs | [Notebook + dados - ZIP](aula_5_dados_py/aula_5_dados_py.zip) | [PDF](aula_5_dados_py/ml_dados_py.pdf) |
| 06 | Modelagem, subajuste/sobreajuste, viés/variância e atributos de sinais | [Notebook](aula_6_ml_viesvar/aula_aprendizado_maquina.ipynb) | [PDF](aula_6_ml_viesvar/aula_aprendizado_maquina.pdf) |
| 07 | Classificação e avaliação de classificadores | [Notebook](aula_7_classificacao/aula_07_tecnicas_de_classificacao.ipynb) | [PDF](aula_7_classificacao/aula_07_tecnicas_de_classificacao.pdf) |
| 08 | Regressão, resíduos e métricas | [Notebook](aula_8_regressao/aula_08_tecnicas_de_regressao.ipynb) | [PDF](aula_8_regressao/aula_08_tecnicas_de_regressao.pdf) |
| 09 | KNN, distâncias, padronização e validação cruzada | [Notebook](aula_9_knn/aula_09_knn_classificacao.ipynb) | [PDF](aula_9_knn/aula_09_knn_classificacao.pdf) |
| 10 | Regressão linear simples e múltipla; previsão temporal | [Notebook](aula_10_regressaoLinear/aula10_regressao_linear.ipynb) | [PDF](aula_10_regressaoLinear/aula10_regressao_linear.pdf) |
| 11 | Regressão logística, desbalanceamento e limiar de decisão | [Notebook](aula_11_regressaoLogistica/aula_11_regressao_logistica.ipynb) | [PDF](aula_11_regressaoLogistica/aula_11_regressao_logistica.pdf) |
| 12 | Ridge, Lasso, ElasticNet, expansão polinomial e validação temporal | [Notebook](aula_12_Ridge_Lasso_elasticNet/aula_regressao_regularizada_polinomial.ipynb) | [PDF](aula_12_Ridge_Lasso_elasticNet/aula_Ridge_Lasso_elasticNet.pdf) |
| 13 | Árvores de decisão, florestas aleatórias e SVM | [Notebook](aula_13_dt_rf_svm/aula_13_dt_rf_svm.ipynb) | [PDF](aula_13_dt_rf_svm/aula_13_dt_rf_svm.pdf) |
| 14 | SysIdentPy: identificação de sistemas, NARX, NAR, FROLS e BIC | [Notebook](aula_14_sysidentpy/aula_14_sysidentpy.ipynb) | [PDF](aula_14_sysidentpy/aula_14_sysidentpy.pdf) |
| 15 | Recomendação, filtragem colaborativa e Precision@K | [Notebook](aula_15_recomendadores/aula_sistemas_recomendadores.ipynb) | [PDF](aula_15_recomendadores/aula_sistemas_recomendadores.pdf) |

## Aplicações e estudos de caso

### Bases externas

| Aplicação e dados | Abordagem | Aulas |
| --- | --- | --- |
| Estabilidade de redes elétricas - simulações | KNN, árvores, florestas e SVM; padronização, validação cruzada para k e métricas | [09](aula_9_knn/aula_09_knn_classificacao.ipynb), [13](aula_13_dt_rf_svm/aula_13_dt_rf_svm.ipynb) |
| Potência líquida de usina de ciclo combinado - medições operacionais | Regressão estática simples/múltipla, Ridge/Lasso/ElasticNet e expansão polinomial; seleção de atributos e métricas | [10](aula_10_regressaoLinear/aula10_regressao_linear.ipynb), [12](aula_12_Ridge_Lasso_elasticNet/aula_regressao_regularizada_polinomial.ipynb) |
| Potência ativa residencial - medições | Regressão linear, defasagens, médias móveis e codificação horária; divisão temporal, um passo à frente e predição livre | [10](aula_10_regressaoLinear/aula10_regressao_linear.ipynb) |
| Falhas para manutenção preditiva | Logística e KNN; desbalanceamento e limiar por custo na validação | [11](aula_11_regressaoLogistica/aula_11_regressao_logistica.ipynb) |
| Passageiros mensais em aviação - série histórica | Regressão regularizada, defasagens, tendência e sazonalidade; validação cruzada temporal, um passo à frente e predição livre | [12](aula_12_Ridge_Lasso_elasticNet/aula_regressao_regularizada_polinomial.ipynb) |
| Vibração estrutural do F-16 - experimental | NARX polinomial, FROLS/BIC e predição livre | [14](aula_14_sysidentpy/aula_14_sysidentpy.ipynb) |
| Motor-gerador CC - experimental | NARX, padronização, FROLS/BIC e predição livre | [14](aula_14_sysidentpy/aula_14_sysidentpy.ipynb) |
| Demanda hospitalar em San Francisco | NAR, defasagens, BIC e predição livre | [14](aula_14_sysidentpy/aula_14_sysidentpy.ipynb) |
| Filmes - avaliações de usuários | Filtragem colaborativa item-item, cosseno em NumPy, baseline de popularidade e Precision@K offline | [15](aula_15_recomendadores/aula_sistemas_recomendadores.ipynb) |

### Exemplos sintéticos

| Aplicação | Conceitos | Aulas |
| --- | --- | --- |
| Carga e temperatura de equipamentos e transformadores | Ajuste linear, resíduos, polinômios com Ridge e floresta aleatória | [06](aula_6_ml_viesvar/aula_aprendizado_maquina.ipynb), [08](aula_8_regressao/aula_08_tecnicas_de_regressao.ipynb) |
| Sinal ruidoso | Graus polinomiais, subajuste/sobreajuste e erro em treino/teste | [06](aula_6_ml_viesvar/aula_aprendizado_maquina.ipynb) |
| Diagnóstico normal/falha | Matriz construída: acurácia, precisão, recall e F1; comparação com sempre prever normal | [06](aula_6_ml_viesvar/aula_aprendizado_maquina.ipynb) |
| Sinais normais e com harmônicos/ruído | RMS, fator de crista e THD com FFT | [06](aula_6_ml_viesvar/aula_aprendizado_maquina.ipynb) |
| Condições operacionais de motores | Logística e KNN, fronteiras de decisão, escala e validação cruzada | [07](aula_7_classificacao/aula_07_tecnicas_de_classificacao.ipynb), [09](aula_9_knn/aula_09_knn_classificacao.ipynb) |
| Resistência elétrica pela Lei de Ohm | Regressão sem intercepto, interpretação física e resíduos | [10](aula_10_regressaoLinear/aula10_regressao_linear.ipynb) |
| Desvio de tensão e variação de carga | SVM RBF e fronteira de decisão 2D | [13](aula_13_dt_rf_svm/aula_13_dt_rf_svm.ipynb) |

## Dados e execução

Os dados utilizados nos exemplos estão disponíveis nos links abaixo.

| Dados | Fontes e arquivos |
| --- | --- |
| Estabilidade de redes | [Electrical Grid Stability/UCI](https://archive.ics.uci.edu/dataset/471) |
| Usina de ciclo combinado | [CCPP/UCI](https://archive.ics.uci.edu/dataset/294) |
| Consumo residencial | [Household Electric Power Consumption/UCI](https://archive.ics.uci.edu/dataset/235) |
| Manutenção preditiva | [AI4I 2020/UCI](https://archive.ics.uci.edu/dataset/601) |
| Passageiros | [AirPassengers/R](https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/AirPassengers.html) · [CSV/Rdatasets](https://raw.githubusercontent.com/vincentarelbundock/Rdatasets/master/csv/datasets/AirPassengers.csv) |
| F-16 | [Benchmark original](https://www.nonlinearbenchmark.org/benchmarks/f-16-gvt) · [Arquivo/SysIdentPy](https://raw.githubusercontent.com/wilsonrljr/sysidentpy-data/refs/heads/main/datasets/f_16_vibration_test/f-16.txt) |
| Motor-gerador CC | [Experimento/SysIdentPy](https://sysidentpy.org/user-guide/tutorials/electromechanical-system-identification-overview/) · [Entrada](https://raw.githubusercontent.com/wilsonrljr/sysidentpy-data/refs/heads/main/datasets/generator/x_cc.csv) · [Saída](https://raw.githubusercontent.com/wilsonrljr/sysidentpy-data/refs/heads/main/datasets/generator/y_cc.csv) |
| Demanda hospitalar | [OpenEI/NREL](https://data.openei.org/submissions/153) · [Proveniência via NeuralProphet/SysIdentPy](https://raw.githubusercontent.com/wilsonrljr/sysidentpy-data/main/data_sources.md) · [CSV](https://raw.githubusercontent.com/wilsonrljr/sysidentpy-data/refs/heads/main/datasets/san_francisco_hospital/SanFrancisco_Hospital.csv) |
| Filmes | [MovieLens/GroupLens](https://grouplens.org/datasets/movielens/latest/) |
| Curva de carga | [ONS](https://dados.ons.org.br/dataset/curva-carga) |
| Capacidade de geração | [SIGA/ANEEL](https://dadosabertos.aneel.gov.br/dataset/siga-sistema-de-informacoes-de-geracao-da-aneel) |
| Estados brasileiros | [API de Localidades/IBGE](https://servicodados.ibge.gov.br/api/docs/localidades) |
| Selic anualizada, base 252 | [SGS 1178/BCB](https://dadosabertos.bcb.gov.br/dataset/1178-taxa-de-juros---selic-anualizada-base-252) |

## Trabalhos da disciplina

| Trabalho | Escopo | Materiais |
| --- | --- | --- |
| T1 - Análise de dados reais | Obtenção e preparação em Python, análise exploratória/estatística, gráficos e proposta de tarefa de ML | [Enunciado](trabalho1/trabalho1_enunciado.ipynb) |
| T2 - Modelagem e validação | Continuação supervisionada do T1: pelo menos três modelos e três métricas, validação e artigo técnico | [Enunciado](trabalho2/t2_enunciado.pdf) · [LaTeX](trabalho2/trabalho2_latex/t2_machine_learning.tex) |

[Projetos dos alunos - turma 2026/1](REPOSITORIOS_TRABALHOS_2026_1.MD), por grupo e tema. Autoria dos respectivos grupos.

## Licença

[BSD 3-Clause](LICENSE). Dados e materiais de terceiros seguem os termos das respectivas fontes.
