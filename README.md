# Bystander-Detection
## Dependencies

* PyTorch >= 1.0.0
* torchvision >= 0.2.1

## **structure**：

```
  ├── feature
  | ├── pic : store images
  | ├── lable.csv : labeled data
  | ├── pad.py: data generation and data set division
  ├── net
  | ├── train.py :training model
  | ├── predict.py: single image prediction
  | ├── batch_predict.py: batch image prediction
```
