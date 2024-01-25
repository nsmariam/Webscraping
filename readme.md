# Projet Webscraping

## Description du projet
Ce projet Python sert a scraper le site web d'Action,
récupère des informations sur les produits de la catégorie habitat, 
et enregistre ces informations au format JSON.


Le code effectue une boucle sur les pages en faisant des requêtes pour récupérer les données de chaque page.\
Il extrait ensuite les détails des produits, tels que la le titre, la description et le prix, 
puis enregistre chaque produit au format JSON dans un dossier "DATA".


#### Modules utilisés
from bs4 import BeautifulSoup\
import requests\
import json\
from typing import List, Dict


#### Auteurs
EL YAOUTI Aya\
N'DIAYE Mariam
