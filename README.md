# Learning_transfer_CNN
This repository contains code about the transfer of learning (fine tuning) on ​​the VGG16 network in the MIT dataset: Indoor Scene Recognition.
The projects are separated by folders, with the name of the datasets.

# Contents
``` shell
.
├── colab_notebooks
│   ├── Transferência_de_Aprendizagem.ipynb
│   └── Transfer_Learning.ipynb
├── imgs
│   ├── img.png
│   ├── mimg.png
│   └── resimg.png
├── LICENSE
└── README.md

```
The **colab_notebooks** folder contains the python codes used in projects.The other folders follow the same pattern.

# Requirements

 * Check the **requirements.txt** file.


# Test

```shell
git clone https://github.com/gslmota/Learning_transfer_CNN.git
cd Learning_transfer_CNN
pip install -r requirements.txt
```

# Dataset

### **Indoor Scene Recognition** MIT dataset
"Indoor scene recognition is a challenging open problem in high level vision. Most scene recognition models that work well for outdoor scenes perform poorly in the indoor domain. The main difficulty is that while some indoor scenes (e.g. corridors) can be well characterized by global spatial properties, others (e.g., bookstores) are better characterized by the objects they contain. More generally, to address the indoor scenes recognition problem we need a model that can exploit local and global discriminative information." 
**MIT dataset description**.

![!cnn](https://github.com/gslmota/Learning_transfer_CNN/blob/main/imgs/img.png)

# Results

### **VGG16 pretrained**: 
* **CNN**. This project using a CNN VGG16 model pretrained with finetuning. With 5 category acuracy: 95%.

![!cnn](https://github.com/gslmota/Learning_transfer_CNN/blob/main/imgs/resimg.png)

### **VGG16 pretrained**: 
* **CNN**. This project using a CNN VGG16 model pretrained with finetuning. With 10 category acuracy: 93%.

![!cnn](https://github.com/gslmota/Learning_transfer_CNN/blob/main/imgs/mimg.png)

