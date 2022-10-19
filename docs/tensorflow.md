# Tensorflow

## What is tensorflow?
- End-to-End platform for ML
- Write fast DL code in python or any other accessible languages (able to run GPU/TPU)
- Able to access many pre-built DL models through <b>Tensorflow Hub</b>, either to leverage them to build new models or use directly for an application.
- Whole stack: 
    - preprocess data
    - model data
    - deploy model in your application
- Originally designed and used in-house by Google.

## Why tensorflow?
- Easy model building
- Robust ML production anywhere
- Powerful experimentation for research

(put the pic from tensorflow website)


## What are TPUs?
TPUs are hardware accelerators specialized in deep learning tasks.

## What is a tensor?
A n-dimension matrix.

## Tensor attributes
<table border=1>
    <tr>
        <th><b>Attribute</b></th>
        <th><b>Definition</b></th>
        <th><b>Code</b></th>
    </tr>
    <tr>
        <td>Shape</td>
        <td>The length (number of elements) of each of the dimension of a tensor.</td>
        <td><code>tensor.shape</code></td>
    </tr>
    <tr>
        <td>Rank</td>
        <td>The numebr of tensor dimensions.
            <br>Scalar has rank 0. 
            <br>Vector has rank 1. 
            <br>Matrix has rank 2. 
            <br>Tensor has rank n 
        </td>
        <td><code>tensor.ndim</code></td>
    </tr>
    <tr>
        <td>Axis or dimension</td>
        <td>A particular dimension of a tensor</td>
        <td><code> tensor[0], tensor[:, 1]...</code></td>
    </tr>
    <tr>
        <td>Size</td>
        <td>The total number of elements in the tensor</td>
        <td><code>tf.size(tensor)</code></td>
    </tr>
</table>