# Mapas Interativos Folium-chuva/Folium-Google Engine

Mapa interativo utilizando os dados do pluviometro CEMADEN (Centro Nacional de Monitoramento e Alertas de Desastres Naturais), explicação mais detalhada pode ser encontrada no meu Medium https://vlsantos5938.medium.com/criando-mapas-meteorol%C3%B3gicos-interativos-usando-a-biblioteca-folium-5a95b4655924

Requisitos: 
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
from matplotlib.colors import BoundaryNorm
from scipy.interpolate import griddata  
import numpy.ma as ma
import folium
from folium.plugins import HeatMap



Mapa interativo do Rio Grande do Sul.
![image](https://github.com/vlsantos-bit/Folium-mapa-chuva/blob/master/mapa_int_RS.png)

Cidade de Porto Alegre, RS.
![image](https://github.com/vlsantos-bit/Folium-mapa-chuva/blob/master/Port_Alegr_RS.png)
