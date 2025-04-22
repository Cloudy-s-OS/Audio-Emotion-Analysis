![cloudy_os_banner](https://github.com/user-attachments/assets/02676383-5ea1-4d2a-b018-a3e1c3b767df)
### Introduction:

This project aims to develop and predict the human emotion by their speech (specifically Angry, Frustrated, Happy, Neutral, and Sad) directly from Thai speech audio dataset named THAI SER dataset.

A key focus of this project is to analyze and optimize the computational performance and how we optimize it:
1. A **Standard Sequential Version or First Version:** Processes audio files one by one.
2. An **Optimized Parallel Version or Enchanced Version:** Using (`multiprocessing` by `joblib`) to doing multi-core computation in CPU.

The primary optimization goal is to significantly reduce the execution time of the feature extraction stage by doing parallelizing when running the code and shows that how OS is doing parallelism can enhance the performance in machine learning tasks. Both versions will be compared for computational performance (time, CPU, memory) and predict accuracy of the machine learning.

### Team Members
* 6688077 Bhumipat Pengpaiboon
* 6688108 Napas Siripaskrittakul
* 6688142 Krerkkiat Wattanaporn
