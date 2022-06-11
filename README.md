# my_fall_detection


Our dataset(we get them from Kaggle) is included in "yolov5-master" file and we begin training by the following codes:

python train.py --weights weights/yolov5l.pt  --cfg models/yolov5l.yaml  --data data/VOC.yaml --epoch 300 --batch-size 2 --img 1200 

Or if you want to use your dataset,you should create a datapath.yaml which include your images' path and write down class_num and other existed ".yaml" files in "~/yolov5-master/data" can be a reference,and yolov5l.yaml too(if you want to use other size model,modify the corresponding file).

If some model's parameters are expected to change,please refer yolov5-master help document.
