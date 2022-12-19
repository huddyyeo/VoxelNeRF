# Voxel NeRF - an amalgamation of NeRF tricks
Implemented a tiny replica of [Direct Voxel Grid Optimisation](https://arxiv.org/abs/2111.11215), along with some other changes. Helper functions including data loading are taken from [here](https://github.com/airalcorn2/pytorch-nerf) but have been modified to include more functionality.

Changes are:

1) Trilinear interpolation grid sampling, for points along the ray
2) Swapping standard NeRF positional encoding for the [Neural tangent kernel](https://bmild.github.io/fourfeat/index.html)
3) Shifted softplus trick



