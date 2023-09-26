# TransMUSIC: A Transformer-Aided Subspace Method for DOA Estimation with Low-Resolution ADCs



# Abstract

Direction of arrival (DOA) estimation employing low-resolution analog-to-digital convertors (ADCs) has emerged as a challenging and intriguing problem, particularly with the rise in popularity of large-scale arrays. The substantial quantization distortion complicates the extraction of signal and noise subspaces from the quantized data. To address this issue, this paper introduces a novel approach that leverages the Transformer model to aid the subspace estimation. In this model,multiple snapshots are processed in parallel, enabling the capture of global correlations that span them. The learned subspace empowers us to construct the MUSIC spectrum and perform gridless DOA estimation using a neural network-based peak finder. Additionally, the acquired subspace encodes the vital information of model order, allowing us to determine the exact number of sources. These integrated components form a unified algorithmic framework referred to as TransMUSIC. Numerical results demonstrate the superiority of TransMUSIC over the classic MUSIC algorithm and the state-of-the-art data-driven approach, showing the potential of Transformer-based techniques in DOA estimation.


