# Descrição do projeto

O objetivo do projeto é construir uma interface via Gradio na qual seja possível o envio de arquivos em PDF contento informações a respeito de gastos pessoas e que através de técnica como Text Embeddings e com Generative AI o usuário possa obter informações relevantes a respeitos dos dados usados como input.

## Etapas
![image]()
*fonte: autor*
<br>
<br>

1. Obter dados do usuário em formato adequado (PDF)
2. Aplicar Text Embedding ao PDF de modo que o modelo (LLaMA) possa diferir)
3. Enviar os dados para um VectorDataBase(Pinecode)
4. Ajustar prompt e aspectos relacionados a resposta desejada
5. Entregar dados ao modelo
6. Avaliar resposta

## Requirements
A linguagem dinâmica escolhida foi Python, para IDE eu optei pelo jupyter lab. 

### Packages
Instale os seguintes pacotes

``` Python
import os
import warnings
import numpy as np
import pandas as pd
import seaborn as sns
import opendatasets as od
import matplotlib.pyplot as plt
```

## Autor
> Janiel Santos. - [Github](https://github.com/JanielS) - Maio 2024

