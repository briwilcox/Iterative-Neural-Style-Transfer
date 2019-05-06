# Iterative-Neural-Style-Transfer
Tensorflow implementation of neural style transfer as proposed by Gatys et al.in the paper <a href="http://arxiv.org/abs/1508.06576">A Neural Algorithm of Artistic Style</a>

Sharing a simplified implementation of the style transfer algorithm. Code has been written and executed on GoogleCollab.

The below examples have been generated with 1000 iterations of Adam Optimizer (lr=5.0) with content (_&alpha;_) and style (_&beta;_) weights set to 1e1 and 1e-2 respectively.
The original paper mentioned that the ratio _&alpha;_/_&beta;_ was set to 1e-3, 1e-4 or 1e-5 but somehow I was not able to achieve good results with it.

Size of images ranged from 320x320 to 512x512 and took roughly 45-60 mins to train.

Different hyperparameter settings can be appropriate for different sets of images.

## Examples

### Style Images

<p align="center">
<img src="images/style/cubist.jpg" width="280" height="280"/>
<img src="images/style/starry_night.jpg" width="280" height="280"/>
<img src="images/style/patterned_leaves.jpg" width="280" height="280"/>
</p>

### Generated Images

<p align="center">
<img src="images/cubist_style_transfers/building-cubist_1000.jpg" width="280" height="280"/>
<img src="images/starry_night_style_transfers/building-starry_night_1000.jpg" width="280" height="280"/>
<img src="images/patterned_leaves_style_transfers/building-patterned_leaves_1000.jpg" width="280" height="280"/>
</p>


