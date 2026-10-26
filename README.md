# Developing a Neural Network Regression Model

## AIM
To develop a neural network regression model for the given dataset.

## THEORY
Explain the problem statement

## Neural Network Model
Include the neural network model diagram.

## DESIGN STEPS
### STEP 1: 

Create your dataset in a Google sheet with one numeric input and one numeric output.

### STEP 2: 

Split the dataset into training and testing

### STEP 3: 

Create MinMaxScalar objects ,fit the model and transform the data.

### STEP 4: 

Build the Neural Network Model and compile the model.

### STEP 5: 

Train the model with the training data.

### STEP 6: 

Plot the performance plot

### STEP 7: 

Evaluate the model with the testing data.

### STEP 8: 

Use the trained model to predict  for a new input value .

## PROGRAM

### Name:Kamlesh Y

### Register Number:212224100029

```python
import torch
import torch.nn as nn
import torch.optim as optim
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import MinMaxScaler
import pandas as pd
input_value = torch.FloatTensor([[16]])


scaled_input = torch.FloatTensor(
    scaler_x.transform(input_value)
)


with torch.no_grad():

    prediction = model(
        scaled_input
    )


print("\nPrediction for Input 16:")
print(prediction.item())



# -----------------------------
# Training Loss Graph
# -----------------------------

plt.figure(figsize=(8,5))


plt.plot(
    range(epochs),
    loss_history
)


plt.xlabel(
    "Iterations"
)

plt.ylabel(
    "Training Loss"
)


plt.title(
    "Training Loss vs Iteration"
)


plt.grid(True)


plt.show()

```

### Dataset Information
Include screenshot of the generated data


<img width="307" height="320" alt="Screenshot 2026-10-26 134915" src="https://github.com/user-attachments/assets/f7941ce3-346f-44ea-907e-a2ba457d0eeb" />

### OUTPUT

### Training Loss Vs Iteration Plot
Include your plot here


<img width="705" height="469" alt="1b189191-df4e-47a9-bac5-7f46dc3df85c" src="https://github.com/user-attachments/assets/4a34c81b-5c15-44bd-8e50-fbc43adf1363" />

### New Sample Data Prediction
Include your sample input and output here


<img width="382" height="373" alt="Screenshot 2026-10-26 135032" src="https://github.com/user-attachments/assets/89bcc9ca-a3f3-433a-8e0f-5807ff69f9cb" />


## RESULT
Thus, a neural network regression model was successfully developed and trained using PyTorch.
