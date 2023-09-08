<h1>Deep_Learning_Challenge</h1>

<h1> Overview:</h1>
<p1>
Alphabet Soup is a nonprofit that helps fund organizations. The purpose of the ML model is to predict how successful these organizations are. The bulk of these decisions would help them gain vision and clarity as to what decision would benefit them and make a deeper impact. 
</p1>
<h1> Results </h1>
<bullet>Data Preprocessing </bullet>
  <bullet1> Target variable for this Neural Network IS_SUCCESSFUL </bullet1>
  <bullet2> Features for the model were: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT </bullet2>
  <bullet3> Variables that should be removed: EIN, NAME </bullet3>
<h2> Compiling, Training, and Evaluating the Model <h2>
  <bullet1> Model nn1: Two lawyers were used, 80 and 30 neurons, respectively. The first hidden layer uses ReLU activation, and the second hidden layer uses the hyperbolic tangent (tanh) activation function. This model is simple with a low quantity of neurons used.  </bullet1>
  <bullet2> Model nn2: Three hidden layers were used, 120, 80, and 30 neurons respectively. ReLU activation functions were used in the first and third layers and the tanh activation function was used in the second layer. This one is deeper than the previous one with greater complexity. </bullet2>
  <bullet3> Model nn3: Four hidden layers were used, 300, 100, 50, and 30 neurons respectively. ReLU activation function was used in the first, third, and fourth layers and tanh activation function was used in the second layer. This is so that another layer of complexity is identified within this model. </bullet3>
  <bullet> I was not able to hit the 75% accuracy. However, the steps taken to increase model performance are as follows: increase the number of layers and neurons, adjust the number of different activation functions, but hold EPOCHs at 100. 
  </bullet>
<h3> Summary</h3>
<p1> To improve the performance of the model, one can change the learning rate, and activation functions, or even increase epochs. If the training number of epochs was increased, overfitting would be prevented. To improve the quality of data, one can explore feature engineering as well. Although these models did not hit the 75% accuracy mark, they did land fairly close (73%, 73%, 72.7%). Each time, new hidden layers were added between each of these models to improve accuracy which failed, despite garnering an increase in loss. </p1>
