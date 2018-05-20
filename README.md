# scrapy_ml_real_estate
Extract properties information from real state ads on Mercado Libre

# Run

## Create virtual env
`python3 -m venv venv`

## Install dependencies
`pip install -r requirements.txt`

## Scrap
Running `scrapy crawl properties -o properties.json` will save results to properties.json

Example output:

    {"Cocheras disponibles": "61", "address": "Yatay 237, Almagro,  Capital Federal", "Bodegas disponibles": "30", "Unidades totales": "35", "Departamentos por piso": "6", "price": "U$S 59.000", "url": "https://departamento.mercadolibre.com.ar/MLA-712542236-emprendimiento-terrazas-de-yatay-i-i-yatay-237-_JM", "Pisos": "7", "Entrega": "Preventa", "Torres": "2", "Fecha de entrega": "Noviembre 2019"},
    
    {"Tipo de departamento": "Departamento", "Disposici\u00f3n": "Interno", "Departamentos por piso": "3", "Ambientes": "3", "Expensas": "1100", "Dormitorios": "2", "address": "Estados Unidos 2700, Almagro,  Capital Federal", "Antig\u00fcedad": "30 a\u00f1os", "price": "U$S 135.000", "url": "https://departamento.mercadolibre.com.ar/MLA-721995404-departamento-venta-almagro-3-amb-bajas-expensas-_JM", "Superficie total": "80 m\u00b2", "Pisos": "3", "Ba\u00f1os": "1", "Orientaci\u00f3n": "Oeste", "Superficie cubierta": "80 m\u00b2"}

