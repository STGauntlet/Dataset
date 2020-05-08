# Dataset
The dataset consists of the training set and test set. The training set contains Lie algebra-based motion features collected from six participants (P1-P6). The test set is collected from 3 testers (T1-T3) and is used to verify the performance of our framework.

The Lie algebra-based motion features was calculated by motion sensor data collected from a wearable glove at a sampling rate of 25Hz (file: Train_Lie algebra.csv, Test_Lie algebra.csv).  The file contains 43 columns:
|Index|1-7|8-14|15-21|22-28|29-35|36-42|43|
|--|--|--|--|--|--|--|--|
|**Content**|The motion feaures of opisthenar|The motion feaures of thumb|The motion feaures of index finger|The motion feaures of middle finger|The motion feaures of ring finger|The motion feaures of little thumb|Label|

The motion feaures of each joint: x aixs of displacement, y axis of displacement, z axis of displacement, real element of quaternion, x of complex element of quaternion,  y of complex element of quaternion, z of complex element of quaternion.
For Each Joint Attribute (Lie algebra-based motion features):

**Displacement feature**

X: continuous, time-series

Y: continuous, time-series

Z: continuous, time-series

**Rotation feature**

The real element of quaternion: continuous, time-series

The three complex elements of quaternion: continuous, time-series

**Label**: integer, 8 categories (1: S&B fingers, 2: Circling, 3: B wrist U&D, 4: B wrist L&R, 5: R forearm, 6: Throwing, 7: Drinking, 0: Null)



