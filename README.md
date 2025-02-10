# Data Science and Analytics [DSA-USP-ESALQ-2024]
<<<<<<< 

# Inteligência Artificial para Predição de Acidentes de Trânsito na Rodovia BR-101

### Resumo:

Neste trabalho utilizou-se técnicas de Aprendizado de Máquina, tais como modelos de 
Regressão Logística Multinomial e Random Forest, visando melhorar a segurança viária. 
Foram analisados dados de acidentes de trânsito na BR-101, uma rodovia que enfrenta 
desafios devido à sua extensão e às diversas condições geográficas e climáticas. Este 
trabalho incluiu a identificação dos principais tipos de acidentes e suas causas, bem como os 
trechos da rodovia com maior índice de acidentes. Com base nessa análise, foram 
implementados modelos para prever acidentes e viabilizar a tomada de medidas preventivas. 
A precisão foi estimada com base na proporção de verdadeiros positivos (acidentes previstos 
corretamente) em relação ao total de positivos previstos (verdadeiros positivos e falsos 
positivos). A Regressão Logística Multinomial apresentou um desempenho preditivo com 
precisão de 59,97% e uma diferença de 0,04% entre os conjuntos de treinamento e teste. Já 
o Random Forest obteve uma precisão de aproximadamente 87,60%, com uma diferença de 
12,49% entre esses conjuntos, sugerindo um possível overfitting. Além disso, foram utilizados 
dados abertos da Polícia Rodoviária Federal e ferramentas como Jupyter Notebook e Python 
para visualizar os resultados. Dessa forma, verificou-se os estados brasileiros que devem ter 
prioridade na elaboração e ampliação de políticas públicas para prevenção e redução de 
acidentes de trânsito. A análise considerou dados de geolocalização, como latitude e 
longitude, e explorou como técnicas de IA podem melhorar a segurança nas rodovias.  


### Referências: 

Biau, G. 2012. Analysis of a Random Forests model. The Journal of Machine Learning 
Research 13(1): 1063-1095. 

Boffo, G.H. 2011. Formatos e técnicas de modelos de previsão de acidentes de trânsito. 
Tese de Mestrado em Engenharia de Produção. Escola de Engenharia. Universidade 
Federal do Rio Grande do Sul. Porto Alegre, Rio Grande do Sul, RS, Brasil. 

Caliendo C.; Guida M.; Parisi A. 2007. A crash-prediction model for multilane roads. Accident 
Analysis & Prevention. ScienceDirect 39(4): 657-670. 

Chuerubim, M. L. 2019. Possibilidades em inteligência artificial na detecção de padrões e 
previsão de acidentes em rodovias. Tese de Doutorado em Engenharia de Transportes. 
Escola de Engenharia de São Carlos. Universidade de São Paulo. São Carlos, SP, Brasil. 

Confederação Nacional do Transporte [CNT]. 2022. Painel CNT de Acidentes Rodoviários - 
Principais dados 2022. Disponível em: <https://www.cnt.org.br/painel-acidente>. Acesso em: 
28 set. 2023. 

Dataset. Dados Abertos da Polícia Rodoviária Federal [PRF] - Arquivos em formato .CSV. 
Disponível em: <https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dadosabertos-da-prf>. Acesso em: 27 ago. 2023.

Departamento Nacional de Infraestrutura de Transportes [DNIT]. 2021. Estatísticas de 
Acidentes. Disponível em: <https://www.gov.br/dnit/pt-br/rodovias/operacoesrodoviarias/estatisticas-de-acidentes>. Acesso em: 15 ago. 2023. 

Departamento Nacional de Infraestrutura de Transportes [DNIT]. 2020. Nomenclatura das 
Rodovias Federais. Disponível em: <https://www.gov.br/dnit/pt-br/rodovias/rodoviasfederais/nomeclatura-das-rodovias-federais>. Acesso em: 26 set. 2023. 

Gelman, A.; Hill, J. 2006. Data Analysis Using Regression and Multilevel/Hierarchical 
Models. Cambridge University Press., Cambridge, UK. 

Google. Receber alertas sobre vias com histórico de acidentes: Ajuda do Waze. 2023. 
Disponível em: <https://support.google.com/waze/answer/13014546?hl=pt-BR >. Acesso em: 
25 ago. 2023. 

Kraut, C.; Sapia, H. M. 2022. Aprendizado de máquina utilizando agrupamento e regressão 
na previsão de locais de acidentes de trânsito em zonas urbanas. Colloquium Exactarum 
14(1): 1-11. 

Lima. J.F.S.; Vilar. J.W.C. 2022. Nova configuração territorial da BR-101 em Sergipe - 
Brasil. Revista Geográfica Acadêmica 16(2): 86-99. 

Lobato, C.R.V. 2018. Análise dos acidentes nas rodovias federais concedidas no Brasil. 
Tese de Mestrado em Geotecnia e Transportes. Universidade Federal de Minas Gerais. Belo 
Horizonto, Minas Gerais, MG, Brasil. 

Raschka S.; Mirjalili V. 2015. Python Machine Learning: Machine Learning and Deep 
Learning With Python, Scikit-Learn, and TensorFlow 2, 5ed., Packt Publishing Ltd., 
Birmingham, UK. 

Tukey, J. W. 1977. Exploratory data analysis, Volume 2., 18ed., Addison-Wesley Publishing 
Company, Massachusetts, EUA. 

US Department of Transportation’s Federal Highway Administration [FHWA]. Intelligent 
Transportation Systems Joint Program Office. Disponível em: <https://highways.dot.gov>. 
Acesso em: 23 ago. 2023. 

Wang, B. et al. 2022. Comparing Resampling Algorithms and Classifiers for Modeling Traffic 
Risk Prediction. International Journal of Environmental Research and Public Health 19(1): 1-
23. 

World Health Organization [WHO]. 2023. Road traffic injuries. Disponível em: 
<https://www.who.int/health-topics/road-safety>. Acesso em: 15 ago. 2023. 

### Arquivos:

**_DATASET-ACIDENTES_RODOVIAS_FED-2018-2023-PRF** == contém o dataset coletado na base de dados da PRF [salvo em .CSV].

**Dataframe-dados-processados-tratados** == contém planilhas com os dados [em .CSV].

**Plots-Figuras** == contém todas as figuras utilizadas neste trabalho, inclusive as geradas por meio dos scripts.

**Scripts-Python-JupyterNotebook** == contém os scripts utilizados nas etapas deste trabalho: [000Coleta-e-Limpeza.ipynb]; [001Filtragem_e_AnaliseExploratória.ipynb];[002Aprendizado_e_003Avaliacao.ipynb]; e [004Predicao.ipynb]. 

**PLANILHA 1 Apendice-MBA-DSA-TCC-USPesalq** == planilha com descrição detalhada dos dados provenientes do dataset.

**Requirements** == requisitos para reprodução deste trabalho.




