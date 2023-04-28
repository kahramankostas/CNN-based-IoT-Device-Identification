# CNN based IoT Device Identification

# Overview
In this repository you will find a Python implementation of the methods in the paper [CNN based IoT Device Identification](https://arxiv.org/abs/2304.13894).

# Summary

While the use of the Internet of Things is becoming more and more popular, many security vulnerabilities are emerging with the large number of devices being introduced to the market. In this environment, IoT device identification methods provide a preventive security measure as an important factor in identifying these devices and detecting the vulnerabilities they suffer from. In this study, we present a method that identifies devices in the [Aalto dataset/IoT devices captures](https://research.aalto.fi/en/datasets/iot-devices-captures)  using the convolutional neural network (CNN).




# Requirements and Infrastructure: 

Wireshark and Python 3.10 were used to create the application files. Before running the files, it must be ensured that [Wireshark](https://www.wireshark.org/), [Python 3.10+](https://www.python.org/downloads/) and the following libraries are installed.

| Library | Task |
| ------ | ------ |
|[ Scapy ](https://scapy.net/)| Packet(Pcap) crafting |
|[ tshark ](https://www.wireshark.org/)| Packet(Pcap) crafting |
|[ Sklearn ](http://scikit-learn.org/stable/install.html)| Machine Learning & Data Preparation |
| [ Numpy ](http://www.numpy.org/) |Mathematical Operations|
| [ Pandas  ](https://pandas.pydata.org/pandas-docs/stable/install.html)|  Data Analysis|
| [ Scipy  ](https://pypi.org/project/scipy/)|  Data Analysis, Mathematical Operations|
| [ Matplotlib ](https://matplotlib.org/users/installing.html) |Graphics and Visuality|
| [Seaborn ](https://seaborn.pydata.org/) |Graphics and Visuality|
| [Keras ](https://keras.io/) |Deep Learning|



The technical specifications of the computer used for experiments are given below.


The technical specifications of the computer used for experiments are given below.

|  | |   |
| ------ |--|  ------ |
|Central Processing Unit|:|Intel(R) Core(TM) i7-7500U CPU @ 2.70GHz 2.90 GHz|
| Random Access Memory	|:|	8 GB (7.74 GB usable)|
| Operating System	|:|	Windows 10 Pro 64-bit |
| Graphics Processing Unit	|:|	AMD Readon (TM) 530|

# Data: 


# Full Datasets

The processed datasets are shared in depository. However, raw versions of the datasets used in the study and their addresses are given below.

| Dataset | capture year | Number of Devices | Type |
|---|---|---|---|
|[ Aalto University ](https://research.aalto.fi/en/datasets/iot-devices-captures)| 2016|31|Benign|





# License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details


# Citations
If you use the source code please cite the following paper:

```
@misc{kostas2023CNN,
      title={{CNN} based {IoT} Device Identification]}, 
      author={Kahraman Kostas},
      year={2023},
      eprint={2304.13905},
      archivePrefix={arXiv},
      primaryClass={cs.CR}
}
```

Contact:
*Kahraman Kostas
kahramankostas@gmail.com*


