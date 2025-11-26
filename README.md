# CLBMN
# Learning to Navigate Sequential Environments: A Continual Learning Benchmark for Multi-modal Navigation
### Yinduo Xie, Yuenan Zhao, Qian Zhang, Lin Zhang, Teng Li, Wei Zhang*
### School of Control Science and Engineering, Shandong University

## Abstract
Existing works for robot navigation typically focus on performance in specific tasks, overlooking the adaptability of navigation strategies to sequential environments. In this paper, we present CLBMN, a continual learning (CL) benchmark for multi-modal robot navigation, which aims to enhance robots' navigation capabilities in handling sequential tasks. The benchmark is composed of a multi-modal dataset, a CL-based algorithm, and three comprehensive evaluation metrics for CL-based multi-modal navigation. Specifically, we construct a multi-modal dataset with 10,000 samples by collecting images, point clouds, and odometry data from five scenarios, including daytime, nighttime, rainy conditions, highway, and field. Then, we propose an end-to-end navigation framework with momentum update to mitigate catastrophic forgetting across various environments, which provides a baseline approach for CL-based robot navigation. Furthermore, we define three evaluation metrics specifically designed to evaluate the robot's continual navigation performance across different scenarios. Experimental results demonstrate that the proposed benchmark is effective for studying multi-modal continual robot navigation in sequential environments.

## Dataset
The dataset is collected from five scenarios: daytime, nighttime, rainy conditions, highway, and field, comprising a total of 10,000 samples. As shown in the figure below, each sample includes images, point clouds, and odometry data.
<img width="793" height="558" alt="image" src="https://github.com/user-attachments/assets/180f69e1-1800-4f9f-9592-4ba30baf93f0" />

1. Although every effort has been made to ensure accuracy through manual inspection, we (Shandong University, VSISLab) do not accept any responsibility for user-defined biases in the released images. That you include a reference to the MMN Dataset in any work that makes use of the dataset.
2. You agree not to further copy, publish or distribute any portion of the MMN dataset. Except, for internal use at a single site within the same organization it is allowed to make copies of the dataset.
3. The Visual, Sensing and Intelligent System Lab of Shandong University reserves the right to terminate your access to the database at any time.
4. The dataset only collects and summarizes publicly available forum images on the internet for data type annotation. If you feel that any image in this dataset is offensive to yourself or violates your privacy, please contact us (email: info@vsislab.com).

## Overview
<img width="793" height="408" alt="image" src="https://github.com/user-attachments/assets/00f976b6-4caf-42f8-acf5-5394f39bce6c" />
