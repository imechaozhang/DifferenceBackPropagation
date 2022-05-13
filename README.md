# DifferenceBackPropagation

Since the proposal of neural network, the derivative-based back propagation algorithm has been
the default setting. However, the derivative for a non-linear function is an approximation for the
difference, and it may be a more precise way to do back propagation using difference instead of
derivative. While no one thinks to make changes to the back propagation algorithm, it may be
the bottleneck in modern deep learning models. With the explosion of big data and large-scale
deep learning models, a tiny change in the back propagation could lead to a huge difference. Here
we propose a new back propagation algorithm based on inverse sigmoid function to calculate the
difference instead of derivative. Restricted by hardware, we only experimented on a small scale to
illustrate the effectiveness
