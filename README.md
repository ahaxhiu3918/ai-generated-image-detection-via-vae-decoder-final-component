# ai-generated-image-detection-via-vae-decoder-final-component

This works tries to implement the first model of this paper **"Liu, Yanzhu & Liu, Xiao & Wang, Yuexuan & Soumik, Mondal. (2026). Exploiting the Final Component of Generator Architectures for AI-Generated Image Detection. 10.48550/arXiv.2601.20461."**

2 notebooks are proposed : one for the contamination of the images and the training of the VAE decoder final component binary detector, and the other for the inference of the saved "detector.pth" detector moodel for the binary classification. The "detector.pth" can be created by the first notebook.

Future work would be to : 1.Fine-tune the dinov3 backbone with a small learning rate of 5.10**(-7) & 2. to implement the 3 other models of the paper.

For improvements, one can think of trying different backbones.
