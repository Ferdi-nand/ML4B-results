# ML4B-results
A collection of the data created during our ML4B project.

# Image sources
The "extracted" directory contains 1000 images of grapes processed by us from the [Embrapa Wine Grape Instance Segmentation Dataset](https://github.com/thsant/wgisd). The exact steps for processing can be found in [this Google Colab notebook](https://colab.research.google.com/drive/1QmoeBVebIoKtN-uDUacPTcEl_4Um_7Sj?usp=sharing). Please note that the actual processing generated over 4000 images, but GitHub enforces a limit of 1000 images maximum per directory. The full collection with all generated images is available in the [extracted.zip](https://github.com/Ferdi-nand/ML4B-results/blob/main/extracted.zip) file.

The "generated" directory contains 1000 images of grapes that we generated using a neural network and the [StyleGAN2 program from NVlabs](https://github.com/NVlabs/stylegan2). We trained the neural network with images from the "extracted" directory. Our trained network is too large to upload to GitHub, but can be downloaded [here](https://1drv.ms/u/s!As35dOeUoSwbagG_yia5211BaCQ?e=ZyNSw9). It is a .pkl file ready to be used with StyleGAN2.

# License information

The images in [/extracted/](https://github.com/Ferdi-nand/ML4B-results/tree/main/extracted) and [extracted.zip](https://github.com/Ferdi-nand/ML4B-results/blob/main/extracted.zip) are a derivative of ["Embrapa WGISD"](https://github.com/thsant/wgisd) by Embrapa Agricultural Informatics, maintained by [Thiago Santos](https://github.com/thsant) used under [Creative Commons BY-NC 4.0 (Attribution-NonCommercial 4.0 International license)](https://creativecommons.org/licenses/by-nc/4.0/). These images are licensed under [Creative Commons BY-NC 4.0 (Attribution-NonCommercial 4.0 International license)](https://creativecommons.org/licenses/by-nc/4.0/) by Albin Lokaj and Ferdinand Eckl. (Attribution according to [best practices](https://wiki.creativecommons.org/wiki/Best_practices_for_attribution#This_is_a_good_attribution_for_material_from_which_you_created_a_derivative_work))

The images in [/generated/](https://github.com/Ferdi-nand/ML4B-results/tree/main/generated) are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) by Albin Lokaj and Ferdinand Eckl.
