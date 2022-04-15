# Machine-Tool-Wear-RUL

Machine Tool Wear Regression Model using LSTM and GRU Neural Networks.

**Data Reference:** 2010 PHM Data Callenge

**Paper Reference:**
  1. Multi‐Scale Convolutional Gated Recurrent Unit Networks for Tool Wear Prediction in Smart Manufacturing by Weixin Xu, Huihui Miao, Zhibin Zhao, Jinxin Liu, Chuang Sun and Ruqiang Yan.
  2. A hybrid information model based on long short‐term memory network for tool condition monitoring by Weili Cai, Wenjuan Zhang, Xiaofeng Hu, Yingchao Liu.

**Data Description:**
  Tool wear data is obtained from public dataset of PHM 2010 Data Challenge. The data contains time series data of six end mill (6mm 3-flute) cutters. These end mills were machined using a high-speed CNC machine under dry milling condition. Seven Time Series data of Force in XYZ direction, Vibrations in XYZ direction and Acoustic Emission data were obtained.
  
The 6mm end mill was machined line by line with an axial depth of cut of 0.2mm and radial depth of cut of 0.125 mm on a workpiece till the whole surface was machined. Then the tool was removed and its wear was measured under a microscope. Then again it was machined with the above parameters and wear was measured. These cutting tests were done for 315 times. A total of 315 files are present for each cutter with recordings of 315 wear values.

A dynamometer was used to get the cutting forces obtained in the XYZ Direction during machining. An accelerometer was used to get the vibrations obtained in the XYZ direction during machining. An Acoustic Emission Sensor was used to get the acoustic data emitted during machining. In this project, data of cutter C1, C4 and C6 were used.

**Methodology**:
  1. GRU and LSTM models were built on the methodology described in the paper.
  2. C1 and C4 data were used as training set and C6 was used as the testing set.
