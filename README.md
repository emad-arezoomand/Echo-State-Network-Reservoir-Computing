# Echo-State-Network-Reservoir-Computing
Echo State Network is a single layer, recurrent neural network (reservoir). 

it trains weights of a readout (linear) neuron to produce the output, with inputs beeing the states of the reservoir neurons.

because of the recurrent nature of the model, it has information from previous states. 

this model can be used with feedback from the output (readout) node, which is autoregressive moving average model OR it can be used without feedback which is only a moving average model. 

this code is the implementation of the paper echo state network by jaeger, you can access the paper at https://scholar.google.com/citations?view_op=view_citation&hl=en&user=0uztVbMAAAAJ&citation_for_view=0uztVbMAAAAJ:u5HHmVD_uO8C
