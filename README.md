# hello_world
Just another repository

    standard neural network with python

    def parameters_initializer(lst):
        """
        lst--Number of neurons in each layer（including input layer which is defined layer l=0）
        """
        L = len(lst)
        for l in range(1,L):    #
            parameters['W' + str(l)] = ...
            parameters['b' + str(l)] = ...

        return parameters
