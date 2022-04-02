# Conditional Wasserstein GAN for Synthetic Time Series Generation

Conditional Wasserstein GAN with gradient penalty for the generation of synthetic time series.

## Description

Propriatary dataset was used to train the conditional WGAN with gradient penalty. Any dataset with shape (num_samples, num_features) will work.

Run the cells in sequence in `cwgan-gp_time_series.ipynb` jupyter notebook. Final cell contains code to create synthetic 
image conditioned on a label.

Code in part based on:

* https://keras.io/examples/generative/conditional_gan/
* https://keras.io/examples/generative/wgan_gp/
* https://keras.io/examples/generative/dcgan_overriding_train_step/

## Getting Started

### Dependencies

* tensorflow
* numpy
* matplotlib

See `requirements.txt` file.


## License

Free to use for any purpose