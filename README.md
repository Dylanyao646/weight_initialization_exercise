# weight_initialization_exercise

In this lesson, you'll learn how to find good initial weights for a neural network. Weight initialization happens once, when a model is created and before it trains. Having good initial weights can place the neural network close to the optimal solution. This allows the neural network to come to the best solution quicker.
Default initialization

Something really interesting is happening here. You may notice that the red line "no weights" looks a lot like our uniformly initialized weights. It turns out that PyTorch has default weight initialization behavior for every kind of layer. You can see that linear layers are initialized with a uniform distribution (uniform weights and biases) in the module source code.

However, you can also see that the weights taken from a normal distribution are comparable, perhaps even a little better! So, it may still be useful, especially if you are trying to train the best models, to initialize the weights of a model according to rules that you define.
