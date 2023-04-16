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

## For vehical.pkl

```

import pickle

with open('vehical.pkl', 'rb') as file:
    model = pickle.load(file)

# Prepare the input data

[['weights','goods'], ['weights','goods']]

input_data = [[30,1], [2,20]]

# Make a prediction
predicted_labels = model.predict(input_data)

# Interpret the prediction
for i in predicted_labels:
  if i == 1:
    print('car')
  elif i == 2:
    print("truck")


```
