The phrase "Saving a TensorFlow model" typically means one of two things:  

1. Checkpoints  
2. SavedModel  

Checkpoints capture the exact value of all parameters (tf.Variable objects) used by a model. Checkpoints do not contain any description of the computation defined by the model and thus are typically only useful when source code that will use the saved parameter values is available.  

The SavedModel includes a serialized description of the computation defined by the model in addition to checkpoint. Models in this format are independent of the source code that created the model. 
