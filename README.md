# Building-Deep-Neural-Network-Step-by-Step
Building your own deep neural network from scratch.
To build your neural network, you will be implementing several "helper functions". These helper functions will be used in the next assignment to build a two-layer neural network and an L-layer neural network. Each small helper function you will implement will have detailed instructions that will walk you through the necessary steps. Here is an outline of this assignment, you will:

   1. Initialize the parameters for a two-layer network and for an $L$-layer neural network.
   2. Implement the forward propagation module (shown in purple in the figure below).
        -> Complete the LINEAR part of a layer's forward propagation step.
        
        -> We give you the ACTIVATION function (relu/sigmoid).
        
        -> Combine the previous two steps into a new [LINEAR->ACTIVATION] forward function.
        
        -> Stack the [LINEAR->RELU] forward function L-1 time (for layers 1 through L-1) and add a [LINEAR->SIGMOID] at the end      (for the final layer $L$). This gives you a new L_model_forward function.
    
    3.Compute the loss.
    
    4.Implement the backward propagation module (denoted in red in the figure below).
        -> Complete the LINEAR part of a layer's backward propagation step.
        
        -> We give you the gradient of the ACTIVATE function (relu_backward/sigmoid_backward)
        
        -> Combine the previous two steps into a new [LINEAR->ACTIVATION] backward function.
        
        -> Stack [LINEAR->RELU] backward L-1 times and add [LINEAR->SIGMOID] backward in a new L_model_backward function
    5.Finally update the parameters.

