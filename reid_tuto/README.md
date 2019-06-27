For my memo of Person_reID_baseline_pytorch

See https://github.com/layumi/Person_reID_baseline_pytorch  

## Machine info
* Ubuntu 16.04  
* CPU:Intel(R) Core(TM) i7-7700HQ CPU @ 2.80GHz  
* RAM: 32 GB  
* GPU:NVIDIA Quadro M1200 Mobile 4 GB, driver384.130  
* Cuda 9.0  
* cuDNN 7  


## Set up
### Envirionment
Create an environment.  
`conda create --name reid python=3.6 numpy anaconda`
`conda activate reid` 

Install pyrorch (check https://pytorch.org/).  
`conda install pytorch torchvision cudatoolkit=9.0 -c pytorch`  

Install apex  that save GPU memory usin Float16 (check https://github.com/NVIDIA/apex).  
`git clone https://github.com/NVIDIA/apex`  
`cd apex`  
`pip install -v --no-cache-dir ./`  

Install pretrainedmodels (check https://pypi.org/project/pretrainedmodels/).  
`pip install pretrainedmodels`  

### Dataset
Market-1501  
https://jingdongwang2017.github.io/Projects/ReID/Datasets/Market-1501.html  

