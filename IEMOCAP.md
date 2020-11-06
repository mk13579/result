|model|ACC|F1|mF1|hap ACC/F1|sad  ACC/F1|neu  ACC/F1|ang  ACC/F1|exc  ACC/F1|fru  ACC/F1|
|----|----|----|----|----|----|----|----|----|----|
|论文中baseline|63.5|63.5|63.0|48.3/52.1|68.3/73.3|61.6/58.4|57.5/61.9|68.1/69.7|**67.1**/62.3|
|我跑的baseline|null|null|null|null|null|null|null|null|null|
|baseline+知识A|null|null|null|null|null|null|null|null|null|
|baseline+知识B|null|null|null|null|null|null|null|null|null|
|baseline+GRU|66.06|65.03|64.81|55.46/**54.99**|**82.14**/77.90|58.71/58.04|**71.31**/**63.74**|**72.86**/**69.40**|59.47/64.75|
|baseline+知识A+GRU|null|null|null|null|null|null|null|null|null|
|baseline+知识A_B|null|null|null|null|null|null|null|null|null|
|baseline+知识B+GRU|null|null|null|null|null|null|null|null|null|
|**baseline+知识A_B+GRU**|**68.20**|**67.29**|**66.36**|**58.18**/54.10|81.91/**78.99**|**62.02**/**64.72**|70.64/63.17|**73.58**/**70.62**|64.09/**66.58**|

