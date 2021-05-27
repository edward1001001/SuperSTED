# SuperSTED
Codes for our paper [Deep adversarial network for super stimulated emission depletion imaging](https://doi.org/10.1117/1.JNP.14.016009)

## Prerequisites
The codes are developed in Python v3.6 with jupyter notebook, and the dependent packages include:
* tensorflow 1.12.0/1.13.1
* numpy 1.17.2
* h5py 2.9.0
* scipy 1.3.1
* scikit-learn 0.20.1
* matplotlib 3.1.1

You also need the parameter file `vgg19.npy` which can be downloaded from [link](https://www.dropbox.com/s/691wtp4oq5ip38p/vgg19.npy) (by [rikardocorp/tensorflow_vgg_train](https://github.com/rikardocorp/tensorflow_vgg_train)).

The file `CPCE_SR.ipynb` is for network training. The file `Test_CPCE_SR.ipynb` is for testing.
The shuffled training data of patch pairs (64 by 64) are stored in 5 `.h5` files (`M0.h5` to `M4.h5`). The validation data during training and the testing data after training are stored in `.mat` files.


## Paper Information
```
Mengzhou Li, Hongming Shan, Sergey Pryshchep, Maria M. Lopez, Ge Wang, "Deep adversarial network for super stimulated emission depletion imaging," J. Nanophoton. 14(1) 016009 (14 February 2020) https://doi.org/10.1117/1.JNP.14.016009
```

```
@article{li2020deep,
  title={Deep adversarial network for super stimulated emission depletion imaging},
  author={Li, Mengzhou and Shan, Hongming and Pryshchep, Sergey and Lopez, Maria M and Wang, Ge},
  journal={Journal of Nanophotonics},
  volume={14},
  number={1},
  pages={016009},
  year={2020},
  publisher={International Society for Optics and Photonics}
}
```
