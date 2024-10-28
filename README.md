# Bystander-Detection

Welcome to the repository for our bystander detection project! We provide the code, models, and datasets used in developing bystander-subject classifier. 

## Directory Structure

The repository contains the following main directories:

```
  ├── feature
  | ├── pic : store images
  | ├── lable.csv : labeled data
  | ├── pad.py: data generation and data set division
  ├── net
  | ├── train.py :training model
  | ├── predict.py: single image prediction
  | ├── batch_predict.py: batch image prediction
  ├── dataset
```

## Dependencies

* PyTorch >= 1.0.0
* torchvision >= 0.2.1

## Additional Notes:

- Several models exceed GitHub's 50MB file size limit. To access the full code and models, please download them via the links provided in the feature and net folders.
- Our paper includes four datasets. The images in Dataset1 and Dataset2b are sourced from publicly available datasets or platforms where data can be collected. We provide the complete set of images for these two datasets. You can download them using the links in the Dataset folder.
- Dataset2a and Dataset3 consist of real user photos from social media. In accordance with the Ethics Review Committee guidelines of our institute, the images in these datasets are not publicly available. If you require access, please contact us to request information on how to build these datasets.

## Contributing

If you have suggestions or wish to contribute code, please submit a Pull Request or create an Issue.

## Contact

For any questions or need assistance, please reach out through the following channels:

- Create an Issue
- Email us (Our contact email will be provided at a later date.)
- Visit our coming website

---

Thank you for visiting and showing interest in this project!

