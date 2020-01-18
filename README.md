# Graph Convolutional Matrix Completion based on Pytorch
PyTorch and PyTorch geometric based implementation of [Graph Convolutional Matrix Completion](https://arxiv.org/abs/1706.02263).

Using tanimutomo's implementation, there were some mis-implementations so RMSE was about 1.2
I tried to remove errors and use RGCNConv rather than make own layers made RMSE : 0.92 in without features.

### Local
Installation of Pytorch Geometric is difficult and can destroy your local python environment.  
So, if you already installed docker and docker-compose in your machine, recommend to use Docker (above).  
Please see [Pytorch Geometirc document](https://rusty1s.github.io/pytorch_geometric/build/html/notes/installation.html) for more details.  
#### Install requirements
- torch
- torchvision
- comet_ml
- torch-scatter
- torch-sparse
- torch-cluster
- torch-spline_conv
- torch-geometric
