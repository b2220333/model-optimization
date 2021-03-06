**Updated: Aug 7th, 2020**

## Quantization

*   Post training quantization for dynamic-range kernels --
    [Launched](https://blog.tensorflow.org/2018/09/introducing-model-optimization-toolkit.html)
*   Post training quantization for (8b) fixed-point kernels --
    [Launched](https://blog.tensorflow.org/2019/06/tensorflow-integer-quantization.html)
*   Quantization aware training for (8b) fixed-point kernels and experimentation
    for <8b --
    [Launched](https://blog.tensorflow.org/2020/04/quantization-aware-training-with-tensorflow-model-optimization-toolkit.html)
*   [WIP] Post training quantization for (8b) fixed-point RNNs
*   Quantization aware training for (8b) fixed-point RNNs
*   [WIP] Quality and performance improvements to post training dynamic-range
    quantization

## Pruning / Sparsity

*   During-training magnitude-based weight pruning --
    [Launched](https://blog.tensorflow.org/2019/05/tf-model-optimization-toolkit-pruning-API.html)
*   Sparse model execution support in TensorFlow Lite --
    [WIP](https://github.com/tensorflow/model-optimization/issues/173)

## Weight clustering

*   During-training weight clustering

## Cascading compression techniques

*   [WIP] Additional support for combining different compression techniques.
    Today, users can only combine one during-training technique with
    post-training quantization. The proposal is coming soon.

## Compression

*  [WIP] Tensor compression API
