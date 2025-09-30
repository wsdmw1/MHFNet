Quick Start Guide
1. Clone the Project

2. Prepare the Dataset
Configure your dataset directory or TXT file according to one of the two datasets. Baidu link: https://pan.baidu.com/s/1wbNaI1nDXQZAU9kQVvhAdQ?pwd=cvka, key: 

3. Install Dependencies
(It is recommended to directly use the YOLOv8 environment that has already been set up on this computer, without the need to download again.)

conda create -n pt121_py38 python=3.8
conda activate pt121_py38

conda install pytorch==1.12.1 torchvision==0.13.1 torchaudio==0.12.1 cudatoolkit=11.3 -c pytorch

pip install -r requirements.txt

pip install -e .

4. Run the Program

python train_RGBT.py --data your_dataset_config.yaml

5. Testing

python val.py

6. Visualization

python plot.py

7. COCO Evaluation

python calcu_uncer.py
