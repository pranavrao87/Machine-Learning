# Tensors in Machine Learning with TensorFlow
What are Tensors?
In the field of machine learning, tensors are fundamental data structures that are used to represent and manipulate multi-dimensional ("N" dimensions) arrays of numerical values. They are analogous to matrices but can have any number of dimensions, including scalars (0-D tensors), vectors (1-D tensors), matrices (2-D tensors), and higher-dimensional arrays.

## Function and Importance of Tensors
Tensors play a crucial role in machine learning algorithms as they enable the efficient computation and storage of data. They serve as the primary data structure for representing inputs, outputs, and intermediate states during the training and inference processes. Tensors allow for parallel and distributed processing, which is vital for handling large-scale datasets and performing computations on modern hardware, such as GPUs.

## Usage of Tensors in TensorFlow
TensorFlow, a popular open-source machine learning framework, extensively utilizes tensors for its computations. It provides a specialized library for tensor operations, making it easier to perform various mathematical operations on tensors efficiently. TensorFlow offers a high-level interface that allows users to define and manipulate tensors effortlessly.

TensorFlow represents tensors as tf.Tensor objects, which are n-dimensional arrays that store the data values. These tensors can be created from various sources like NumPy arrays, Python lists, or directly generated using TensorFlow operations. Tensors in TensorFlow are immutable, meaning their values cannot be changed once created. However, TensorFlow operations can create new tensors that are modified copies of the original tensors.

## What this section focuses on
This specific folder on the repository focuses on creating tensors in tensorflow using pre-determined values to generating tensors w/ random values. Additionally, these notebooks experiment w/ indexing, getting information, encoding, and manipulating tensors. There is also a dedicated section to matrix multiplication using tensors which is an essential process used by many ML algorithms in modifying and discovering patterns. 


## Conclusion
Tensors are essential building blocks in machine learning, enabling efficient representation, computation, and storage of multi-dimensional data. They are widely used in machine learning frameworks like TensorFlow to perform mathematical operations and facilitate the training and inference processes. Understanding tensors is crucial for effectively working w/ machine learning algorithms and frameworks.





