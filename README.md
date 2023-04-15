# F_MODEL

## For .sav

```
import pickle

filename = 'linear_regression_model.sav'
loaded_model = pickle.load(open(filename, 'rb'))

loaded_model.predict([[3]])
```



## For .pkl

```
import pickle

with open('my_model.pkl', 'rb') as file:
    my_model = pickle.load(file)

my_model.predict([[3]])
```
