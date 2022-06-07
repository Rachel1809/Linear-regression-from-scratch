# Linear regression from scratch

This project is carried out in `Google Colaboratory`, with the support of `numpy` library for calculations and `matplotlib.pyplot` as well as `mpl_toolkits.mplot3d` for data visualization. 

This project is simply about the algorithm of linear regression, using MSE loss and gradient descent to find the global minimum to optimze the model which reduces the loss between prediction and true value. 

I have encapsulate the random generation of `x` and `y_true` as well as `weight_true` and `bias_true` inside the class `Model`, so reader don't need to generate it anymore. However, I have return all of it when you call the instances, you can retrieve all of its for comparison or something if you wish.
