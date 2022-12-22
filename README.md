# Multiple-scattering simulator-trained neural network for intensity diffraction tomography

Abstract: Recovering 3D phase features of complex biological samples traditionally sacrifices
computational efficiency and processing time for physical model accuracy and reconstruction
quality. Here, we overcome this challenge using an approximant-guided deep learning framework
in a high-speed intensity diffraction tomography system. Applying a physics model simulatorbased
learning strategy trained entirely on natural image datasets, we show our network can
robustly reconstruct complex 3D biological samples. To achieve highly efficient training and
prediction, we implement a lightweight 2D network structure that utilizes a multi-channel input for
encoding the axial information. We demonstrate this framework on experimental measurements
of weakly scattering epithelial buccal cells and strongly scattering C. elegans worms. We
benchmark the network’s performance against a state-of-the-art multiple-scattering model-based
iterative reconstruction algorithm. We highlight the network’s robustness by reconstructing
dynamic samples from a living worm video. We further emphasize the network’s generalization
capabilities by recovering algae samples imaged from different experimental setups. To assess
the prediction quality, we develop a quantitative evaluation metric to show that our predictions
are consistent with both multiple-scattering physics and experimental measurements.
