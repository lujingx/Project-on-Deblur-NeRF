# Project-on-Deblur-NeRF
Study Deblur-NeRF's mechanism and think.

The results are produced by the code [Deblur-NeRF](https://github.com/limacv/Deblur-NeRF)

[logs_exp](https://github.com/get-through/Project-on-Deblur-NeRF/tree/main/logs_exp) contains the videos, params and testsets (reconstruct from original view) after 200000 iterations, also metrics. The ones labelled full is the result of Deblur-NeRF, and the ones labelled naive is the result of pure NeRF.
Blur5grass is its original dataset, while blurtea and defocus drinks are shot by our own.

[tensorboard_exp](https://github.com/get-through/Project-on-Deblur-NeRF/tree/main/tensorborad_exp) contains the visualization of training loss, training PSNR, and four metrics on testset.

![defocus drinks](https://github.com/get-through/Project-on-Deblur-NeRF/blob/main/logs_exp/defocus%20drinks_full/defocusdrinks_full_spiral_200000_rgb.mp4)
