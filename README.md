# Tensorflow_HD_models
Contains TF Frozen graph for TVM. 
TF.version = 1.12
Input size = [1,1200,1920,3] (NHWC)

In order to create dummy input placeholder: `input_ = np.random.random_integers(0, 255, input_shape).astype(np.uint8)`

