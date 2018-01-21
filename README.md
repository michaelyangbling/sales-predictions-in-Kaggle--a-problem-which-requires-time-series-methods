# sales-predictions-in-Kaggle--a-problem-which-requires-time-series-methods
Due to time limit, only utilized some time-series  methods and the accuracy result just ranked about top 20% in Kaggle. 
Please note Pandas is slow in some complex operation( during using time-series  methods). 
So here I coded C in python to enhance the perforamce.
Writing  C code instead of Pandas operations was as least 100 times faster in my test, 
Even using C in python to generate time-series data took about  6 minute per time-window column, 
Considering many kinds of time-windows to use, and considering future other complex operations,  writing C in Python is a good performance enhancement method
