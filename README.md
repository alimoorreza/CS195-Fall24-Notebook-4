# CS195-Fall24-Notebook-4
## Underwater Animal Detection

<b>Due</b>: Wednesday, November 6th, 2024

For this assignment, you'll use the Underwater Animal Detection Dataset (UWSDet_v1), which has been provided and is also available on Blackboard for the CS195 course. This is a single-class detection task, requiring you to detect the presence of an underwater animal in the image (from the following four categories: dolphins, seals, sharks, and whales) and provide the rectangular bounding box where the animal is located within the image. Your goal is to fine-tune two deep neural network-based detectors, such as Faster R-CNN and Mask R-CNN, using this dataset.
![Underwater Animal Categories](https://github.com/alimoorreza/CS195-Fall24-Notebook-3/blob/main/etc/uws_v1_samples.png)


## Notebook:
You should use these two notebooks for two experiments: 
    * [_Notebook_4_starter for Faster R-CNN_](https://github.com/alimoorreza/CS195-Fall24-Notebook-4/blob/main/cs195_notebook4_faster_rcnn_starter.ipynb).
    * [_Notebook_4_starter for Mask R-CNN_](https://github.com/alimoorreza/CS195-Fall24-Notebook-4/blob/main/cs195_notebook4_mask_rcnn_starter.ipynb).

## Expectations: ☑️
You need to create a Colab notebook starting from here [_Notebook_3_starter notebook_](https://github.com/alimoorreza/CS195-Fall24-Notebook-3/blob/main/cs195_notebook3_starter.ipynb), then add your code and results to document your experiment. Most importantly, you will use text cells in the notebook to explain what you did, interpret the results, and make your recommendations. The written markdown protions must include the following things:
1. **Data, Evaluation Metric, Optimizer, Hyper-parameters** [2 points]: Write the names and values for the following: 
    - __Total number of samples__: total number of examples you have in the dataset
    - __Total number of training samples__: total number of examples you have in the training split of the dataset
    - __Total number of testing samples__: total number of examples you have in the testing split of the dataset
    - __Number of classes__: total number of categories in the dataset
    - __Metrics__: metrics you used to evaluate your model
    - __Optimizer__: learning algorithms you tried and which important hyper-parameters you tuned.
2.  **Results** [2.5 point]: After you conduct your learning experiment, summarize the results you got. Include visualizations as appropriate. More explicitly, you should fill in the following table:

| **Model**                        |**Best epoch** |**Best performance** |**Best optimizer** 
| :------------------------------- | ------------: | ------------: | ------------: |
| 1: AlexNet                       |               |               |               |
| 2: VGG16                         |               |               |               |
| 3: ResNet18                      |               |               |               |
| 4: ResNet50                      |               |               |               |
| 5: ResNet152                     |               |               |               |

📉 📊 📈 💹 You also should include **visualizations (graphs)** of tuning parameters eg, _loss curves_, _accuracy curves_, _confusion matrices_.

3.  **Conclusions** [0.5 point]: What insights/recommendations do you have? What did you find that was interesting? Which model was your best model? Why do you think models are giving excellent results from the first epoch? Do you need too many epochs to find your best? Why or why not? In general, I want a discussion of your experiment, the results, and what they mean.


### Your Experiments should demonstrate the following well-established and effective convolutional neural networks (CNNs):
- **AlexNet**
- **VGGNet**
- **ResNet18**
- **ResNet50**
- **ResNet152**


### Rubric:
> *This assignment is worth 5 points. It will be graded using the following rubric. I strongly suggest evaluating your project using this rubric before turning it in. It consists of two criteria: 1) *writing (2.5 points)*, and 2) *code (2.5 points)*. The details of the rubrics are as follows:

| Exercise #  | Points Awarded (out of 5)  | Notes |
| --------- | ------------------- | --------- |
| 1: Data, Evaluation Metric, Optimizer, Hyper-parameters          |    -/2.0    |            |
| 2: Results                                                       |    -/2.5    |            | 
| 3: Conclusions                                                   |    -/0.5    |            | 
| <b>Total                                                         |    -/5      |     </b>   |

