##kaken  

#data.yamlの中身  
train: C:/kaken/dataset/images/train  # 訓練用画像のパス  
val: C:/kaken/dataset/images/val      # 検証用画像のパス  
  
nc: 2  # クラス数  
names: ['sleep', 'up']  # クラス名（実際のクラス名に変更）  
  
#実行手順  
#python train.py --img 640 --batch 16 --epochs 50 --data data.yaml --weights yolov5s.pt --cache  
  
#カメラで推論  
#python detect.py --weights runs/train/exp?/weights/best.pt --source 0 --conf 0.25  
