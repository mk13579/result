|model|ACC|F1|mF1|hap ACC/F1|sad  ACC/F1|neu  ACC/F1|ang  ACC/F1|exc  ACC/F1|fru  ACC/F1|
|----|----|----|----|----|----|----|----|----|----|
|论文中baseline|63.5|63.5|63.0|48.3/52.1|68.3/73.3|61.6/58.4|57.5/61.9|68.1/69.7|**67.1**/62.3|
|我跑的baseline|65.84|64.78|64.58|53.90/57.58|80.11/74.45|58.02/60.34|63.54/62.10|77.50/70.76|60.92/62.27|
|baseline+知识A|null|null|null|null|null|null|null|null|null|
|baseline+知识B|null|null|null|null|null|null|null|null|null|
|baseline+GRU|65.74|64.81|64.41|55.21/**54.76**|**80.28**/76.31|58.73/76.31|**70.06**/**62.67**|**72.24**/**69.18**|60.38/64.08|
|baseline+知识A+GRU|null|null|null|null|null|null|null|null|null|
|baseline+知识A_B|null|null|null|null|null|null|null|null|null|
|baseline+知识B+GRU|null|null|null|null|null|null|null|null|null|
|**baseline+知识A_B+GRU**|**68.20**|**67.29**|**66.36**|**58.18**/54.10|81.91/**78.99**|**62.02**/**64.72**|70.64/63.17|**73.58**/**70.62**|64.09/**66.58**|

