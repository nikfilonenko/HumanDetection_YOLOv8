# About the project ***`HumanDetection_YOLOv8`***

#
# Table of contents (Оглавление)
1. [**A little bit about the dataset**](#01)
2. [**The result of the trained model - YOLO8 Medium custom**](#02)
3. [**The result of the trained model - `Fine-tuning` YOLO8 Medium custom**](#03)
4. [**Conclusion**](#04)
#

## `01.` A little bit about the dataset <a name="01"></a>
- This dataset was created by extracting `frames` from `12 short videos`. To enrich this data collection with a variety of images, such as blurry images, small-sized images, and others, it was decided to use the unmarked data set available on Kaggle. 

- **After the required number of frames was obtained, all images were annotated using the [`Roboflow platform`](https://roboflow.com/).**

## `02.` The result of the trained model - YOLO8 Medium custom <a name="02"></a>

### Training model
![1 train без fine tune](https://github.com/nikfilonenko/HumanDetection_YOLOv8/assets/103507130/14283836-e761-4352-a65e-e07f14e7e773)
![2 train без fine tune](https://github.com/nikfilonenko/HumanDetection_YOLOv8/assets/103507130/5255fa3c-9c6d-4610-ae39-a63c989943b6)

### Model Validation
![image](https://github.com/nikfilonenko/HumanDetection_YOLOv8/assets/103507130/28fb9314-6431-4844-8df5-77f1151a49e8)

### Predict on images
![1 без fine tune](https://github.com/nikfilonenko/HumanDetection_YOLOv8/assets/103507130/d20790af-7a30-49d2-991f-cecc863978ce)
![2 без fine tune](https://github.com/nikfilonenko/HumanDetection_YOLOv8/assets/103507130/585c4b6c-4d09-450d-ba16-c34ab5d08131)
![3 без fine tune](https://github.com/nikfilonenko/HumanDetection_YOLOv8/assets/103507130/3e93155a-5198-4997-9636-d6505858c974)
![без fine tune](https://github.com/nikfilonenko/HumanDetection_YOLOv8/assets/103507130/91abbf56-06c5-42a6-b5e0-c7017acdb623)

### Predict on video
![output(video-cutter-js com) (1)](https://github.com/nikfilonenko/HumanDetection_YOLOv8/assets/103507130/196d82ad-dc29-4440-9fc7-64bcd55f1ab9)

## `03.` The result of the trained model - `Fine-tuning` YOLO8 Medium custom <a name="03"></a>

### Training model
![1 train с fine tune](https://github.com/nikfilonenko/HumanDetection_YOLOv8/assets/103507130/932d1d0e-73b8-4661-b509-5583d0de2262)
![2 train с fine tune](https://github.com/nikfilonenko/HumanDetection_YOLOv8/assets/103507130/15e0106e-f49c-460c-9955-001ac8c53c34)

### Model Validation
![2 val с fine tune](https://github.com/nikfilonenko/HumanDetection_YOLOv8/assets/103507130/a21bc6f0-c41c-4cc7-93ae-bfb14cee430f)

### Predict on images
![1 с fine tune](https://github.com/nikfilonenko/HumanDetection_YOLOv8/assets/103507130/1f750dd8-c5e4-4d68-ae0c-2e0d960e1db0)
![2 с fine tune](https://github.com/nikfilonenko/HumanDetection_YOLOv8/assets/103507130/42f572b6-f721-428f-8aa2-cd5cdc758f11)
![3 с fine tune](https://github.com/nikfilonenko/HumanDetection_YOLOv8/assets/103507130/e073cedc-93aa-480a-b7c9-2b3b99cf820b)

### Predict on video
![_-fine-tune](https://github.com/nikfilonenko/HumanDetection_YOLOv8/assets/103507130/7e30bfed-13fe-4b95-afff-5ea3bb3af104)

### `04.` Conclusion <a name="04"></a>
**As you can see, a trained model using fine tuning shows better results. Does not make mistakes when detecting an object, as it happens with a model without fine tuning**

