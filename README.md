# deep-learning-challenge

# **Neural Network Model Report**

## **Overview**

#### The goal of this analysis is to build a tool that can help predict which organizations have the best chances of being successful. 

## **Results**

### Data Processing:
  * Target Variable: IS_SUCCESSFUL
  * Features: All variables except EIN and NAME
  * Removed Variables: EIN and NAME

### Compiling, Training, and Evaluating the Model:
  * Neurons, Layers, and Activation Functions:
    * Input Layer: 80 neurons with ReLU
    * Hidden Layer: 30 neurons with ReLU
    * Output Layer: 1 neuron with Sigmoid
  * Model Performance:
    * The model was not able to achieve target performance with an accuracy performance of 73% with 56% loss on the test data
  * Optimization Attempt:
    * Input Layer: 100 neurons with ReLU
    * Hidden Layer: 30 neurons with ReLU
    * Addition Hidden Layer: 10 neuron with Relu
    * Output Layer: 1 neuron with Sigmoid
  * Optimized Model Performance:
    * The optimized model was able to achieve target performance with an accuracy score of 80% with 46% loss

### **Summary**

#### The model performed reasonably well and the optimization attempts significantly improved the model’s performance, achieving the desired accuracy target. The adjustments to the number of neurons and layers were crucial in enhancing the model’s predictive ability, but further optimization could include trying a different model like Random Forest.
