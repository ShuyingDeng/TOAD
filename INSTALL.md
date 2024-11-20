conda create -n toad python==3.10

conda activate toad

conda install -c conda-forge openslide

pip install timm==0.9.8 torch torchvision h5py pandas PyYAML opencv-python matplotlib scikit-learn scipy tqdm openslide-python tensorboardX -i https://pypi.tuna.tsinghua.edu.cn/simple