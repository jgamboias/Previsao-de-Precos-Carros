# Previsão de Preços de Carros Usados
Usando algoritmos de inteligência artificial, é possível com este script prever a que intervalo de preços pertence um veículo com base nos que existem disponíveis para venda no StandVirtual.

# Funções :
  - Web Scraper:
      Recolhe para um ficheiro csv as características dos automóveis presentes no StandVirtual. Entre elas estão o número de quilómetros, nº de mudanças, nº de portas, nº de lugares, ano e obviamente o preço.
      Quanto mais tempo esta função correr, mais dados estarão disponíveis para os algoritmos de previsão. 
      Notas:
      Colocar sempre no início do .csv o seguinte cabeçalho Marca,Modelo,Ano,Quilometros,Portas,Lugares,Mudancas,Preco
  - Previsão de Preços: 
      Utilizando alguns algortimos disponíveis no sklearn, para efeitos de comparação, este script irá treinar o algoritmo de forma a prever o preço.  
   -Por implementar: Inserindo todas as outras categorias, prever o preço. Apesar de apenas bastar um pouco de conhecimento de csv e alimentar o algorimtmo depois de treinado com todas as colunas preenchidas tirando a última. 
   
 
