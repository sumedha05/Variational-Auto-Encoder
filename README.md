# Variational-Auto-Encoder

Dimensionality Reduction: Dimensionality reduction is the process of reducing the number of features that describe some data. The selection is done eitherby selection or by ex
-traction and can be useful in situations that require low dimensional data. First, let’s call encoder the process that produce the “new features” representation from the “old 
features” representation (by selection or by extraction) and decoder the reverse process. Dimensionality reduction can then be interpreted as data compression where the encoder 
compress the data (from the initial space to the encoded space, also called latent space) whereas the decoder decompress them.

A variational Autoencoder is an encoder whose training is regu;arised to avvoid overfitting and ensure thta the latent space has good properties that enable generative process.
In a nutshell, a VAE is an autoencoder whose encodings distribution is regularised during the training in order to ensure that its latent space has good properties allowing us 
to generate some new data.
