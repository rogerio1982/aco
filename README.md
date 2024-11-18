![Texto alternativo](https://www.insectlore.com/cdn/shop/articles/iStock-525968315_1600x.jpg?v=1723159302)

O algoritmo tentará encontrar uma solução de percurso que minimiza a distância total, com base nas interações das formigas durante as iterações.

Distância entre as cidades: A função distance(city1, city2) calcula a distância euclidiana entre duas cidades.

Inicialização das cidades: A função initialize_cities(num_cities) cria um conjunto de cidades com coordenadas aleatórias.

Distância total de uma rota: A função total_distance(route, cities) calcula a distância total de uma rota, considerando a volta à cidade inicial.

ACO (Ant Colony Optimization):

As formigas começam em cidades aleatórias e, em cada iteração, escolhem uma nova cidade com base em um cálculo de probabilidades que considera tanto a
quantidade de feromônio nas arestas (para intensificar boas rotas) quanto a visibilidade (1/distância, para incentivar rotas curtas).
O feromônio é atualizado após cada iteração. Há uma evaporação de feromônio (controlada pela constante rho) e uma atualização positiva 
com base nas rotas encontradas pelas formigas, com a intensidade proporcional à qualidade da solução (distância).
Resultados: O algoritmo retorna a melhor rota encontrada e a distância total associada.







