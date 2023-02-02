<div>

## <div align="center">Modification for Yolo</div>


Using F1 score to decide the current best model: fitness() in utils/metrics.py

Using IoU instead of CIoU in utils/metrics.py and utils/segment/metrics.py

Making the detection result csv instead of txt in detect.py and val.py
  
Output and store the TP, FP and FN numbers in val.py
  
Set the default threshold consistant as detect.py in val.py 


</div>
