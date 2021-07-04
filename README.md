# pandas_vowpal
Jupyter notebook using Pandas/VW integration to analyse rain gauges data.
The data acquired in the Hidroweb platform, mantained by the brazilian government, which has information from 78 rain gauges in the city of Sao Paulo - Brazil, is combined into one CSV and then as a Pandas dataframe.
After some data mining, the definitive csv is converted using the DFtoVW function.
Using Vowpal Wabbit, a simple model is trained, automatically finding its features, weights and layers.
Finally, a comparison is set up between the real values and the ones predicted by the model.

CREDITS:
Data acquired from the Hidroweb platform:  https://www.snirh.gov.br/hidroweb/apresentacao using this project: https://github.com/duartejr/pyHidroWeb.
Pandas and Vowpal Wabbit integration mainly based on: https://github.com/VowpalWabbit/vowpal_wabbit/blob/master/python/examples/DFtoVW_tutorial.ipynb

