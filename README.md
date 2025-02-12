# CIENCIA_DADOS

Desafio de Ciência de Dados da Lighthouse. Meu arquivo documenta todo o passo a passo da minha solução.

O modelo de regressão linear foi salvo no arquivo .pkl. Para utilizá-lo, basta carregar o modelo e seguir este formato para a entrada de dados:


teste = {'id': [259],
 'nome': ['Skylit Midtown Castle'],
 'host_id': [2845],
 'host_name': ['Jennifer'],
 'bairro': ['Midtown'],
 'latitude': [40.75362],
 'longitude': [-73.98377],
 'minimo_noites': [1],
 'numero_de_reviews': [45],
 'ultima_review': ['2019-05-21'],
 'reviews_por_mes': [0.38],
 'calculado_host_listings_count': [2],
 'disponibilidade_365': [355],
 'bairro_group_Brooklyn': 0,
 'bairro_group_Manhattan': 1,
 'bairro_group_Queens': 0,
 'bairro_group_Staten Island': 0,
 'room_type_Private room': 0,
 'room_type_Shared room': 0}

 

Os valores 1 representam True, e 0 representam False.
Além disso, antes de realizar previsões, os valores numéricos devem ser normalizados seguindo os mesmos padrões do banco de dados original.

Todas as informações necessárias para replicar o processo estão disponíveis no arquivo principal .ipynb.
