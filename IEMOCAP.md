|model|ACC|F1|mF1|hap ACC/F1|sad  ACC/F1|neu  ACC/F1|ang  ACC/F1|exc  ACC/F1|fru  ACC/F1|
|----|----|----|----|----|----|----|----|----|----|
|论文中baseline|63.5|63.5|63.0|48.3/52.1|68.3/73.3|61.6/58.4|57.5/61.9|68.1/69.7|**67.1**/62.3|
|我跑的baseline|65.74|64.60|64.32|51.22/**57.00**|78.76/75.11|58.17/61.13|63.43/61.36|**77.76**/69.69|62.07/61.68|
|baseline+知识A|66.43|65.51|64.41|52.64/51.58|80.55/75/58|59.91/63.20|64.27/61.41|73.67/68.99|64.39/65.72|
|baseline+知识B|null|null|null|null|null|null|null|null|null|
|baseline+GRU(3LOSS)|65.74|64.81|64.41|55.21/54.76|80.28/76.31|58.73/**76.31**|70.06/62.67|72.24/69.18|60.38/64.08|
|baseline+知识A+GRU(3LOSS)|null|null|null|null|null|null|null|null|null|
|baseline+知识A_B|null|null|null|null|null|null|null|null|null|
|baseline+知识B+GRU(3LOSS)|null|null|null|null|null|null|null|null|null|
|**baseline+知识A_B+GRU(3LOSS)**|**68.20**|**67.29**|**66.36**|**58.18**/54.10|**81.91**/**78.99**|**62.02**/64.72|**70.64**/**63.17**|73.58/**70.62**|64.09/**66.58**|
