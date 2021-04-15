# pyre-lookout

Run in command line inside the yolov5 folder with:
python detect.py --source ../test/images --weights 'runs/train/yolov5l_best/weights/best.pt' --img 416 --conf 0.5

--source designates the location of images to run detection on
--weights designates the active model

Add --save-txt or --save-img to save text or image output, respectively.