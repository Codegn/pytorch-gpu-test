# Test CUDA with Pytorch

1. conda create -n pytorch_gpu_test python=3.7.4 jupyter
2. conda activate pytorch_gpu_test
3. conda install pytorch torchvision cudatoolkit=10.1 -c pytorch
4. jupyter notebook
5. run 'test_gpu_on_pytorch.ipynb'