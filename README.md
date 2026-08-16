# Miniprojeto_RhommarMartinez_Visualiza-o-de-Dados-e-BI-T3-
Análise Exploratória de Dados (AED) aplicada ao varejo para aprender como transformar dados brutos em informações úteis.

Este projeto foi desenvolvido como parte do curso de Visualização de Dados e BI, com o objetivo de aplicar técnicas de Análise Exploratória de Dados (AED) no contexto do varejo. Através da análise de dados brutos, buscamos identificar padrões, tendências e insights que possam auxiliar na tomada de decisões estratégicas para o negócio.

Foi usado o arquivo base varejo.csv e criado outro arquivo a partir do original chamado limpo_varejo.csv, onde serão armazenados os dados tratados e limpos, prontos para análise.

Sera usado jupyter Notebook para realizar a análise exploratória dos dados, utilizando bibliotecas como pandas, matplotlib e seaborn para visualização e manipulação dos dados.

E necessario criar o ambiente ambiente virtual para instalar as bibliotecas necessárias para o projeto, garantindo que todas as dependências estejam corretamente configuradas.

no terminal 
escrever  
python -m venv .venv
ativar o ambiente virtual
no windows
.\venv\Scripts\activate 

instalar as bibliotecas necessárias
pip install pandas matplotlib seaborn

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import os
import re
import datetime

Para esta analise exploratoria de dados deste arquivo se tomaram apenas 100 linhas de registro. Para fazer para fines academicos e de aprendizado, pois o arquivo original contem mais de 1.000 linhas.

![alt text](image.png)