|model|ACC|F1|mF1|
|----|----|----|----|
|论文中baseline|63.50|63.50|63.00|
|我跑的baseline|65.27|64.52|64.19|
|baseline+知识消融1+|66.19|65.36|64.64|
|baseline+知识消融2+|66.52|65.88|65.08|
|baseline+知识消融3+|65.86|65.45|64.52|
|baseline+知识消融1_2+|65.84|65.49|64.66|
|baseline+知识消融1_3-|64.76|65.14|64.18|
|baseline+知识消融2_3-|64.99|64.92|64.16|
|baseline+知识消融1_2_3-|64.92|65.07|64.31|
|baseline+知识消融1_2_3+反馈+|65.89|64.66|63.45|
|baseline+1处加知识消融3+|66.23|65.49|64.58|
|baseline+Encoder-|65.15|63.92|63.57|
|baseline+知识消融2+GRU+|67.42|65.80|64.96|
|baseline+1处加知识消融3+GRU(7轮)+|65.41|65.27|64.39|
|baseline+1处加知识消融3_2-|65.07|64.95|63.94|
|baseline+知识消融2(GRU+Attention)+|65.95|65.46|64.90|
|2020ACL+用GRU-|32.08|35.87|30.08|
|baseline+知识消融2+GRU+LSTM+|67.14|65.71|65.09|
|baseline+知识消融2+GRU+GRU+|67.56|66.36|65.45|
|baseline+知识消融2(GRU)+|66.13|65.60|64.91|
|2020ACL+用GRU预测最后一个(预训练)-|27.05|22.61|17.80|
|2020ACL+用GRU预测最后一个(未预训练)-|27.05|22.61|17.80|

