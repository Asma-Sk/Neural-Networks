# Neural-Networks Shaik Asma Sonu - 700758269

1 Sol:

This script will:
Create a random (4, 6) tensor.
Print its rank and shape.
Reshape it into (2, 3, 4) and then transpose it to (3, 2, 4).
Broadcast a (1, 4) tensor to match (3, 2, 4) and perform addition.
Explain how broadcasting works in TensorFlow.

2 Sol:

This Python script implementing your task using TensorFlow and Matplotlib. It:

Defines y_true (true values) and y_pred (model predictions).
Computes Mean Squared Error (MSE) and Categorical Cross-Entropy (CCE) losses.
Slightly modifies predictions and checks how the loss values change.
Plots a bar chart comparing MSE and CCE loss values.

3 Sol:

This Python script to train an MNIST model using both Adam and SGD optimizers, then compare their accuracy trends with Matplotlib. 
Steps:
Loads the MNIST dataset.
Trains two models: one with Adam and another with SGD.
Compares training and validation accuracy using Matplotlib.

4 Sol :

This Python script to train a neural network on the MNIST dataset while logging metrics to TensorBoard.
Steps:
Loads and preprocesses the MNIST dataset.
Trains a simple neural network while logging to TensorBoard.
Launch TensorBoard to visualize accuracy and loss trends.

4.1 Sol :

1. Patterns in Training and Validation Accuracy Curves
If the model is learning well: Both training and validation accuracy should increase steadily and converge.
If overfitting occurs: Training accuracy will keep increasing while validation accuracy plateaus or even drops.
If underfitting occurs: Both training and validation accuracy will remain low and improve slowly.

2. Using TensorBoard to Detect Overfitting
Compare training and validation loss: If validation loss starts increasing while training loss keeps decreasing, it's a sign of overfitting.
Monitor accuracy trends: If training accuracy is significantly higher than validation accuracy, the model might be memorizing instead of generalizing.
Check weight histograms: Overfitting models often have weight values that grow large, which can be seen in TensorBoard's histograms and distribution tabs.

3. Effect of Increasing the Number of Epochs
For well-regularized models: More epochs can improve performance as the model converges.
For overfitting models: After a certain point, validation accuracy will drop while training accuracy continues to increase.
For underfitting models: More epochs might help, but if the model is too simple, increasing epochs alone won't solve the issue.


