# CSCMOT
CSCMOT
conda create -n CSCMOT
conda activate CSCMOT
conda install pytorch==1.7.0 torchvision==0.8.0 cudatoolkit=10.2 -c pytorch
cd ${CSCMOT_ROOT}
pip install cython
pip install -r requirements.txt
