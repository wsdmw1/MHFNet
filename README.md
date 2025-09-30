Quick Start Guide
1. Clone the Project and Unzip

2. Prepare the Dataset
  Configure your dataset directory or TXT file according to one of the two datasets. Baidu link: https://pan.baidu.com/s/1wbNaI1nDXQZAU9kQVvhAdQ?pwd=cvka, key: cvka

3. Install Dependencies
  (It is recommended to directly use the YOLOv8 environment，but need to download the pakeage of DCNv4.)

  install pytorch

  pip install -r requirements.txt

  pip install -e .

4. Run the Program

  python train_RGBT.py --data your_dataset_config.yaml (our config is ultralytics\models\v8-RGBT\yolov8-RGBT-FAFM.yaml)

5. Testing

  python val.py

6. Visualization

  python plot.py

7. COCO Evaluation

  python calcu_uncer.py (our final result is postprocess\predictions.json)
