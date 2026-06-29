# Adaptive Filtering and Transformers: From Widrow's LMS to the Gradient Circuits of Attention

## Introduction

The modern Transformer architecture is often presented as a breakthrough in deep learning, but its mathematical core — gradient descent and adaptive weight adjustment — has deep roots in signal processing. In the 1960s and 1970s, Bernard Widrow and his colleagues developed the Least Mean Squares (LMS) algorithm, which introduced the concept of adaptive filtering: a system that adjusts its parameters to minimize the error between its output and a desired signal.

In this article, we show that the LMS algorithm and the Transformer share the same mathematical foundation: a quadratic error surface, gradient descent, and a correlation matrix that captures the structure of the input signal. The key difference lies in the scale and the space: Widrow worked with linear filters in the signal domain, while Transformers operate in high-dimensional latent spaces. Yet the principle — adapting a kernel to resonate with incoming data — remains unchanged.

This paper bridges the gap between Widrow's adaptive filtering and the attention mechanism of Transformers, revealing a continuous line of evolution from classical signal processing to modern AI.
